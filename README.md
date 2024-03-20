GIVEN an employee payroll tracker
WHEN I click the "Add employee" button
THEN I am presented with a series of prompts asking for first name, last name, and salary
![image](https://github.com/jlcastro1877/payRoll/assets/161878013/0ab98c89-37a4-44f2-9439-d011a6a5e081)
![image](https://github.com/jlcastro1877/payRoll/assets/161878013/648e53ca-6e02-4c8c-9c2c-bb1757ae74e2)
![image](https://github.com/jlcastro1877/payRoll/assets/161878013/90acbfdc-53c2-4377-990b-2d1e1631caec)

WHEN I finish adding an employee
THEN I am prompted to continue or cancel
![image](https://github.com/jlcastro1877/payRoll/assets/161878013/42ac6579-b035-42c3-b914-3b1f82212d53)

WHEN I choose to continue
THEN I am prompted to add a new employee
![image](https://github.com/jlcastro1877/payRoll/assets/161878013/948a6846-e463-45d1-8f6b-7fb32b651ee1)
![image](https://github.com/jlcastro1877/payRoll/assets/161878013/1f1e001d-934d-4f7a-ab1d-87785cf2fbce)

WHEN I choose to cancel
THEN my employee data is displayed on the page sorted alphabetically by last name, and the console shows computed and aggregated data
![image](https://github.com/jlcastro1877/payRoll/assets/161878013/b3f82859-094c-4bcf-aeb0-4052d27f3a73)


WHEN I inspect the page
Then I can see the average salary between the employes and the random employee
![image](https://github.com/jlcastro1877/payRoll/assets/161878013/29fcb2fe-03a6-4885-acfe-9c011a9193ad)

