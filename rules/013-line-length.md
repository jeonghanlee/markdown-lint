---
title: MD013 - Line length
tags:  [line_length]
alias: line-length
---

Parameters: line_length, code_blocks, tables (number; default 80, boolean; default true)

This rule is triggered when there are lines that are longer than the
configured line length (default: 80 characters). To fix this, split the line
up into multiple lines.

This rule has an exception where there is no whitespace beyond the configured
line length. This allows you to still include items such as long URLs without
being forced to break them in the middle.

You also have the option to exclude this rule for code blocks and tables. To
do this, set the `code_blocks` and/or `tables` parameters to false.

Code blocks are included in this rule by default since it is often a
requirement for document readability, and tentatively compatible with code
rules. Still, some languages do not lend themselves to short lines.

