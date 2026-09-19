# Accessibility Baseline Audit

## Website Audited
National Portal of India — india.gov.in

## Lighthouse / PageSpeed Results

### Desktop
- Performance: 64
- Accessibility: 89
- Best Practices: 92
- SEO: 100

### Key Accessibility Findings

1. **ARIA role hierarchy issue**
   - Lighthouse reports that some ARIA roles are not contained by their required parent element.
   - Priority: High

2. **Insufficient color contrast**
   - Lighthouse reports that some background and foreground colors do not have sufficient contrast.
   - Priority: High

3. **Invalid list structure**
   - Some `<li>` elements are not contained within `<ul>`, `<ol>`, or `<menu>` elements.
   - Priority: Medium

## Manual Testing
Keyboard-only navigation should be performed separately because automated Lighthouse testing cannot cover all accessibility issues.

## Recommended Remediation
- Correct ARIA role and parent-element relationships.
- Improve color contrast to meet accessibility requirements.
- Correct list markup and semantic HTML structure.
- Perform a manual keyboard navigation review.
