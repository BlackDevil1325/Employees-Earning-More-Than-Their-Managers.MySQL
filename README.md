# Employees-Earning-More-Than-Their-Managers.MySQL






# Write your MySQL query statement below
SELECT 
    e.name AS Employee         
FROM 
    Employee e                
INNER JOIN 
    Employee m                 
ON 
    m.id = e.managerId   
WHERE     
    e.salary > m.salary;      
    
