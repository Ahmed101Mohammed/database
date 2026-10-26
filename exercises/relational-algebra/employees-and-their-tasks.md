# [Exercise: Employees and Their Tasks](https://relational.alexcole.net/learn/intermediate-operations)

FinA natural join matches two relations on every column they share. Employee 
and Task share exactly one column — dept_id — so joining them pairs each 
employee with the tasks in their department. No renaming needed here.

> **Task:**    
> Natural join Employee and Task to pair each employee with the tasks in their 
> department

Using dataset: Employee, Task

## Answer

```math
\text{Employee} \bowtie \text{Task}
```