# ExerciciosSQL_Oracle

## Exercícios de SQL no Oracle (utilizando o Schema HR)

<br>

1 – Selecione todos os ids, nomes e sobremedos de empregados,
que estajam nas faixas de salários de 0 a 2000 e maiores ou iguais a 5000.

SELECT EMPLOYEE_ID, FIRST_NAME, LAST_NAME, SALARY
FROM EMPLOYEES
WHERE SALARY BETWEEN 0 AND 2000
OR SALARY >= 5000

<br>

2 – Selecione todos os ids e nomes de departamentos,
o id do gerente do departamento que estejam no id de locais entre 1500 a 2000;

SELECT DEPARTMENT_ID, DEPARTMENT_NAME,
MANAGER_ID, LOCATION_ID
FROM DEPARTMENTS
WHERE LOCATION_ID BETWEEN 1500 AND 2000;
