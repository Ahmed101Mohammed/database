# [Exercise: Employees with Department Info](https://relational.alexcole.net/learn/basic-operations)

Join Employee and Department to see which department each employee belongs to. 
Since both relations share "id" and "name" columns, you need to rename them 
first so only the foreign key column is shared.

> **Task:**    
> Rename Employee columns (id->emp_id, name->emp_name) and Department columns 
> (id->dept_id, name->dept_name), then natural join them on the shared dept_id 
> column  

Using dataset: Employee, Department

## Answer

```math
\rho_{
  \text{emp\_id} \leftarrow \text{id}, 
  \text{emp\_name} \leftarrow \text{name}
} (Employee)

\bowtie

\rho_{
  \text{dept\_id} \leftarrow \text{id}, 
  \text{dept\_name} \leftarrow \text{name}
} (Department)
```