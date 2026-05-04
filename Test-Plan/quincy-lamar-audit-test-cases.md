# Quincy Lamar Website Audit - Test Cases & Bug Report
**Website:** https://www.quincylamar.com/  
**Audit Date:** May 2026  
**Tester:** Cassondra Dilworth  
**Test Type:** Content Audit, UX/Navigation Testing, Link Verification

---

## Executive Summary
The Quincy Lamar website contains critical content gaps, broken navigation, missing branding alignment, and non-functional links that undermine the artist's professional presentation. The site requires a holding page and content overhaul before public release.

**Overall Status:** 🔴 CRITICAL - Not Production Ready

---

## Test Case Format
Each test case follows this structure:
- **Test ID:** Unique identifier
- **Module/Section:** What's being tested
- **Test Title:** What you're checking
- **Priority:** Critical / High / Medium / Low
- **Steps to Reproduce:** How you tested it
- **Expected Result:** What should happen
- **Actual Result:** What actually happened
- **Severity:** Impact level
- **Status:** Pass/Fail
- **Evidence:** Screenshots/proof

---

## HOME PAGE TESTS

### TC-001: About Me Section Content Completeness
**Module:** Home Page > About Me Section  
**Priority:** HIGH  
**Severity:** HIGH  
**Status:** 🔴 FAIL

**Steps to Reproduce:**
1. Navigate to https://www.quincylamar.com/
2. Scroll to "About Me" section
3. Read the teaser text above "READ MORE" button
4. Assess if content is compelling enough to drive clicks

**Expected Result:**
- About Me teaser should be detailed and compelling
- Text should showcase Quincy's versatility and major accomplishments
- Font size should be readable and prominent (14px minimum for body text)
- "READ MORE" button should have clear call-to-action copy

**Actual Result:**
- Teaser text is generic and lacks detail
- Font size is too small, difficult to read on all devices
- Text does not highlight signature accomplishments (Stomp the Yard, Monica, etc.)
- Insufficient incentive for users to click "READ MORE" button

**Impact:** Users leave without engaging; first impression fails to capture Quincy's brand authority.

**Recommendation:** Expand About Me teaser with 2-3 key accomplishments and increase font size to 16px minimum.

---

### TC-002: About Me Font Size Accessibility
**Module:** Home Page > About Me Section > Typography  
**Priority:** MEDIUM  
**Severity:** MEDIUM  
**Status:** 🔴 FAIL

**Steps to Reproduce:**
1. View website on desktop (1440px width)
2. View website on tablet (768px width)
3. View website on mobile (375px width)
4. Measure/assess font size readability on each device

**Expected Result:**
- Desktop: 16px minimum for body text
- Tablet: 14px minimum
- Mobile: 14px minimum
- No text should require zooming to read comfortably

**Actual Result:**
- Current font size is below 14px on desktop
- Text becomes unreadable on mobile without zoom
- Poor accessibility compliance

**Impact:** Users with vision challenges or on mobile devices cannot easily read content.

---

## ABOUT Q SECTION TESTS

### TC-003: About Q Bio Content Accuracy & Completeness
**Module:** About Q Page > Biography  
**Priority:** HIGH  
**Severity:** HIGH  
**Status:** 🔴 FAIL

**Steps to Reproduce:**
1. Navigate to About Q page
2. Read the biography section
3. Assess if bio represents Quincy's full range of talents and experience

**Expected Result:**
- Bio should include major career highlights
- Should showcase versatility across multiple disciplines (film, dance, choreography, directing, etc.)
- Should reflect current professional positioning
- Should be 150-250 words (professional length)

**Actual Result:**
- Bio contains original template text
- Does not represent Quincy's actual accomplishments and versatility
- Missing key career details and expertise areas

**Impact:** Professional credibility undermined; visitors get wrong impression of Quincy's scope and experience.

**Recommendation:** Replace with comprehensive, updated bio highlighting film appearances, choreography work, teaching experience, and unique value proposition.

---

## CREDITS SECTION TESTS

### TC-004: Credits Content Completeness
**Module:** Credits Page > Film/Television Credits List  
**Priority:** HIGH  
**Severity:** HIGH  
**Status:** 🔴 FAIL

**Steps to Reproduce:**
1. Navigate to Credits page
2. Review the full credits list
3. Cross-reference against known filmography (Stomp the Yard, Monica, etc.)

**Expected Result:**
- All major film and television appearances should be listed
- Each credit should include year, title, and role
- List should be comprehensive and current
- Credits should be alphabetized or organized by date/type

**Actual Result:**
- Only partial credits listed (missing Stomp the Yard, Monica, and others)
- Incomplete filmography
- Does not showcase full breadth of work

**Impact:** Potential clients, collaborators, and fans cannot see full range of Quincy's experience.

---

