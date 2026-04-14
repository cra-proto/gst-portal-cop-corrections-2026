# GST portal COP corrections 2026

*description of the project*

**Timeframe** 2026-03-31 - 2026-07-07

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/gst-portal-cop-corrections-2026](https://cra-test-arc.canada.ca/gst-portal-cop-corrections-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-04-14

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Digital services)
    node4(Digital services for businesses)
    node5(Adjusting a GST/HST #40;and QST#41; return  – CRA account help – Businesses)
    node6(Completing a GST/HST or QST return – CRA account help - Businesses)
    node7(GST/HST for businesses)
    node8(File your GST/HST return)
    node9(How to file – File your GST/HST return)
    node10(Get a GST/HST access code – File your GST/HST return)
    node1 --> node2
    node2 --x node3
    node3 --> node4
    node4 --x node5
    node4 --x node6
    node2 --> node7
    node7 --> node8
    node8 --> node9
    node9 --> node10
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/services/taxes.html" _blank
    click node3 "https://www.canada.ca/en/revenue-agency/services/e-services.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-businesses.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-businesses/business-account/adjust-a-return.html" _blank
    click node6 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-businesses/business-account/gst-hst-electronic-filing.html" _blank
    click node7 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/gst-hst-businesses.html" _blank
    click node8 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/gst-hst-businesses/file-gst-hst-return.html" _blank
    click node9 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/gst-hst-businesses/file-gst-hst-return/how-file.html" _blank
    click node10 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/gst-hst-businesses/file-gst-hst-return/how-file/get-gst-hst-access-code.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node5,node6,node10 inscope
```
