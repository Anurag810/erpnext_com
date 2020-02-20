<!-- add-breadcrumbs -->
# Additional Salary

**Additional Salary is something that an Employee receives from the company they work for, other than their usual pay.**


ERPNext offers you a feature called Additional Salary to add or deduct adhoc salary for a particular Employee while processing the Payroll. Some examples of Additional Salary could be Performance Bonus, Deputation Allowance, Arrears, Incentives or other adjustments.

To access Additional Salary, go to:

> Home > Human Resources > Payroll > Additional Salary

## 1. Prerequisites

Before creating a Job Offer, it is advisable to create the following:

* [Employee](/docs/user/manual/en/human-resources/employee)
* [Salary Component](/docs/user/manual/en/human-resources/salary-component)


## 2. How to create an Additional Salary

To create a new Additional Salary:

1. Go to Additional Salary list, click on New.
2. Select Employee.
3. Select Salary Component.
4. Enter the Amount.
1. Enter the Payroll Date. If Payroll Date for Additional Salary is in the interval when the salary is processed, it will be added to the earnings/deduction.
1. Save and Submit.

Select the 'Overwrite Salary Structure Amount' checkbox to overwrite the Additional Salary component on the Salary Structure amount. Addtionally, the 'Deduct Full Tax on Selected Payroll Date' checkbox can be selected if full tax needs to be deducted on the Additional Salary component for that particular payroll date.

<img class="screenshot" alt="Additional Salary" src="{{docs_base_url}}/assets/img/human-resources/additional-salary.png">

## 3.Features

### 3.1 Recurring Additional Salary
This feature allows users to create an Additional Salary for a fixed interval.
If 'Is Recurring' is checked then you need to fill To Date and From Date. The Additional Salary will be repeated for every month between From Date to To Date interval and it will be reflected in Salary Slip for that employee.

## 4. Related Topics

1. [Retention Bonus](/docs/user/manual/en/human-resources/retention-bonus)
1. [Employee Incentive](/docs/user/manual/en/human-resources/employee-incentive)
1. [Salary Structure](/docs/user/manual/en/human-resources/salary-structure)
1. [Salary Structure Assignment](/docs/user/manual/en/human-resources/salary-structure-assignment)
1. [Payroll Entry](/docs/user/manual/en/human-resources/payroll-entry)
1. [Payroll Period](/docs/user/manual/en/human-resources/payroll-period)


{next}
