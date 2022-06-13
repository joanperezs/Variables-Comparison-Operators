# Variable and Comparison Operators
### Hecho por Joan Pérez Susidko

## Task 1
Assign a variable with each datatypes covered in the previous workshop
```
$BoolanVar = $True
$StringVar = "This is a string"
$IntVar = 42
``` 
![image](https://user-images.githubusercontent.com/101748401/173260615-80e583ad-6109-45f2-8596-1cb9c3fe54a9.png)

## Task 2
List all variables currently loaded in to memory.
```
Get-Variable
```
![image](https://user-images.githubusercontent.com/101748401/173260709-993aaa28-aaab-4a8f-bd2b-00684f5661bc.png)

## Task 3
Multiple two Int variables together
PowerShell can perform basic maths operators, such as “+”, “-“ and “*”
```
$IntVar1 = 4
$IntVar2 = 10
$IntVar1 * $IntVar2
```
![image](https://user-images.githubusercontent.com/101748401/173260752-965d9de1-42d4-4841-8e2c-4a8b5b7ed32b.png)

## Task 4
First declare two Int variables. Then divided the first
variable by the second and assign the result to a
variable named $VariableResult
```
$IntVar3 = 10
$IntVar4 = 2

$VariableResult = $IntVar3 / $IntVar4
```
![image](https://user-images.githubusercontent.com/101748401/173260797-30105f4e-8c12-485b-a050-f432bf38655a.png)

## Task 5
Typecast a Variable as a “String” and assign it a value of 5
Remember to normal brackets [] rather than curly brackets {} when
typecasting a variable
```
[String]$TypecastVar = 5
```
![image](https://user-images.githubusercontent.com/101748401/173260851-bf4ba160-337f-46e6-8489-9ab22ce2fe83.png)
