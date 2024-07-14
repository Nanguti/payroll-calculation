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

-   **NSSF**:
    -NSSF = Gross Pay \* 10%

-   **PAYE**:

-   If Taxable Income ≤ 270,000: PAYE = 0
-   If 270,000 < Taxable Income ≤ 519,999:
    ```
    PAYE = (Taxable Income - 270,000) * 8%
    ```
-   If 520,000 ≤ Taxable Income ≤ 759,999:
    ```
    PAYE = (Taxable Income - 520,000) * 20% + 20,000
    ```
-   If 760,000 ≤ Taxable Income ≤ 999,999:
    ```
    PAYE = (Taxable Income - 760,000) * 25% + 68,000
    ```
-   If Taxable Income ≥ 1,000,000:

    ```
    PAYE = (Taxable Income - 1,000,000) * 30% + 128,000
    ```

-   **SDL**:
    -SDL = Gross Pay \* 3.5%

-   **WCF**:
    -WCF = Gross Pay \* 0.5%

### Net Pay Calculation

-Net Pay = Taxable Income - PAYE - SDL - WCF - Fuel Allowance - Advances - HESLB deductions

### Payroll Amount

-Payroll Amount = Net Pay - Advances - Fuel Allowance - HESLB deductions

## Summary of Formulas

-   **NSSF**: NSSF (10% of Gross Pay) = Gross Pay \* 10%

-   **SDL**: SDL = Gross Pay \* 3.5%

-   **WCF**: WCF = Gross Pay \* 0.5%

-   **Net Pay**: Net Pay = Taxable Income - PAYE - SDL - WCF - Fuel Allowance - Advances - HESLB deductions

-   **Payroll Amount**: Payroll Amount = Net Pay - Advances - Fuel Allowance - HESLB deductions
