# Reading Notes Class 12

## EJS partials

1. Partials are where you want to reuse pieces of code and specific functions across your entire site, but don't want to rewrite it. You just redefine the bundle of code and include it where you need it. For example, using the same header and footer across multple pages of the same website. You just define the partials, and then can use it easier in those multple areas you need to use it in, it's a very straightforward way of reusing code.

## EJS paritals

1. An ad bar or a footer, reusable pieces of text that stay static. We can use a single dash, and it will include a particular file named partials, and a file within called onepartial. Inside this, you enter your code, and it becomes reusable in the rest of the codebase. 
`<%- include ('partials/onepartial') %>`
