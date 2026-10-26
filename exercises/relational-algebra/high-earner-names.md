# [Exercise: High Earner Names](https://relational.alexcole.net/learn/basic-operations)

Find the names of employees who earn more than $85,000. This combines selection 
(to filter) and projection (to extract names).

> **Task:**    
> Write an expression that first selects high earners, then projects their 
> names  

Using dataset: Employee

## Answer

```math
\pi_{\text{name}} (\sigma_{salary > 85000} (Employee))
```