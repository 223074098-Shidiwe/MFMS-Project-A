Municipal Financial Management System (MFMS)

Project Title
Municipal Financial Management System — Project A (Foundation System)

 Course
PAP521S — Programming in Practice

Group Number
Group 8

## Group Members
| Name | Student Number | Responsibility |
|------|----------------|----------------|
| Jose Carlos Mutongolume | 226054179 | Employee Management |
| Matias Joseph | 226065669 | Budget Management |
| Esther Haihambo | 226041352| Budget Management |
| Mukanwa Matta| 223023205| Supplier Management |
| Mukanwa Mataa | 223023205 | Asset Management |
| Christiaan Shidiwe | 223074098 | Testing, Documentation & Git Coordination |
| Esala Amunyela | TBC | Functions, Integration & Validation |

 Project Description
MFMS is a menu-driven C application developed for a municipality.
It manages employees, budgets, suppliers, and assets, and produces
basic reports. It is the foundation version that will be extended in Project B.

System Features
1. Main Menu (Employee, Budget, Supplier, Asset, Reports, Exit)
2. Employee Management — add, display, search, calculate salary
3. Budget Management — allocate, capture expenditure, show remaining, flag overspend
4. Supplier Management — add, display, search
5. Asset Management — add, display, search
6. Reports — Employee, Budget, Supplier, Asset reports
7. Input validation (no negative salary/budget, invalid menu handled, empty names rejected)


gcc -std=c99 -Wall -o mfms main.c employees.c budget.c suppliers.c assets.c reports.c
