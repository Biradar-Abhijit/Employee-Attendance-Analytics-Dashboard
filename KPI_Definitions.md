# KPI Definitions

## Total Employees
Count of unique employees.

## Present
Employee-day records classified as Present.

## Leave
Employee-day records with code `L`.

## Absent
Employee-day records with code `A`.

## Week Off
Employee-day records classified as Week Off:
- Monday
- W
- E
- K
- F

## Work Hours
Sum of recorded working hours.

## Attendance %
```text
Present / (Present + Leave + Absent) × 100
```

Week-off records are excluded.

## Data Structure
Each row in the cleaned attendance table represents:
`One employee + One date`
