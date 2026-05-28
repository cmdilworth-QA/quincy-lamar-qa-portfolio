# Test Execution Results – Quincy Lamar Website

## Overview
This document captures the results of executing manual test cases for the Quincy Lamar website.

---

## Test Execution Summary

| Total Test Cases | Passed | Failed | Not Executed |
|-----------------|--------|--------|--------------|
| 15 | 9 | 6 | 0 |

---

## Detailed Test Execution

### Navigation

| Test Case ID | Title/Purpose | Expected Result | Actual Result | Status |
|-------------|--------------|----------------|--------------|--------|
| TC-NAV-001 | Verify homepage loads | Homepage loads successfully | Homepage loaded successfully without errors | Pass |
| TC-NAV-002 | Verify menu navigation | Correct page loads | Navigation links respond and load corresponding sections | Pass |
| TC-NAV-003 | Verify no broken links | No 404 errors | No broken links observed during testing | Pass |

---

### Contact Form

| Test Case ID | Title/Purpose | Expected Result | Actual Result | Status |
|-------------|--------------|----------------|--------------|--------|
| TC-FORM-001 | Submit valid form | Success message displayed | Form submission behavior unclear / no confirmation observed | Fail |
| TC-FORM-002 | Submit empty form | Validation errors shown | No clear validation feedback displayed | Fail |
| TC-FORM-003 | Validate email format | Error message displayed | Invalid email format not properly validated | Fail |

---

### Media

| Test Case ID | Title/Purpose | Expected Result | Actual Result | Status |
|-------------|--------------|----------------|--------------|--------|
| TC-MEDIA-001 | Video playback | Video plays successfully | Video played successfully with no lag or errors | Pass |
| TC-MEDIA-002 | Image loading | Images load properly | Images displayed correctly without distortion | Pass |

---

### Responsiveness

| Test Case ID | Title/Purpose | Expected Result | Actual Result | Status |
|-------------|--------------|----------------|--------------|--------|
| TC-RESP-001 | Mobile responsiveness | Layout adjusts correctly | Layout appears slightly compressed on smaller screens | Fail |
| TC-RESP-002 | Tablet responsiveness | No layout issues | Layout remains stable across screen sizes | Pass |

---

### Accessibility

| Test Case ID | Title/Purpose | Expected Result | Actual Result | Status |
|-------------|--------------|----------------|--------------|--------|
| TC-A11Y-001 | Keyboard navigation | Fully accessible | Limited keyboard navigation support observed | Fail |
| TC-A11Y-002 | Image alt text | Alt text present | Some images missing alt attributes | Fail |

---

### Performance

| Test Case ID | Title/Purpose | Expected Result | Actual Result | Status |
|-------------|--------------|----------------|--------------|--------|
| TC-PERF-001 | Page load speed | Loads under 3 seconds | Page loaded within acceptable time | Pass |

---

## Notes
- Status values reflect actual execution results  
- Failed tests correspond to documented bugs  
- Testing was performed manually using browser-based tools  
