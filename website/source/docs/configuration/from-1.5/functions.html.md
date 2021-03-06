---
layout: "docs"
page_title: "Functions - Configuration Language"
sidebar_current: "configuration-functions"
description: |-
  The HCL language has a number of built-in functions that can be called
  from within expressions to transform and combine values.
---

# Built-in Functions

The HCL language includes a number of built-in functions that you can
call from within expressions to transform and combine values. The general
syntax for function calls is a function name followed by comma-separated
arguments in parentheses:

```hcl
max(5, 12, 9)
```

For more details on syntax, see
[_Function Calls_](./expressions.html#function-calls)
on the Expressions page.

The HCL language does not support user-defined functions, and so only
the functions built in to the language are available for use. The navigation
for this section includes a list of all of the available built-in functions.