### TC-005: Credits - "Keith" Spelling Error
**Module:** Credits Page > Credits List  
**Priority:** MEDIUM  
**Severity:** MEDIUM  
**Status:** 🔴 FAIL

**Steps to Reproduce:**
1. Navigate to Credits page
2. Search for "Keith" in credits list
3. Verify spelling against source material

**Expected Result:**
- Film/project title spelled correctly
- Professional presentation without typos

**Actual Result:**
- "Keith" is misspelled in credits

**Impact:** Unprofessional appearance; credibility loss.

**Recommendation:** Correct spelling and verify all credits for accuracy.

---

### TC-006: Credits Section Font Size
**Module:** Credits Page > Typography  
**Priority:** MEDIUM  
**Severity:** MEDIUM  
**Status:** 🔴 FAIL

**Steps to Reproduce:**
1. View Credits page on desktop
2. Assess font size readability
3. Compare to industry standard (12px minimum for lists)

**Expected Result:**
- Font size: 12px minimum for credits list
- Clear distinction between title and supporting info

**Actual Result:**
- Font size too small
- Difficult to scan and read

**Impact:** Poor user experience; visitors struggle to read credits.

---

## NAVIGATION & FOOTER TESTS

### TC-007: Footer Navigation - Links Not Present
**Module:** Footer Section  
**Priority:** HIGH  
**Severity:** HIGH  
**Status:** 🔴 FAIL

**Steps to Reproduce:**
1. Scroll to bottom/footer of any page
2. Look for navigation links to main sections
3. Attempt to click footer links

**Expected Result:**
- Footer should contain links to main pages: Home, About, Credits, Masterclasses, Workshops, Choreography, Contact
- Footer links should be visible and functional
- Footer should appear on every page
- Footer should allow easy navigation back to main pages

**Actual Result:**
- Footer is either missing or does not contain navigation links
- No quick way to navigate to other sections from footer
- Users must scroll back to top to navigate

**Impact:** Poor UX; users cannot easily navigate between pages. Increased bounce rate.

**Recommendation:** Add footer with links to all main pages. Consider adding social media links.

---

## MASTER CLASSES PAGE TESTS

### TC-008: Master Classes Page - Content Status
**Module:** Master Classes Page  
**Priority:** HIGH  
**Severity:** HIGH  
**Status:** 🔴 FAIL

**Steps to Reproduce:**
1. Navigate to Master Classes page via menu
2. Review page content
3. Assess if content is placeholder or actual offerings

**Expected Result:**
- Master Classes page should display either:
  - Real masterclass offerings with dates, descriptions, pricing, and enrollment links, OR
  - Clear "Coming Soon" message with expected launch date
- If placeholder text remains, should be removed

**Actual Result:**
- Page contains original template information
- No indication of whether content is coming soon
- No clear status communication to visitors
- Confusing for users about Quincy's offerings

**Impact:** Broken user expectations; appears unprofessional and incomplete.

**Recommendation:** Either populate with masterclass details or display "Coming Soon" with expected launch timeline.

---

## WORKSHOPS PAGE TESTS

### TC-009: Workshops Page - Content Missing
**Module:** Workshops Page  
**Priority:** HIGH  
**Severity:** HIGH  
**Status:** 🔴 FAIL

**Steps to Reproduce:**
1. Navigate to Workshops page via menu
2. Assess page content

**Expected Result:**
- Workshops page should display workshop offerings with:
  - Workshop titles and descriptions
  - Dates and times
  - Pricing or enrollment information
  - Location/format (online, in-person)
  OR
  - Clear "Coming Soon" message if not yet available

**Actual Result:**
- Page is completely blank
- No content
- No status indicator

**Impact:** Poor UX; page appears broken or unfinished. Reduces credibility.

**Recommendation:** Add workshop content or "Coming Soon" holding page with expected launch date.

---

## CHOREOGRAPHY PAGE TESTS

### TC-010: Choreography Page - Content Status
**Module:** Choreography Page  
**Priority:** HIGH  
**Severity:** HIGH  
**Status:** 🔴 FAIL

**Steps to Reproduce:**
1. Navigate to Choreography page via menu
2. Review page content
3. Assess if content is meaningful or template

**Expected Result:**
- Choreography page should showcase:
  - Portfolio of choreography work (videos, descriptions, context)
  - Choreography services offered
  - Notable pieces or collaborations
  - OR clear "Coming Soon" message

**Actual Result:**
- Page contains original template information
- No actual choreography portfolio or offerings
- Does not represent Quincy's choreography work or expertise

**Impact:** Visitors cannot learn about Quincy's choreography services or see portfolio. Missed business opportunity.

**Recommendation:** Populate with choreography portfolio pieces, videos, and service descriptions.

---

## LINK VERIFICATION TESTS

### TC-011: Instagram Link Functionality
**Module:** Social Media Links > Instagram Button  
**Priority:** HIGH  
**Severity:** HIGH  
**Status:** 🔴 FAIL

