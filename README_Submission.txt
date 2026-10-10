NJ CAR MEET EVENT — MODULE 7 FINAL CAPSTONE PACKAGE

Published website
https://jeanfortuna.github.io/nj-car-meet-event/

GitHub repository
https://github.com/jeanfortuna/nj-car-meet-event

PROJECT OVERVIEW
This production-style HTML/CSS capstone presents a local car-meet event concept. It gives visitors organized information about the event, schedule, gallery, FAQs, and contact options. Event date and venue are intentionally marked as to be confirmed rather than invented.

SITE FILES
- index.html — Home
- about.html — About the event
- schedule.html — Draft schedule and event information
- gallery.html — Vehicle photo gallery
- faq.html — Visitor questions
- contact.html — Contact information/form area
- css/styles.css — Shared design system, components, responsive layouts, focus states, reduced-motion and print rules
- assets/images/ — Optimized responsive WebP image variants
- sitemap.xml and robots.txt — Discoverability files

PROJECT AND EVIDENCE DOCUMENTATION
- Architecture_Notes.txt — CSS architecture, tokens, components, naming and print support
- Layout_Notes.txt — Responsive layout decisions, breakpoints, container query, subgrid fallback and reduced motion
- Responsive_Wireframe_Annotations.txt — Text annotations describing the mobile, tablet and desktop layout plan
- Acceptance_Criteria.txt — Observable project acceptance criteria and documented verification status
- Technical_Defense.txt — Concise explanation of project scope, implementation, tests, decisions and remaining limitations
- Accessibility_Remediation_Changes.txt — Accessibility changes and remediation notes
- Refactoring_Evidence.txt — Before/after explanation of CSS refactoring decisions
- Asset_Inventory.txt — Image and asset inventory
- Optimization_Evidence.txt — Responsive images, typography and media performance evidence
- Testing_Evidence_Previous.txt — Browser checks and related screenshot paths
- Module6_Implementation_Notes.txt — Module 6 implementation notes
- AI_Disclosure.txt — AI-use disclosure
- README_Submission.txt — This package overview
- testing-evidence/ — Screenshots supporting responsive, zoom, keyboard, reduced-motion, gallery and network checks

MODULE 7 RELEASE EVIDENCE
Submit the separate PDF named “NJ_Car_Meet_Module7_Release_Sprint.pdf” with this ZIP. The PDF contains the focused release checklist and an evidence appendix for HTML validation, CSS validation, responsive views, Lighthouse results and the SEO link-text fix.

KNOWN LIMITATIONS — DO NOT REPRESENT THESE AS FIXED
- The W3C CSS Validator reported 2 errors related to container-query properties and 10 warnings. These findings remain open; responsive visual checks did not show a corresponding layout failure in the tested views.
- Two “Uncaught (in promise) Object” console messages were observed in DevTools. The source was not identified and they are not claimed as fixed.
- The documented release checks were performed in Chrome and Chrome Incognito. Firefox and Edge are not claimed as tested in this release pass.
- Lighthouse scores can vary by device, browser context and network. The included report documents the captured run and the earlier run.
- The event date and venue remain to be confirmed.

FINAL REVIEW
Before submission, open the published URL and repository, confirm the expected files are present, and make sure the separate Module 7 Release Sprint PDF is uploaded alongside this ZIP. The uploaded ZIP itself does not publish changes to GitHub Pages; repository updates must be committed and pushed separately.
