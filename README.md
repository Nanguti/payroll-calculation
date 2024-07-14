# Payroll Calculations - Tanzania

## Understanding the Variables

-   **Gross Pay**: The total amount earned by the employee before any deductions.
-   **NSSF (10% of Gross Pay)**: Employee contribution towards the National Social Security Fund, calculated as 10% of Gross Pay.
-   **Taxable Income**: Gross Pay minus NSSF.
-   **PAYE (Pay As You Earn) tax**: Income tax deducted from the taxable income.
-   **Net Pay**: The amount the employee actually receives after all deductions.
-   **Fuel Allowance**: Fuel allowance.
-   **Advances**: Advances.
-   **HESLB deductions**: Higher Education Students' Loans Board deductions.
-   **Payroll Amount**: Total amount paid to the employee, including deductions.
-   **SDL (Statutory Deduction Levy)**: Statutory Deduction Levy, calculated as a percentage of Gross Pay.
-   **WCF (Work Injury Compensation Fund)**: Work Injury Compensation Fund, calculated as a percentage of Gross Pay.

## Formula Breakdown

### Deductions

1. **NSSF**:
   \[
   \text{NSSF} = \text{Gross Pay} \times 10\%
   \]

2. **PAYE**:

    - If Taxable Income ≤ 270,000: PAYE = 0
    - If 270,000 < Taxable Income ≤ 519,999:
      \[
      \text{PAYE} = (\text{Taxable Income} - 270,000) \times 8\%
      \]
    - If 520,000 ≤ Taxable Income ≤ 759,999:
      \[
      \text{PAYE} = (\text{Taxable Income} - 520,000) \times 20\% + 20,000
      \]
    - If 760,000 ≤ Taxable Income ≤ 999,999:
      \[
      \text{PAYE} = (\text{Taxable Income} - 760,000) \times 25\% + 68,000
      \]
    - If Taxable Income ≥ 1,000,000:
      \[
      \text{PAYE} = (\text{Taxable Income} - 1,000,000) \times 30\% + 128,000
      \]

3. **SDL**:
   \[
   \text{SDL} = \text{Gross Pay} \times 3.5\%
   \]

4. **WCF**:
   \[
   \text{WCF} = \text{Gross Pay} \times 0.5\%
   \]

### Net Pay Calculation

\[
\text{Net Pay} = \text{Taxable Income} - \text{PAYE} - \text{SDL} - \text{WCF} - \text{Fuel Allowance} - \text{Advances} - \text{HESLB deductions}
\]

### Payroll Amount

\[
\text{Payroll Amount} = \text{Net Pay} - \text{Advances} - \text{Fuel Allowance} - \text{HESLB deductions}
\]

## Summary of Formulas

-   **NSSF**:
    \[
    \text{NSSF} = \text{Gross Pay} \times 10\%
    \]

-   **SDL**:
    \[
    \text{SDL} = \text{Gross Pay} \times 3.5\%
    \]

-   **WCF**:
    \[
    \text{WCF} = \text{Gross Pay} \times 0.5\%
    \]

-   **Net Pay**:
    \[
    \text{Net Pay} = \text{Taxable Income} - \text{PAYE} - \text{SDL} - \text{WCF} - \text{Fuel Allowance} - \text{Advances} - \text{HESLB deductions}
    \]

-   **Payroll Amount**:
    \[
    \text{Payroll Amount} = \text{Net Pay} - \text{Advances} - \text{Fuel Allowance} - \text{HESLB deductions}
    \]
