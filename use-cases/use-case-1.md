# USE CASE: 1 Generate Salary Report for All Employees

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to produce a report on the salary of all employees so that I can support financial reporting of the organization.*

### Scope

Company.

### Level

Primary task.

### Preconditions

The database contains current employee salary data.

### Success End Condition

A comprehensive report containing salary information for all employees is available for HR to provide to finance.
### Failed End Condition

No report is produced.

### Primary Actor

HR Advisor.

### Trigger

A request for finance information is sent to HR.

## MAIN SUCCESS SCENARIO

1. Finance requests salary information for all employees.
2. HR advisor initiates the process to generate a salary report for all employees.
3. HR advisor executes a query to retrieve current salary information for all employees.
4. HR advisor provides report to finance.

## EXTENSIONS

3. **No Salary Data Available**:
    1. HR advisor informs finance that no salary data is available for the employees.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0