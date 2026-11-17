SmartSalary 3.7.0 Free Offline — Created with care by Hurraim Khan
================================================================================
Professional Offline Personal Budgeting, Expense Tracker & Payroll System

QUICK START
1. Extract the SmartSalary-3.7.0-Free-Offline.zip folder.
2. Open the extracted folder in VS Code or any modern browser.
3. If using VS Code, click "Go Live" (Live Server) on index.html, or double-click index.html directly.
4. No account, sign-in, OTP, credit card, or internet connection is required.
5. All data is saved privately inside your browser's local storage on this device.

KEY FEATURES IN VERSION 3.7.0
1. New Update Screen & Onboarding Experience
   - Displays the official upgrade message:
     "Update SmartSalary to enjoy the latest features. Your saved details and records will remain safe and will not be erased."
   - Dynamic Salary Handling:
     * Existing users: Displays "You previously set your salary to Rs [saved salary]. We are keeping your existing salary and personal records unchanged."
     * New users: Displays demo starting salary of Rs 50,000 (editable).
   - Animated 5-second progress indicator (0% to 100%) during upgrade initialization.
   - Smooth transition into Welcome Screen, Personal Details, Updated App Guide, and Dashboard.
   - Guide Finish & Skip buttons navigate directly to the Overview/Dashboard screen ready for immediate use.

2. Personal Details Management
   - Added Employee Name and Designation fields.
   - Used cleanly in generated Salary Slips and reports without unnecessarily cluttering greetings.
   - Editable anytime from Settings or Salary Slip dialog.

3. Complete Salary & Payroll Management (5 Dedicated Cards)
   - Leaves This Month:
     * 26 working days calculation basis.
     * 4 Sundays regular weekly holidays.
     * 2 free allowed leaves per month.
     * Deductible leaves = Total leaves - 2 (minimum 0).
     * Leave deduction = Deductible leaves × Daily salary.
   - Sundays (Weekly Holiday Details) — MANUAL HOURS ENTRY:
     * Manual entry of date, hours worked, and note.
     * No automatic 8h/16h assignment.
     * No 2x multiplier or double payment.
     * Sunday Payment = Entered Hours × Standard Hourly Rate.
     * Standard Hourly Rate = Monthly Basic Salary ÷ 26 ÷ 9.
     * Full add, edit, and delete capability. Recalculates dynamically with salary.
   - Overtime — Extra Hours & Payment Record:
     * Manual overtime entry with date, extra hours, and note.
     * Payment = Extra Hours × (Standard Hourly Rate × 1.5).
     * Full add, edit, and delete capability.
   - Advance — Balance & Recovery:
     * Full advance ledger: add advances with date and reason.
     * Record monthly recovery amounts (capped at outstanding balance).
     * Outstanding balance carries forward across months.
   - Extra Pay — Bonus & Additional Earnings:
     * Record performance bonuses, festival gifts, and incentives.
     * Included accurately in monthly salary calculations.

4. Salary Slip Generation & 100% Offline PDF Download
   - "Generate Salary Slip" is present in only the two intended locations:
     1. Top header/action area beside the SmartSalary heading.
     2. Monthly Salary Slip section in Salary & Payroll.
   - Prompts for Employee Name and Designation if missing.
   - Excel-style clean, professional salary sheet preview.
   - Download genuine PDF 1.4 document generated completely offline via pure JavaScript!
   - Also includes direct Print Slip preview.
   - Saves permanent monthly salary snapshots in Monthly Records.
   - Creator credit: "By Hurraim Khan".

5. Eight New Improvements
   - Savings Goals Progress: Target, saved, remaining amount, percentage, and progress bar. Removed prefilled personal iPhone 13 Pro goal. Added placeholder: "e.g. Car, Bike, House".
   - Monthly Expense Summary: Dedicated breakdown table showing category budget, spent, remaining, and % used.
   - Search & Filter: Real-time search across expenses and monthly records (by month name, year, and employee name).
   - Low Savings Alert: Visual gentle reminder on goals that are behind schedule (< 25%).
   - Edit History: Audit trail recording key changes with old and new values and rollback options.
   - Backup Reminder: Friendly offline reminder banner if no backup has been created in > 14 days.
   - Dashboard Improvements: Preserved existing colors and themes while enhancing spacing and readability.
   - Empty Screen Design: Beautiful, clean empty states with icons and action buttons across all lists.

6. Strict Main Navigation Order
   1. Overview
   2. Expenses
   3. Salary & Payroll (Priority feature, tab #3)
   4. Extra Income
   5. Savings Goals (Tab #5)
   6. Monthly Records
   7. Backup / Restore

7. Creator Branding & Authentic Profile Picture
   - Authentic profile picture of creator Hurraim Khan (Hurraim_Khan_Profile_Round(1).png).
   - Displayed immediately before "Hurraim Khan" wherever creator credit appears:
     "Created with care by Hurraim Khan"
   - Caching enabled in sw.js for 100% offline access.

8. Complete Multi-language Support
   - Full English (LTR) and Urdu (RTL) interface with instant switching.
