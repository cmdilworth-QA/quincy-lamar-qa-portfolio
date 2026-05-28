QA Audit

**Project Type:** Website Content & UX Audit  
**Website:** https://www.quincylamar.com/  
**Audit Date:** May 2026  
**Tester:** Cassondra Dilworth  

---

## 📋 Project Overview

This audit represents a **comprehensive QA evaluation** of the Quincy Lamar artist website, identifying 12 critical issues across content completeness, UX/navigation, link functionality, and brand alignment. The project demonstrates systematic testing methodology, professional bug reporting, and strategic recommendations for website improvement.

**Key Skills Demonstrated:**
- Content audit and completeness testing
- UX/navigation testing and gap analysis
- Link verification and QA testing
- Bug categorization and severity assessment
- Test case documentation (formal QA format)
- Strategic recommendations and prioritization
- Cross-device/responsive testing
- Professional communication of findings

---

## Executive Summary

| Metric | Result |
|--------|--------|
| **Total Test Cases** | 12 |
| **Tests Failed** | 12 (100%) |
| **Critical Issues** | 2 |
| **High Priority Issues** | 8 |
| **Medium Priority Issues** | 2 |
| **Overall Status** | NOT PRODUCTION READY |

**Key Findings:**
- Website contains mostly template content
- Critical branding issues undermine professional credibility
- Multiple pages incomplete or non-functional
- Social media links broken (Instagram)
- Navigation and footer missing
- Typography accessibility issues across all pages

---

## Repository Contents

### Test Cases & Documentation
- **[Full Test Cases](./test-cases/)** - Detailed test cases in formal QA format
  - Each test includes: Steps to Reproduce, Expected Result, Actual Result, Impact
  - Organized by page/section for easy navigation
  
- **[Bug Reports](./bug-reports/)** - Individual critical and high-priority bugs with evidence
  
- **[Test Summary](./test-summary/)** - Executive summary and coverage matrices

### Evidence
- **[Screenshots](./evidence/screenshots/)** - Visual proof of each issue
- **[Demo Videos](./evidence/videos/)** - Screen recordings of broken functionality

### Detailed Documentation
- **[Testing Methodology](./docs/testing-methodology.md)** - How the audit was conducted
- **[Recommendations](./docs/recommendations.md)** - Prioritized action items

---

## Test Cases

### Critical Issue - Brand Not Represented
**Test ID:** TC-012  
**Severity:** CRITICAL  
**Status:** ❌ FAIL

**What was tested:** Whether website accurately represents Quincy Lamar as a professional artist.

**What I found:** Website contains mostly template content, incomplete pages, and doesn't communicate Quincy's credentials, accomplishments, or offerings.

**Why it matters:** This undermines professional credibility and prevents potential clients/collaborators from understanding Quincy's value.

**Recommendation:** Implement holding page → complete content overhaul → re-test → launch.

---

### High Priority - Instagram Link Broken
**Test ID:** TC-011  
**Severity:** HIGH  
**Status:** ❌ FAIL

**What was tested:** Instagram social media button functionality.

**Steps to reproduce:**
1. Locate Instagram button on website
2. Click the button
3. Verify destination URL and account

**Expected:** Button should link to Quincy's Instagram profile  
**Actual:** Button links to generic Wix Instagram page (not Quincy's account)

**Impact:** Lost social media traffic and follower growth opportunity.

---

###High Priority - Missing Footer Navigation
**Test ID:** TC-007  
**Severity:** HIGH  
**Status:** ❌ FAIL

**What was tested:** Footer navigation links for improved UX.

**Expected:** Footer should contain links to Home, About, Credits, Masterclasses, Workshops, Choreography, Contact

**Actual:** Footer contains no navigation links OR footer is missing entirely

**Impact:** Users cannot easily navigate between pages; increased bounce rate.

---

## What This Audit Demonstrates

### QA Technical Skills
- Systematic testing methodology
- Formal test case documentation
- Bug identification and severity assessment
- Cross-device/responsive testing
- Link verification testing
- Content completeness auditing

### QA Soft Skills
- Clear communication of findings
- Professional bug reporting
- Strategic prioritization (prioritized action items)
- Understanding user experience impact
- Actionable recommendations
- Empathy for user journey

### Business Acumen
- Recognizing brand/reputation impact
- Understanding business consequences of bugs
- Suggesting holistic improvements (not just fixes)
- Considering user perspective and engagement

---

## Test Coverage

| Category | Pages Tested | Tests Completed | Pass Rate |
|----------|-------------|-----------------|-----------|
| Content Completeness | 6 | 6 | 0% |
| UX/Navigation | 4 | 3 | 0% |
| Link Verification | All | 2 | 0% |
| Typography/Accessibility | 3 | 2 | 0% |
| **TOTAL** | **All** | **12** | **0% (No Passes)** |

*Note: 0% pass rate is expected for an audit of an incomplete/under-construction site.*

---

## 🚀 How to Use This Repository

### For Hiring Managers / QA Teams
1. Start with this **README** for overview
2. Review **[Full Test Cases](./test-cases/)** for detailed testing methodology
3. Check **[Bug Reports](./bug-reports/)** for professional issue documentation
4. View **[Evidence](./evidence/)** for screenshots/videos proving each issue

### For Learning/Reference
This project can be used as a template for:
- Website content audits
- UX testing checklists
- QA test case documentation
- Professional bug reporting formats

---

## 💡 Key Takeaway

This audit shows I can:
1. **Systematically evaluate** digital products against quality standards
2. **Identify problems** at content, UX, technical, and strategic levels
3. **Document findings** in professional, actionable formats
4. **Prioritize issues** based on business impact
5. **Communicate clearly** with both technical and non-technical stakeholders
6. **Provide recommendations** that go beyond just "bug finding"

---

## Testing Methodology

**Test Type:** Manual Content & UX Audit  
**Duration:** ~8-10 hours  
**Scope:** Full website evaluation across all pages  
**Devices:** Desktop (1440px), Tablet (768px), Mobile (375px)  
**Browser:** Chrome (latest)  
**Date:** May 2026  

See [Testing Methodology](./docs/testing-methodology.md) for detailed approach.

---

## Recommended Action Items (Prioritized)

### Phase 1: Immediate (Launch Holding Page)
- [ ] Deploy "Under Construction" holding page
- [ ] Set timeline for new site launch
- [ ] Collect email signups

### Phase 2: Critical (Content Overhaul)
- [ ] Update About Q bio
- [ ] Complete Credits section
- [ ] Populate/plan Master Classes
- [ ] Populate/plan Workshops
- [ ] Add Choreography portfolio

### Phase 3: Important (UX Improvements)
- [ ] Add footer navigation
- [ ] Increase font sizes
- [ ] Fix Instagram link
- [ ] Expand About Me teaser

### Phase 4: QA & Launch
- [ ] Re-test all pages
- [ ] Link verification
- [ ] Cross-browser testing
- [ ] Mobile responsiveness check
- [ ] Public launch

See [Recommendations](./docs/recommendations.md) for detailed rationale.

---

## 📞 Contact

For questions about this audit or QA testing methodology, reach out to:  
**Cassondra Dilworth**  
QA Engineer (Manual Testing)  
[LinkedIn](https://linkedin.com/in/cassondra) | [GitHub](https://github.com/cassondra)

---

## 📄 License

This audit and documentation are provided as a portfolio example. Feel free to reference the methodology for your own audits.

**License:** MIT

---

## Related Projects

- [Creative Services Boutique QA Portfolio](#)
- [Other Audits & Test Cases](#)

---

**Last Updated:** May 2026  
**Status:** Complete & Ready for Review
