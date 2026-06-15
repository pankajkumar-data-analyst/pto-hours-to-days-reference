# pto-hours-to-days-reference
PTO hours to days conversion chart and formula for HR professionals and employees
# PTO Hours to Days Conversion Chart


## Quick Reference (8-Hour Day)

| PTO Hours | Days | Weeks |
|-----------|------|-------|
| 40 | 5 | 1 |
| 72 | 9 | 1.8 |
| 80 | 10 | 2 |
| 88 | 11 | 2.2 |
| 100 | 12.5 | 2.5 |
| 120 | 15 | 3 |
| 152 | 19 | 3.8 |
| 160 | 20 | 4 |
| 192 | 24 | 4.8 |
| 200 | 25 | 5 |
| 240 | 30 | 6 |

## Different Shift Lengths

| PTO Hours | 8-hr day | 10-hr day | 12-hr day |
|-----------|----------|-----------|-----------|
| 80 | 10 days | 8 days | 6.7 days |
| 120 | 15 days | 12 days | 10 days |
| 160 | 20 days | 16 days | 13.3 days |

## Code

```javascript
function ptoHoursToDays(hours, hoursPerDay = 8) {
  return Math.round((hours / hoursPerDay) * 100) / 100;
}
Online Tool
For instant conversion with any shift length:

PTO Hours to Days Calculator:https://ptocalculatorhub.com/pto-hours-to-days-calculator/


ptoHoursToDays(152);     // 19
ptoHoursToDays(80, 10);  // 8
  
