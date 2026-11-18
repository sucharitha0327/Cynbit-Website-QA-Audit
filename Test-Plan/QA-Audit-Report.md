
# Cynbit Website – QA Audit Report

## 1. Project Overview
- **Project:** Cynbit Website Quality Audit
- **Testing Type:** Manual Testing
- **Website:** https://cynbit.in/
- **Testing Status:** Testing Completed

## 2. Objective
To evaluate the Cynbit website's functionality, navigation, usability, responsiveness, accessibility, and basic performance.

## 3. Scope of Testing
- Homepage and company pages
- Company, Expertise, and BitElevate navigation
- Contact page and contact form
- Newsletter section
- Footer links and social media links
- Mobile and tablet responsiveness
- Keyboard accessibility
- Basic browser console and network checks
- HTTPS verification

## 4. Test Environment
- Operating System: Windows 11
- Browser: Google Chrome
- Desktop: Desktop browser
- Mobile: Mobile device and Chrome responsive preview
- Tablet: Chrome responsive tablet preview

*Exact device models, browser versions, and screen resolutions were not recorded.*

## 5. Testing Methodology
Manual testing was performed by:
- Navigating through website pages and menus.
- Checking buttons, links, and dropdown menus.
- Testing contact form input and validation.
- Checking newsletter functionality.
- Verifying mobile and tablet layouts.
- Checking keyboard navigation and image alternative text.
- Observing browser console and network requests.
- Verifying HTTPS connection.

## 6. Test Execution Summary
- Test cases recorded: TC001 to TC140.
- Most executed checks passed.
- Two test cases failed due to the same navigation issue.
- Phone number validation (TC019) remains pending.
- Some repeated checks may be consolidated during final review.

## 7. Issues Identified

### Issue 01 – Return to Site Navigation

- **Test Cases:** TC073 (Desktop), TC138 (Mobile)
- **Module:** Newsletter
- **Expected Result:** Return to Site should navigate to the intended main website landing page.
- **Actual Result:** Clicking Return to Site navigates to the Contact page on both desktop and mobile.
- **Status:** FAIL – Intended destination requires confirmation.
- **Severity:** Low (provisional)
- **Recommendation:** Verify the intended destination and correct the link if necessary.

## 8. Accessibility Testing Observations
- Keyboard navigation using Tab was checked.
- Enter key navigation was checked.
- Visible keyboard focus was observed.
- Image alternative text was inspected.
- Text and background contrast was visually checked.
- Contact form keyboard accessibility was checked.

*Note: Formal WCAG compliance testing was not performed.*

## 9. Performance Testing Observations
- Homepage loaded without noticeable delay during manual observation.
- Browser console showed no visible errors during the checks.
- Inspected network requests showed successful responses, including status 200.
- No visible failed requests were observed during inspection.

*Note: Formal load and stress testing were not performed.*

## 10. Security Observations
- HTTPS connection was verified.
- Contact form was accessed over HTTPS.
- No penetration testing or vulnerability scanning was performed.

## 11. Recommendations
1. Verify and correct the newsletter Return to Site navigation destination if necessary.
2. Review phone number validation on the contact form.
3. Perform automated accessibility testing.
4. Conduct formal performance testing.
5. Perform authorized security testing.
6. Test the website across additional browsers and devices.

## 12. Conclusion
The Cynbit website was evaluated through manual functional, usability, navigation, accessibility observation, and responsive testing.

Most observed website functions worked as expected. One navigation issue was identified in both desktop and mobile testing. Phone number validation remains pending.

The audit documents the observed results and provides recommendations for improving website quality and user experience.
