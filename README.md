# MLang (v1.7.1): The Mathematics Language
THIS IS ON THE GITHUB PAGES BRANCH
## What is M

#### M is an open-source language that is meant to help people learn about Tokenizers, Parsers, and interpreters. It supports variables, logging, and expressions.

## Project Status

#### Version: v1.7.1
-   Scopes

## Known Bugs
-   [ ] PENDING: Unary expressions don't work in conversions (`-23 => c, f` is read as `23 => c, f`)
-   [x] FIXED: Unknown bug (Cause: This bug seems to be caused by the new feature which makes it possible for expressions to be split with `;`)
-   [x] FIXED: Things like `let a = 5; -a` is read as `let a = 5-a` which causes an error due to 'a' being undefined. (This will still happen if you do something like `let a = 5 -a`)

## To-Do (in order from Most Important to Least Important)
-   [ ] Scopes
-   [ ] For & (Do)? While Loop

-   [ ] HTTP Module (Possible, but unexpected)

## Canceled Ideas (maybe in the future?)
-   [ ] Arrays (Priority: HIGH)

## Done
-   [x] Operations like `varName += 5`
-   [x] Better `import`/`export`
-   [x] Multiple arguments in functions (util.arg, util.arg1, util.arg2 || $pid, $pid1, $pid2)
-   [x] Javascript API (Priority: extremely low / not expected soon)
-   [x] Pseudo-pointers / Reference to `$pid` (passed in variable to a function) and `$last` (last variable set) (Priority: unexpected)
-   [x] Conditional statements (Priority: HIGH)
-   [x] Multi-line comments (Priority: extremely low)
-   [x] Export keyword (Priority: unknown)
-   [x] Import files (Priority: unknown)
-   [x] Minimal string support (Priority: unknown)
-   [x] Functions (Priority: Medium)
-   [x] Unit Conversion (Priority: unknown)
-   [x] Expressions (Priority: HIGH)
-   [x] Variables (Priority: Medium)
-   [x] Logging (Priority: Low)
-   [x] Built-in Functions (Priority: unknown)

## Want a tutorial on how you can make your own language?

### Well, are you in luck! I've recently created a tutorial for making [a simple number interpreter from scratch](https://number-interpreter-from-scratch.battledash2.repl.co).

#### Check it out!
