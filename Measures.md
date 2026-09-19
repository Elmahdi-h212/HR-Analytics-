# DAX Measures

Table utilisée : `HR_RAW`

## Total Employees

```DAX
Total Employees =
COUNTROWS(HR_RAW)
```

## Active Employees

```DAX
Active Employees =
CALCULATE(
    [Total Employees],
    HR_RAW[Status] = "Active"
)
```

## Terminated Employees

```DAX
Terminated Employees =
CALCULATE(
    [Total Employees],
    HR_RAW[Status] = "Terminated"
)
```

## Average Age

```DAX
Average Age =
AVERAGE(HR_RAW[Age])
```

## Average Salary

```DAX
Average Salary =
AVERAGE(HR_RAW[Salary])
```

## Average Employee Score

```DAX
Average Employee Score =
AVERAGE(HR_RAW[EmployeeScore])
```

## Total Sick Leave

```DAX
Total Sick Leave =
SUM(HR_RAW[SickLeaveDays])
```

## Total Vacation Leave

```DAX
Total Vacation Leave =
SUM(HR_RAW[VacationLeaveDays])
```
