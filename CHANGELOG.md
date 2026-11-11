# Shift & Stub Tracker – version history

Version numbers: MAJOR.MINOR.PATCH
- MAJOR: big changes (new agreement, new app structure)
- MINOR: new features
- PATCH: fixes and small changes

## v2.3.0 – November 10, 2026
Ideas borrowed from the Overtime Tracker app.
- Check-off: tick each shift once it shows on a pay stub (stub date filled in, amount optional). Shifts show Waiting, ✓ On stub, Scheduled, or "payday passed · not ticked".
- Filter shifts by Waiting / On stub / All.
- "Tick off N shifts" button once a pay period's stub is entered or its payday has passed.
- "Waiting for stub" tile on Home: pay not yet ticked off, and how many shifts are past payday.
- Tap a shift to edit it, add a note, or delete it.
- Backup chip counts changes since the last backup (Back up • 3); tap it to back up.
- After an update, a "what's new" note on Home; also in Settings.
- Restore can add only what's missing (keeps your data) or replace everything.

## v2.2.0 – November 3, 2026
New look and a Year screen, built from the approved mockups.
- New iPhone-style design: large titles, frosted tab bar with icons (Home, Pay, Calendar, Seniority, Settings), dark mode.
- Home: payday card with take-home (estimate, or the stub amount once entered), days to payday, Auxiliary/FSW split, gross and deductions; tiles for the 1,000-hour ring, hours this period and the next stat holiday; shifts with what each one earns.
- Swipe a shift left (or tap ×) to delete it.
- Add a shift: floating + button opens a sheet with quick picks, big time fields and a live "this shift earns" preview that counts overtime, premium and in lieu.
- Quick picks: save shifts you work often; manage them in Settings.
- Pay › Year: take-home so far, gross, deductions breakdown, take-home per cheque chart, pay history with Match/Close/Off/Estimate.
- Year-to-date starting point (from any stub) replaces the old CPP/EI starting point, and a check of the stub's Year to Date column.
- Calendar: paydays marked; tapping a day pops up its shifts and earnings.
- No changes to the pay calculations (76 checks pass).

## v2.1.0 – November 3, 2026
New: Calendar tab.
- Month calendar showing every day worked, colour coded: teal = non-union, amber = FSW · Union, split = both jobs that day.
- Each day shows total hours; stat holidays shown in red; today outlined.
- Tap a day to see the shifts: job, times, break, pay type and hours, with totals per job.
- "Add a shift on this day" button from the day view.
- Month totals: days worked, non-union hours and union hours.

## v2.0.2 – November 3, 2026
Fixes from comparing the app with the November 2026 pay stub.
- Union dues set to 1.9%, worked out from the stub ($8.60 on $452.74). Dues are now taken from union pay without the in-lieu-of-benefits amount. The reminder stays until a second stub confirms it.
- BC income tax uses the CRA's July–December 2026 payroll figures (prorated 6.14% lowest rate, tax reduction up to $805). January–June 2026 and 2027 use their own figures.
- Result on the November stub: CPP, EI, dues and federal tax match; BC tax within $0.30; net pay within $0.30.

## v2.0.1 – November 3, 2026
First numbered release.
- Two jobs: non-union auxiliary (12% in lieu) and Facility Service Worker – Auxiliary (union).
- Union pay follows the Richmond Olympic Oval / CUPE 718-09 agreement (2024–2028), hard-coded:
  - Hourly rate by date: $22.59 (Jul 1 2024), $23.49 (Jul 1 2025), $24.31 (Jul 1 2026), $25.16 (Jul 1 2027).
  - Shift differential $1.00/h, 7 pm–7 am (Art. 7.06).
  - Overtime 1.5× past 8 h/day or 40 h/week; 2× past 12 h/day or 48 h/week (Art. 9.01).
  - Stat holidays worked paid at overtime rates, Boxing Day included (Art. 11.01, 11.06).
  - In lieu of benefits 12%, rising to 16% after 1,000 hours (Art. 7.05).
  - Paid meal break option (LOU #1).
- Seniority tab: running total, 1,000-hour progress, seniority list check, 183-day inactivity warning.
- Pay check tab: expected pay with 2026 CPP, EI, federal and BC tax; compare with the pay stub.
- Works offline on iPhone; data stays on the phone; backup and restore.
- Version number shown at the bottom of Settings; backups record the version that made them.
