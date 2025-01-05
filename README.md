# Tailwind CSS @apply Directive Issue with Pseudo-selectors

This repository demonstrates a common issue encountered when using Tailwind CSS's `@apply` directive with pseudo-selectors like `:hover` and `:focus`.  The `@apply` directive does not correctly apply the styles for these pseudo-selectors. This example shows the bug and how to properly apply the styles without using `@apply`.

## Bug

The `bug.html` file demonstrates the incorrect usage of `@apply` with a hover pseudo-selector, which fails to apply the hover styles. 

## Solution

The `bugSolution.html` file shows the correct approach where hover styles are directly applied to the button element. 