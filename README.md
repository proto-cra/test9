# test9 COP

*description of the COP*

**COP timeframe** 2025-12-30 - 2026-04-07

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://proto-cra.github.io/test9](https://proto-cra.github.io/test9)

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

**Updated:**  2026-01-13

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Tax credits and benefits for individuals)
    node4(Overview of child and family benefits)
    node5(Provincial and territorial programs)
    node6(Business registration with the CRA)
    node7(Maintain your business)
    node8(Bankruptcy/receivership)
    node9(Bankruptcy – Business structures)
    node10(Bankruptcy)
    node11(Proposal in bankruptcy)
    node12(Receivership)
    node13(Insolvency Intake Centres)
    node14(Change of owners, partners, or directors)
    node15(Income tax)
    node16(Businesses – International and non-resident taxes)
    node17(Rendering services in Canada)
    node18(Non-resident employer certification)
    node19(Where to send international waiver and non-resident employer certification applications)
    node20(New page)
    node21(Benefits)
    node22(Benefits payment dates)
    node23(Canada Revenue Agency #40;CRA#41;)
    node24(Forms and publications - CRA)
    node25(Canada Revenue Agency forms listed by number)
    node26(RC342 Request by an Insolvency Practitioner for a Waiver of the Requirement to file a T2 Corporation Income Tax Return under Subsection 220#40;2.1#41; of the Income Tax Act)
    node27(RC473 Application for Non-Resident Employer Certification)
    node28(Canada Revenue Agency publications listed by number)
    node29(B-088 Export Distribution Centre Program)
    node30(Export Distribution Centre Program)
    node31(Sign in to your CRA account)
    node32(CRA Sign in)
    node33(Help with using your CRA account)
    node34(CRA account help - About Sign-In Partners)
    node35(CRA account help - Verify your identity)
    node36(Register for a CRA account)
    node37(Support from the CRA during difficult situations)
    node38(COVID-19 benefits from the CRA)
    node39(Validating your application – COVID-19 benefits from the CRA)
    node40(Untitled)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node2 --> node6
    node6 --> node7
    node7 --> node8
    node8 --x node9
    node8 --> node10
    node8 --> node11
    node8 --> node12
    node8 --x node13
    node7 --> node14
    node2 --> node15
    node15 --x node16
    node16 --> node17
    node17 --> node18
    node17 --> node19
    node2 --x node20
    node1 --> node21
    node21 --> node22
    node1 --x node23
    node23 --> node24
    node24 --> node25
    node25 --> node26
    node25 --> node27
    node24 --> node28
    node28 --> node29
    node29 --x node30
    node23 --> node31
    node31 --x node32
    node31 --> node33
    node33 --> node34
    node33 --> node35
    node31 --> node36
    node23 --> node37
    node37 --> node38
    node38 --> node39
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/services/taxes.html" _blank
    click node3 "https://www.canada.ca/en/services/taxes/child-and-family-benefits.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/provincial-territorial-programs.html" _blank
    click node6 "https://www.canada.ca/en/services/taxes/business-registration.html" _blank
    click node7 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/business-registration/maintain-business.html" _blank
    click node8 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/business-registration/maintain-business/receivership-bankruptcy.html" _blank
    click node9 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/business-registration/maintain-business/receivership-bankruptcy/bankruptcy-business-structures.html" _blank
    click node10 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/business-registration/maintain-business/receivership-bankruptcy/bankruptcy.html" _blank
    click node11 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/business-registration/maintain-business/receivership-bankruptcy/proposal-bankruptcy.html" _blank
    click node12 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/business-registration/maintain-business/receivership-bankruptcy/receivership.html" _blank
    click node13 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/business-registration/maintain-business/receivership-bankruptcy/regional-intake-centres-insolvency-rici.html" _blank
    click node14 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/business-registration/maintain-business/change-owner-partners-directors.html" _blank
    click node15 "https://www.canada.ca/en/services/taxes/income-tax.html" _blank
    click node16 "https://www.canada.ca/en/revenue-agency/services/tax/international-non-residents/businesses-international-non-resident-taxes.html" _blank
    click node17 "https://www.canada.ca/en/revenue-agency/services/tax/international-non-residents/information-been-moved/rendering-services-canada.html" _blank
    click node18 "https://www.canada.ca/en/revenue-agency/services/tax/international-non-residents/information-been-moved/rendering-services-canada/non-resident-employer-certification.html" _blank
    click node19 "https://www.canada.ca/en/revenue-agency/services/tax/international-non-residents/information-been-moved/rendering-services-canada/where-send-completed-waiver-non-resident-employer-certification-applications.html" _blank
    click node20 "https://www.canada.ca/en/revenue-agency/services/bererenefits/worker-lockdown-benefit/cwlb-who-apply.html" _blank
    click node21 "https://www.canada.ca/en/services/benefits.html" _blank
    click node22 "https://www.canada.ca/en/services/benefits/calendar.html" _blank
    click node23 "https://www.canada.ca/en/revenue-agency.html" _blank
    click node24 "https://www.canada.ca/en/revenue-agency/services/forms-publications.html" _blank
    click node25 "https://www.canada.ca/en/revenue-agency/services/forms-publications/forms.html" _blank
    click node26 "https://www.canada.ca/en/revenue-agency/services/forms-publications/forms/rc342.html" _blank
    click node27 "https://www.canada.ca/en/revenue-agency/services/forms-publications/forms/rc473.html" _blank
    click node28 "https://www.canada.ca/en/revenue-agency/services/forms-publications/publications.html" _blank
    click node29 "https://www.canada.ca/en/revenue-agency/services/forms-publications/publications/b-088.html" _blank
    click node30 "https://www.canada.ca/en/revenue-agency/services/forms-publications/publications/b-088/export-distribution-centre-program.html" _blank
    click node31 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services.html" _blank
    click node32 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/cra-login.html" _blank
    click node33 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/help-cra-sign-in-services.html" _blank
    click node34 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/help-cra-sign-in-services/sign-in-partners.html" _blank
    click node35 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/help-cra-sign-in-services/verify-identity.html" _blank
    click node36 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/register-cra-sign-in-services.html" _blank
    click node37 "https://www.canada.ca/en/revenue-agency/services/support-difficult-situations.html" _blank
    click node38 "https://www.canada.ca/en/revenue-agency/services/benefits.html" _blank
    click node39 "https://www.canada.ca/en/revenue-agency/services/benefits/covid-validation.html" _blank
    click node40 "https://www.canada.ca/en/revenue-agency/services/benefits/worker-lockdown-benefit/cwlb-who-apply.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node5,node9,node10,node11,node12,node13,node14,node18,node19,node20,node22,node26,node27,node29,node30,node32,node33,node34,node35,node36,node39,node40 inscope
    classDef isnew fill:#00706f,color:#fff
    class node20 isnew
```
