# Data Quality Analysis Report: 2009-2018 Consolidation

## Executive Summary
This report analyzes the quality and integrity of the consolidated historical data.

### Key Statistics
- **Total Files Scanned**: 113
- **Total Records Processed**: 2558569
- **Total Unique Students Grouped**: 566022
- **MongoDB Collection Count**: *Pending Verification*
- **Records using Roll No Fallback** (Missing Enrollment): 223280
- **Garbage Records Skipped** (No ID): 228

## Data Quality Issues

### 1. Missing Enrollment Numbers
A significant number of records lacked a valid Enrollment Number. 
**Action Taken**: These records were grouped using their `Roll Number` prefixed with `ROLL-` to ensure they are captured and not discarded.
**Count**: 223280

### 2. Unmapped Subject Codes
The following Subject Codes were found in the data but did not match the Master Subject Map (derived from BU 2019+). 
These results retain their original code/name from the Excel sheet.
**Count**: 0
**Sample Codes**: []...

### 3. Semester Identification
Semester information was extracted from `EXAMNAME` where possible using regex patterns (e.g., "IV SEMESTER").
For records where this was ambiguous, the `Semester` field may be empty.

## Recommendations
1.  **MongoDB Storage**: The `Consolidated_2009_2018.json` file is structured identically to the `BU 2019+` format (`Students` dict with `Records` array) and is ready for direct insertion.
2.  **Fallback Review**: Review records with IDs starting with `ROLL-` to see if manual mapping to Enrollment Numbers is possible in the future.
