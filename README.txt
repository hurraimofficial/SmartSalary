SmartSalary 3.6.0 Free Offline — Created with care by Hurraim Khan
================================================================================
Professional Offline Personal Budgeting, Expense Tracker & Payroll System

QUICK START
1. Extract the SmartSalary-3.6.0-Free-Offline.zip folder.
2. Open the folder in VS Code or any modern browser.
3. If using VS Code, click "Go Live" (Live Server) on index.html, or double-click index.html directly.
4. No account, sign-in, OTP, credit card, or internet connection is required.
5. All data is saved privately inside your browser's local storage on this device.

KEY FEATURES IN VERSION 3.6.0
1. Welcome Screen & Interactive Guided Tour
   - Welcomes users on first launch with demo salary (PKR 50,000).
   - Step-by-step interactive application guide with Next, Back, and Skip controls.
   - Progress indicators and instant reopen capability from the three-dot menu.

2. Personal Branding & Creator Credit
   - Authentic profile picture of creator Hurraim Khan (Hurraim_Khan_Profile_Round(1).png).
   - Circular avatar placed immediately before "Hurraim Khan" wherever creator credit appears:
     "Created with care by Hurraim Khan"
   - Displayed on Welcome screen, App Guide branding, Footer, About section, and Offline dialog.

3. Strict Main Navigation Order
   The 7 primary application tabs are arranged in this exact order:
   1. Overview
   2. Expenses
   3. Salary & Payroll (Priority feature, tab #3)
   4. Extra Income
   5. Savings Goals (Tab #5)
   6. Monthly Records
   7. Backup / Restore

4. Three-Dot Menu (⋮) in Header
   - Fully responsive, aligned on the same horizontal line as the brand title on mobile.
   - Contains:
     1. Language: Instant toggle between English and Urdu (اردو) with bidirectional LTR/RTL support.
     2. Offline Support: Accessible offline status, local storage verification, and PWA installation state.
     3. App Guide: Reopen the animated interactive onboarding guide anytime.
     4. Settings: Switch between Rupee Amount mode (PKR) and Percentage mode (%), manage base and custom categories.
     5. About SmartSalary: Version details, creator credit, and privacy/terms links.

5. Professional Overview Dashboard
   - Budget categories immediately visible with crisp SVG icons.
   - Financial overview: Monthly Basic Salary, Total Allocated Budget, Unallocated Amount, Total Expenses, and Net Remaining Balance.
   - Dynamic progress bars with category color accents.
   - Carryover savings summary from previous months.

6. Professional Category SVG Icons
   - Replaced ordinary emojis with consistent, lightweight inline SVG icons for:
     * Household
     * Personal
     * Committee
     * Emergency Fund
     * Family Extra
     * Car/Bike
     * Custom categories
   - 100% vector, responsive, fully offline.

7. Flexible Budget Calculation Modes
   - Default mode: Fixed Rupee amounts (PKR).
   - Optional mode: Percentage allocation (%).
   - Live calculations for category allocations, total allocations, unallocated salary, and remaining balance.
   - Clear warning banners and allocation caps preventing allocations exceeding 100% of salary.
   - Mutually exclusive Car/Bike and Family Extra budget categories.
   - Support for up to 10 total categories with safe add, edit, and delete functionality.

8. Comprehensive Salary & Payroll System
   - Daily Salary Calculation based on 26 working days (Monthly Salary ÷ 26).
   - Leave Rules:
     * 2 leaves allowed free of deduction.
     * Deductible leaves = Total leaves - 2 (minimum 0).
     * Leave deduction = Deductible leaves × Daily salary.
   - Salary Advance Ledger:
     * Add new advance with date and description.
     * Record monthly repayment/recovery (capped at outstanding balance).
     * Formula: Outstanding Advance = Total Advances - Total Recoveries.
     * Persistent advance ledger automatically carries forward balances across months.
     * Advances are never treated as normal income or erased upon month turnover.
   - Payroll Summary:
     * Basic Monthly Salary
     * Extra Income & Attendance Bonus
     * Leave Deductions
     * Advance Recovery
     * Other Deductions
     * Net Payable Salary

9. Data Safety & Backward Compatibility
   - Preserves existing data from versions 3.4.3, 3.2, 3.1, 3.0, and 2.0.
   - Automatic migration of older localStorage keys with full backward compatibility.
   - Up to 7 automatic local recovery snapshots stored before modifications.
   - Complete JSON Export & Import utility.

10. PWA & Offline Support
   - Service worker caches app shell and profile image (smartsalary-offline-v360).
   - Installable as a standalone progressive web app on Android, iOS, Windows, and macOS.
