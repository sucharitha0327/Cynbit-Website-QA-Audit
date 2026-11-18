
# Cynbit Website – Bug and Issue Report

## 1. Project Information
- **Project:** Cynbit Website Quality Audit
- **Testing Type:** Manual Testing
- **Website:** https://cynbit.in/
- **Status:** Testing Completed

## 2. Identified Issue

### BUG-001: Incorrect Return to Site Navigation

| Field | Details |
|---|---|
| Bug ID | BUG-001 |
| Module | Newsletter |
| Test Cases | TC073 (Desktop), TC138 (Mobile) |
| Title | Return to Site navigates to Contact page |
| Preconditions | User has opened the newsletter section |
| Steps to Reproduce | 1. Open the Cynbit website. 2. Open the newsletter section. 3. Click Return to Site. |
| Expected Result | User should be redirected to the intended main website landing page. |
| Actual Result | User is redirected to the Contact page. |
| Severity | Low (provisional) |
| Priority | Medium (provisional) |
| Status | Open – Requires confirmation of intended destination |

## 3. Pending Verification

### TC019 – Phone Number Validation
- **Module:** Contact Form
- **Status:** Pending
- **Observation:** Phone number validation requires further verification.
- **Recommendation:** Confirm whether a phone number field is available and test its validation behavior.

## 4. Recommendations
1. Verify the intended destination of the Return to Site link.
2. Correct the navigation destination if it is not intended to open the Contact page.
3. Verify phone number field availability and validation requirements.
4. Perform additional cross-browser and device testing.

## 5. Summary
One navigation issue was observed in both desktop and mobile testing. It is recorded as one issue linked to two test cases. Phone number validation remains pending further verification.
