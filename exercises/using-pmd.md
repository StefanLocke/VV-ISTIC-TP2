# Using PMD

Pick a Java project from Github (see the [instructions](../sujet.md) for suggestions). Run PMD on its source code using any ruleset. Describe below an issue found by PMD that you think should be solved (true positive) and include below the changes you would add to the source code. Describe below an issue found by PMD that is not worth solving (false negative). Explain why you would not solve this issue.

## Answer

One true positive is the LooseCoupling, this clause asks developers to used interfaces to external libraries instead of hard coded dependencies such as ArrayList instead of list on list declaration.

One problem not really worth solving is the UselessParentheses case. These parentheses are, usually, used for better code clarity for humans.
