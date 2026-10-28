\# Lab 5 - Static Code Analysis



\*\*Name:\*\* Debargho Banerji  

\*\*SRN:\*\* PES1UG24CS141  

\*\*Repository:\*\* L5\_15\_museum\_catalog



\## Issue Documentation



| No. | Tool | Issue Identified | Severity | Fix Applied |

|---|---|---|---|---|

| 1 | Bandit | Hard-coded curator password (B105) | Low | Removed the hard-coded password |

| 2 | Bandit | SQL injection vector through string-based query construction (B608) | Medium | Replaced SQL string concatenation with parameterized queries |

| 3 | Pylint | Unused datetime import | Warning | Removed the unused import |

| 4 | Pylint | Function names not following snake\_case | Convention | Renamed functions to snake\_case |

| 5 | Pylint | Unused curator argument | Warning | Removed the unused argument |

| 6 | Flake8 | Lines exceeding the maximum length | Style | Reformatted long lines |

| 7 | Flake8 | Missing whitespace around operators | Style | Corrected spacing |

| 8 | Pylint | Missing module and function docstrings | Convention | Added documentation strings |

| 9 | Bandit | Unnecessary shell invocation using subprocess | Security | Replaced subprocess call with print |

| 10 | Code inspection | Missing-row handling | Correctness | Added a check for missing database rows |

| 11 | Code inspection | Program runs on import | Maintainability | Added an if \_\_name\_\_ == "\_\_main\_\_": guard |



\## Verification



\- The program runs successfully.

\- Pylint score improved from 4.69/10 to 10.00/10.

\- Bandit reports no issues identified.

\- Flake8 reports no issues.