**Steps to Reproduce:**
1. Locate Instagram button/link on website (typically in header, footer, or sidebar)
2. Click on Instagram button
3. Verify destination URL and page

**Expected Result:**
- Instagram button should link to Quincy's Instagram profile
- URL should be: https://www.instagram.com/[quincy-username]/
- Page should display Quincy's Instagram account (verified by bio, profile photo, content)

**Actual Result:**
- Instagram button links to generic Wix Instagram page
- Does not direct to Quincy's personal Instagram account
- Lost traffic and follower opportunity

**Impact:** Users cannot easily find Quincy on social media. Missed engagement and follower growth.

**Recommendation:** Update Instagram link to point to Quincy's actual Instagram profile URL.

---

## OVERALL BRAND ALIGNMENT TEST

### TC-012: Brand Representation & Messaging
**Module:** Entire Website  
**Priority:** CRITICAL  
**Severity:** CRITICAL  
**Status:** 🔴 FAIL

**Steps to Reproduce:**
1. Visit website as first-time visitor
2. Spend 2-3 minutes reviewing content
3. Assess: Does this website accurately represent Quincy Lamar as a professional?

**Expected Result:**
- Website should clearly communicate:
  - Who Quincy is (artist, choreographer, actor, instructor)
  - What Quincy offers (films, choreography, masterclasses, workshops)
  - Why visitors should care (credentials, accomplishments, unique value)
  - How to work with/contact Quincy
- Visual design should match professional brand standards
- Content should be current, complete, and error-free
- Navigation should be intuitive

**Actual Result:**
- Website contains mostly template content
- Does not speak to or represent Quincy's actual brand, expertise, or offerings
- Incomplete across multiple sections
- Multiple typos and non-functional links
- Not ready for public/professional use

**Impact:** CRITICAL - Website actively undermines Quincy's professional brand and credibility.

**Recommendation:** 
**Implement holding page stating "Site Under Construction" → Complete content overhaul → QA verification → Public launch**

---

## SUMMARY TABLE

| Test ID | Section | Issue | Priority | Severity | Status |
|---------|---------|-------|----------|----------|--------|
| TC-001 | Home Page | About Me content too brief, font too small | HIGH | HIGH | FAIL |
| TC-002 | Home Page | Font size accessibility issues | MEDIUM | MEDIUM | FAIL |
| TC-003 | About Q | Bio is template text, not current | HIGH | HIGH | FAIL |
| TC-004 | Credits | Credits incomplete, missing major titles | HIGH | HIGH | FAIL |
| TC-005 | Credits | Spelling error ("Keith") | MEDIUM | MEDIUM | FAIL |
| TC-006 | Credits | Font size too small | MEDIUM | MEDIUM | FAIL |
| TC-007 | Footer | Navigation links missing | HIGH | HIGH | FAIL |
| TC-008 | Master Classes | Template content, no status | HIGH | HIGH | FAIL |
| TC-009 | Workshops | Completely blank page | HIGH | HIGH | FAIL |
| TC-010 | Choreography | Template content, no portfolio | HIGH | HIGH | FAIL |
| TC-011 | Social | Instagram link broken (goes to Wix page) | HIGH | HIGH | FAIL |
| TC-012 | Overall | Brand not represented, site not ready | CRITICAL | CRITICAL | FAIL |

---

## Recommendations Priority Order

### PHASE 1: HOLDING PAGE (Before Re-launch)
- [ ] Add "Under Construction" holding page
- [ ] Display timeline for new site launch
- [ ] Collect email signups for launch notification

### PHASE 2: CRITICAL CONTENT UPDATES
- [ ] Update About Q bio with current accomplishments
- [ ] Complete Credits section with all major titles
- [ ] Fix "Keith" spelling
- [ ] Populate Master Classes page (content OR "Coming Soon")
- [ ] Populate Workshops page (content OR "Coming Soon")
- [ ] Populate Choreography page with portfolio

### PHASE 3: UX/NAVIGATION FIXES
- [ ] Add footer navigation to all pages
- [ ] Increase all font sizes for readability
- [ ] Fix Instagram link to Quincy's actual account
- [ ] Expand About Me teaser on home page

### PHASE 4: QA & LAUNCH
- [ ] Re-test all pages
- [ ] Verify all links functional
- [ ] Cross-browser testing
- [ ] Mobile responsiveness verification
- [ ] Public launch

---

## Testing Methodology

**Test Type:** Content & UX Audit  
**Scope:** Visual inspection, link verification, content completeness assessment  
**Devices Tested:** Desktop (1440px), Tablet (768px), Mobile (375px)  
**Browser:** Chrome (latest)  
**Date:** May 2026  

**Bugs Identified:** 12 total  
- Critical: 2  
- High: 8  
- Medium: 2  

**Overall Assessment:** Website is NOT production-ready and requires significant content and UX work before public launch.
