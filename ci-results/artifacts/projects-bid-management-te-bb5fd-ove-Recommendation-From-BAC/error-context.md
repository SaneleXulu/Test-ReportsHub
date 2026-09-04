# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: projects/bid-management/test-plans/tender-process/bid-supply-chain-management.spec.ts >> BID-SCM — BID: Supply Chain Management >> TC-14: Approve Recommendation From BAC
- Location: projects/bid-management/test-plans/tender-process/bid-supply-chain-management.spec.ts:1666:7

# Error details

```
Error: expect(locator).toBeVisible() failed

Locator: getByRole('row').filter({ hasText: 'REF2026-0928' }).filter({ hasText: 'Approve Recommendation from BAC' }).first()
Expected: visible
Timeout: 30000ms
Error: element(s) not found

Call log:
  - Expect "toBeVisible" with timeout 30000ms
  - waiting for getByRole('row').filter({ hasText: 'REF2026-0928' }).filter({ hasText: 'Approve Recommendation from BAC' }).first()

```

```yaml
- complementary:
  - menu:
    - menuitem "container Bid Management":
      - img "container"
      - text: Bid Management
    - menuitem "menu-unfold SupplyChain Management":
      - img "menu-unfold"
      - text: SupplyChain Management
    - menuitem "file-text Contract Management":
      - img "file-text"
      - text: Contract Management
    - menuitem "apartment Workflows":
      - img "apartment"
      - text: Workflows
    - menuitem "account-book Requisition":
      - img "account-book"
      - text: Requisition
    - menuitem "setting Configurations":
      - img "setting"
      - text: Configurations
    - menuitem "tool Administration":
      - img "tool"
      - text: Administration
  - img "menu-unfold"
- banner:
  - button "edit":
    - img "edit"
  - paragraph: Shesha/header v9
  - text: Live
  - img "close"
  - link:
    - /url: /
    - img
  - text: Live Mode
  - switch "Switch to Edit mode"
  - img "block"
  - text: Latest Thulile Matekenya
  - img "down"
  - img "user"
- main:
  - button "edit":
    - img "edit"
  - paragraph: Shesha.Workflow/workflows-inbox v7
  - text: Live
  - img "close"
  - heading "Incoming Items" [level=4]
  - textbox
  - button "search":
    - img "search"
  - button "filter":
    - img "filter"
  - button "sliders":
    - img "sliders"
  - list:
    - listitem: 1-10 of 22 items
    - listitem "Previous Page":
      - button "left" [disabled]:
        - img "left"
    - listitem "1"
    - listitem "2"
    - listitem "3"
    - listitem "Next Page":
      - button "right":
        - img "right"
    - listitem:
      - combobox "Page Size"
      - text: 10 / page
  - button "reload":
    - img "reload"
  - button "download Export":
    - img "download"
    - text: Export
  - table:
    - row "Ref No Initiator Type Name Action Required Received Date Target Date Status Period In Possession":
      - columnheader
      - columnheader "Ref No":
        - text: Ref No
        - separator
      - columnheader "Initiator":
        - text: Initiator
        - separator
      - columnheader "Type":
        - text: Type
        - separator
      - columnheader "Name":
        - text: Name
        - separator
      - columnheader "Action Required":
        - text: Action Required
        - separator
      - columnheader "Received Date":
        - text: Received Date
        - separator
      - columnheader "Target Date":
        - text: Target Date
        - separator
      - columnheader "Status":
        - text: Status
        - separator
      - columnheader "Period In Possession":
        - text: Period In Possession
        - separator
    - rowgroup:
      - 'row "search REF2026-1204 Maand-awe Mamathuntsha Tender Process Tender REF2026-1204 - PD-BID: Close Button is Disabled in Supplier Compliance Dialog (Verify Compliance) Approve Recommendation from BAC 06/08/2026 Adjudicate In Progress 29 day(s) ago"':
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=f94e1b39-b337-48d6-b863-f60ca01462e3&todoid=4a8e3619-c8a7-42f4-b165-15ca00009269
            - img "search"
        - cell "REF2026-1204"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - 'cell "Tender REF2026-1204 - PD-BID: Close Button is Disabled in Supplier Compliance Dialog (Verify Compliance)"'
        - cell "Approve Recommendation from BAC"
        - cell "06/08/2026"
        - cell
        - cell "Adjudicate In Progress"
        - cell "29 day(s) ago"
      - row "search REF2026-0879 Maand-awe Mamathuntsha Tender Process Tender REF2026-0879 - TC-01 Automated Draft Tender run-msd7x3nh - 90/10 Compulsory Hybrid Approve Recommendation from BAC 06/08/2026 Adjudicate In Progress 29 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=ea0d73d4-3124-47f0-9e27-b96a78de3524&todoid=7ad78430-cecf-4b28-87d5-4482c2f06259
            - img "search"
        - cell "REF2026-0879"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-0879 - TC-01 Automated Draft Tender run-msd7x3nh - 90/10 Compulsory Hybrid"
        - cell "Approve Recommendation from BAC"
        - cell "06/08/2026"
        - cell
        - cell "Adjudicate In Progress"
        - cell "29 day(s) ago"
      - row "search REF2026-1008 Maand-awe Mamathuntsha Tender Process Tender REF2026-1008 - send back for re-evaluation Approve Recommendation from BAC 06/08/2026 Adjudicate In Progress 29 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=a21073a3-bd7a-4e70-8118-16f34ec66741&todoid=f6a890ce-c165-4c82-abed-71a8b3233f2a
            - img "search"
        - cell "REF2026-1008"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1008 - send back for re-evaluation"
        - cell "Approve Recommendation from BAC"
        - cell "06/08/2026"
        - cell
        - cell "Adjudicate In Progress"
        - cell "29 day(s) ago"
      - row "search REF2026-1053 Maand-awe Mamathuntsha Tender Process Tender REF2026-1053 - TC-01 Automated Draft Tender run-ms7gw5l1 - 80/20 Compulsory Hybrid Approve Recommendation from BAC 30/07/2026 Adjudicate In Progress 2 month(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=41e61092-d706-45dc-91cd-cf9cb4d78909&todoid=04c018ac-6387-40af-9093-b37316c22ec9
            - img "search"
        - cell "REF2026-1053"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1053 - TC-01 Automated Draft Tender run-ms7gw5l1 - 80/20 Compulsory Hybrid"
        - cell "Approve Recommendation from BAC"
        - cell "30/07/2026"
        - cell
        - cell "Adjudicate In Progress"
        - cell "2 month(s) ago"
      - row "search REF2026-5358 Maand-awe Mamathuntsha Tender Process Tender REF2026-5358 - Last test before Workflow changes Approve Recommendation from BAC 15/06/2026 Adjudicate In Progress 3 month(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=420aa439-44fc-4e47-9e1c-ef4eef6351c9&todoid=fce76160-4474-4f71-ab38-1631e3ad8c29
            - img "search"
        - cell "REF2026-5358"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-5358 - Last test before Workflow changes"
        - cell "Approve Recommendation from BAC"
        - cell "15/06/2026"
        - cell
        - cell "Adjudicate In Progress"
        - cell "3 month(s) ago"
      - row "search REF2025-2003 Thulile Matekenya Request For Quotation QA Requisition & Select Suppliers 20/02/2025 In Progress 1 year(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=f782030b-7c0f-423e-86e8-565f1477652d&todoid=7c6af1f5-15c1-424c-af83-f5fdfd37425d
            - img "search"
        - cell "REF2025-2003"
        - cell "Thulile Matekenya"
        - cell "Request For Quotation"
        - cell
        - cell "QA Requisition & Select Suppliers"
        - cell "20/02/2025"
        - cell
        - cell "In Progress"
        - cell "1 year(s) ago"
      - row "search REF2025-2003 Thulile Matekenya Request For Quotation Review RFQ 20/02/2025 In Progress 1 year(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=f782030b-7c0f-423e-86e8-565f1477652d&todoid=18e1e01d-179b-4c82-9585-200f5236214f
            - img "search"
        - cell "REF2025-2003"
        - cell "Thulile Matekenya"
        - cell "Request For Quotation"
        - cell
        - cell "Review RFQ"
        - cell "20/02/2025"
        - cell
        - cell "In Progress"
        - cell "1 year(s) ago"
      - row "search REF2024-0805 Thulile Matekenya Tender Process Tender REF2024-0805 - Test Office Approve Recommendation from BAC 05/12/2024 In Progress 2 year(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=6cc32c6b-e9dd-405d-8c74-5ce646e55b33&todoid=57745632-9e69-4ea3-a4dc-31f24953908e
            - img "search"
        - cell "REF2024-0805"
        - cell "Thulile Matekenya"
        - cell "Tender Process"
        - cell "Tender REF2024-0805 - Test Office"
        - cell "Approve Recommendation from BAC"
        - cell "05/12/2024"
        - cell
        - cell "In Progress"
        - cell "2 year(s) ago"
      - row "search REF2024-0671 Thulile Matekenya Tender Process Tender REF2024-0671 - Test Approve Recommendation from BAC 02/12/2024 In Progress 2 year(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=43cf5ad4-b48a-4fb3-9cdc-bdce4fff1b93&todoid=6563a619-fca1-4006-afbe-d139515f3c95
            - img "search"
        - cell "REF2024-0671"
        - cell "Thulile Matekenya"
        - cell "Tender Process"
        - cell "Tender REF2024-0671 - Test"
        - cell "Approve Recommendation from BAC"
        - cell "02/12/2024"
        - cell
        - cell "In Progress"
        - cell "2 year(s) ago"
      - row "search REF2024-0619 Thulile Matekenya Tender Process Tender REF2024-0619 - Testing fields Monitor calibration and finalise scoring 20/11/2024 In Progress 2 year(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=a89d0fd1-3466-4f8c-aa39-0b15fd1de846&todoid=fb70974c-b857-46ac-bf4e-68b6733fa09d
            - img "search"
        - cell "REF2024-0619"
        - cell "Thulile Matekenya"
        - cell "Tender Process"
        - cell "Tender REF2024-0619 - Testing fields"
        - cell "Monitor calibration and finalise scoring"
        - cell "20/11/2024"
        - cell
        - cell "In Progress"
        - cell "2 year(s) ago"
- alert
```

# Test source

```ts
  1578 | 
  1579 |     // ASSERT (BLOCKING) the item opens on the "BEC: Finalise recommendation" page
  1580 |     await expectOnPage(page, 'BEC: Finalise recommendation:');
  1581 | 
  1582 |     // NEGATIVE (opt-in SEND_BACKS): send this stage back to "Monitor calibration and finalise scoring", have that actor re-action
  1583 |     // it, then return here and carry on with the happy path — the chain still completes.
  1584 |     await sendBackAndReturn(page, { stageNo: 12, stage: 'BEC: Finalise recommendation', previous: 'Monitor calibration and finalise scoring', actor: BEC_CHAIR });
  1585 | 
  1586 |     // STEP: wait for the score/evaluation tables to load, then verify A & A Stationers ranks #1 and is the
  1587 |     // pre-selected Recommended Supplier.
  1588 |     await expect(page.getByText('loading...').first()).toBeHidden({ timeout: 30000 });
  1589 |     const finalEval = page.getByRole('row').filter({ hasText: 'A & A Stationers' }).first();
  1590 |     await expect(finalEval).toBeVisible({ timeout: 15000 });
  1591 | 
  1592 |     // STEP: select the Approve Recommendation decision, then fill the required BEC Report.
  1593 |     await page.getByRole('button', { name: /Approve Recommendation/ }).click();
  1594 |     await page.getByRole('textbox').last().fill(
  1595 |       'BEC recommends the award to A & A Stationers, the top-ranked supplier. ' +
  1596 |       'All responses were above the functionality minimum and compliant. Automated TC-12 happy-path recommendation.');
  1597 | 
  1598 |     // STEP: Submit Recommendation (only enabled once a decision is picked + BEC Report filled) → advances the
  1599 |     // tender out of the stage. Retry the click against the slow app until we leave the workflow-action page.
  1600 |     const submit = page.getByRole('button', { name: 'Submit Recommendation', exact: true });
  1601 |     await expect(submit).toBeEnabled({ timeout: 15000 });
  1602 |     await clickOnceAndAwait(submit, async () => /workflows-(my-items|inbox)/.test(page.url()), 'Finalise recommendation');
  1603 |   });
  1604 | 
  1605 |   // ADO Test Case #60836: https://dev.azure.com/boxfusion/PD-SupplyChainManagement/_workitems/edit/60836
  1606 |   // Happy path VERIFIED LIVE 2026-06-04 against REF2026-1399 (advanced here by TC-12). Logged in as the BAC
  1607 |   // adjudicator (MoshadiM) — switch users via clearLocalStorage + /login (no working logout). ADO Maanda-awe
  1608 |   // login + Export-to-Excel steps are stale. Open the Inbox item (form
  1609 |   // tender-wf-captureoutcomeofthebac-finalrecommendation), review the Stage 1/2/3 adjudication summaries +
  1610 |   // read-only BEC Recommendation (A & A Stationers, Overall 98, Rank 1), select the BAC "Approve Recommendation"
  1611 |   // decision, then Submit → the tender advances to "Approve Recommendation From BAC" (TC-14) and leaves the inbox.
  1612 |   // NOTE: Stage 3 shows the recommended supplier (A & A Stationers) with Recommendation Status "Not Recommended"
  1613 |   // — a suspected inverted-flag defect, flagged for observation on a full rerun (not asserted here).
  1614 |   // Self-supplying: TC-12 replenishes this stage.
  1615 |   test('TC-13: Capture Outcome of the BAC', async ({ page }) => {
  1616 |     test.setTimeout(120_000);
  1617 |     await loginAs(page, BAC);
  1618 |     await openInbox(page);
  1619 |     await expect(page.getByRole('button', { name: /export/i })).toBeVisible({ timeout: 15000 });
  1620 | 
  1621 |     // STEP: open the target tender (our TC-01 item) at the Capture-outcome stage via its magnifying-glass.
  1622 |     await page.getByRole('heading', { name: 'Incoming Items' }).click();
  1623 |     const targetRow = page.getByRole('row')
  1624 |       .filter({ hasText: tenderMatch() })
  1625 |       .filter({ hasText: 'Capture outcome from the BAC' })
  1626 |       .first();
  1627 |     await expect(targetRow).toBeVisible({ timeout: 30000 });
  1628 |     // Open the row by navigating to its href, not a positional click: the Workflows accordion
  1629 |     // flyout ("My Items" nav-link) can overlap the table and intercept the click. goto avoids that.
  1630 |     const rowHref = await targetRow.getByRole('link').first().getAttribute('href');
  1631 |     await page.goto(rowHref.startsWith('http') ? rowHref : `${APP_URL.replace('/login', '')}${rowHref}`);
  1632 |     await page.waitForURL(/workflow-action/, { timeout: 30000 });
  1633 | 
  1634 |     // ASSERT (BLOCKING) the item opens on the "Capture outcome from the BAC" page
  1635 |     await expectOnPage(page, 'Capture outcome from the BAC:');
  1636 | 
  1637 |     // NEGATIVE (opt-in SEND_BACKS): send this stage back to "BEC: Finalise recommendation", have that actor re-action
  1638 |     // it, then return here and carry on with the happy path — the chain still completes.
  1639 |     await sendBackAndReturn(page, { stageNo: 13, stage: 'Capture outcome from the BAC', previous: 'BEC: Finalise recommendation', actor: BAC });
  1640 | 
  1641 |     // STEP: wait for the adjudication summaries to load, then verify Stage 3 ranks A & A Stationers #1 (Overall 98)
  1642 |     // and the BEC Recommended Supplier is A & A Stationers.
  1643 |     await expect(page.getByText('loading...').first()).toBeHidden({ timeout: 30000 });
  1644 |     const stage3Winner = page.getByRole('row').filter({ hasText: 'A & A Stationers' }).first();
  1645 |     await expect(stage3Winner.first()).toBeVisible({ timeout: 15000 });
  1646 | 
  1647 |     // STEP: select the BAC Approve Recommendation decision (enables Submit).
  1648 |     await page.getByRole('button', { name: /Approve Recommendation/ }).click();
  1649 | 
  1650 |     // STEP: Submit → captures the BAC outcome and advances the tender out of the stage. Retry the click against
  1651 |     // the slow app until we leave the workflow-action page (redirect to My Items / Inbox).
  1652 |     const submit = page.getByRole('button', { name: 'Submit', exact: true });
  1653 |     await expect(submit).toBeEnabled({ timeout: 15000 });
  1654 |     await clickOnceAndAwait(submit, async () => /workflows-(my-items|inbox)/.test(page.url()), 'Capture outcome from the BAC');
  1655 |   });
  1656 | 
  1657 |   // ADO Test Case #60843: https://dev.azure.com/boxfusion/PD-SupplyChainManagement/_workitems/edit/60843
  1658 |   // Happy path VERIFIED LIVE 2026-06-04 against REF2026-1399 (advanced here by TC-13). Logged in as the approving
  1659 |   // authority (ThulileM) — switch users via clearLocalStorage + /login. ADO Maanda-awe login + Export-to-Excel
  1660 |   // steps are stale. Open the Inbox item (form tender-wf-approverecommendationfrombac-details), review the Stage
  1661 |   // 1/2/3 summaries, tick the "Approve BAC Recommendation" confirmation checkbox, then Submit → the tender
  1662 |   // advances to "Compile and Upload Appointment Letter" (TC-15) and leaves the inbox.
  1663 |   // NOTE: Stage 3 still shows the recommended supplier (A & A Stationers) as "Not Recommended" — the same
  1664 |   // suspected inverted-flag defect seen in TC-13, flagged for observation on a full rerun (not asserted here).
  1665 |   // Self-supplying: TC-13 replenishes this stage.
  1666 |   test('TC-14: Approve Recommendation From BAC', async ({ page }) => {
  1667 |     test.setTimeout(120_000);
  1668 |     await loginAs(page, APPROVER);
  1669 |     await openInbox(page);
  1670 |     await expect(page.getByRole('button', { name: /export/i })).toBeVisible({ timeout: 15000 });
  1671 | 
  1672 |     // STEP: open the target tender (our TC-01 item) at the Approve-Recommendation-from-BAC stage via its glass.
  1673 |     await page.getByRole('heading', { name: 'Incoming Items' }).click();
  1674 |     const targetRow = page.getByRole('row')
  1675 |       .filter({ hasText: tenderMatch() })
  1676 |       .filter({ hasText: 'Approve Recommendation from BAC' })
  1677 |       .first();
> 1678 |     await expect(targetRow).toBeVisible({ timeout: 30000 });
       |                             ^ Error: expect(locator).toBeVisible() failed
  1679 |     // Open the row by navigating to its href, not a positional click: the Workflows accordion
  1680 |     // flyout ("My Items" nav-link) can overlap the table and intercept the click. goto avoids that.
  1681 |     const rowHref = await targetRow.getByRole('link').first().getAttribute('href');
  1682 |     await page.goto(rowHref.startsWith('http') ? rowHref : `${APP_URL.replace('/login', '')}${rowHref}`);
  1683 |     await page.waitForURL(/workflow-action/, { timeout: 30000 });
  1684 | 
  1685 |     // ASSERT (BLOCKING) the item opens on the "Approve Recommendation from BAC" page
  1686 |     await expectOnPage(page, 'Approve Recommendation from BAC:');
  1687 | 
  1688 |     // NEGATIVE (opt-in SEND_BACKS): send this stage back to "Capture outcome from the BAC", have that actor re-action
  1689 |     // it, then return here and carry on with the happy path — the chain still completes.
  1690 |     await sendBackAndReturn(page, { stageNo: 14, stage: 'Approve Recommendation from BAC', previous: 'Capture outcome from the BAC', actor: APPROVER });
  1691 | 
  1692 |     // STEP: wait for the adjudication summaries to load, then verify Stage 3 ranks A & A Stationers #1 (Overall 98).
  1693 |     await expect(page.getByText('loading...').first()).toBeHidden({ timeout: 30000 });
  1694 |     const stage3Winner = page.getByRole('row').filter({ hasText: 'A & A Stationers' }).first();
  1695 |     await expect(stage3Winner.first()).toBeVisible({ timeout: 15000 });
  1696 | 
  1697 |     // STEP: tick the "Approve BAC Recommendation" confirmation checkbox (enables Submit). The confirm checkbox is
  1698 |     // the one inside the block whose text mentions approving the Bid Adjudication Committee recommendation.
  1699 |     await page.locator('div')
  1700 |       .filter({ hasText: /approve the recomm.*endation from the Bid Adjudication/i })
  1701 |       .filter({ has: page.getByRole('checkbox') })
  1702 |       .last()
  1703 |       .getByRole('checkbox')
  1704 |       .check();
  1705 | 
  1706 |     // STEP: Submit → approves and advances the tender out of the stage. Retry the click against the slow app until
  1707 |     // we leave the workflow-action page (redirect to My Items / Inbox).
  1708 |     const submit = page.getByRole('button', { name: 'Submit', exact: true });
  1709 |     await expect(submit).toBeEnabled({ timeout: 15000 });
  1710 |     await clickOnceAndAwait(submit, async () => /workflows-(my-items|inbox)/.test(page.url()), 'Approve Recommendation from BAC');
  1711 |   });
  1712 | 
  1713 |   // ADO Test Case #60845: https://dev.azure.com/boxfusion/PD-SupplyChainManagement/_workitems/edit/60845
  1714 |   // Happy path VERIFIED LIVE 2026-06-04 against REF2026-1399 (advanced here by TC-14). Logged in as TumisangM
  1715 |   // (the PUBLISHER also handles the appointment-letter upload) — switch users via clearLocalStorage + /login.
  1716 |   // ADO Maanda-awe login + Export-to-Excel steps are stale. Open the Inbox item (form
  1717 |   // tender-wf-compileanduploadappointmentletter-details), upload the signed appointment letter for the successful
  1718 |   // bidder, pick the Contract Management Unit email, tick the Confirm checkbox, then Submit → the tender status
  1719 |   // becomes "Awarded" and it advances to "Capture Order Details" (TC-16). Self-supplying: TC-14 replenishes this.
  1720 |   test('TC-15: Compile and Upload Appointment Letter', async ({ page }) => {
  1721 |     test.setTimeout(150_000);
  1722 |     await loginAs(page, PUBLISHER);
  1723 |     await openInbox(page);
  1724 |     await expect(page.getByRole('button', { name: /export/i })).toBeVisible({ timeout: 15000 });
  1725 | 
  1726 |     // STEP: open the target tender (our TC-01 item) at the Upload-Appointment-letter stage via its glass.
  1727 |     await page.getByRole('heading', { name: 'Incoming Items' }).click();
  1728 |     const targetRow = page.getByRole('row')
  1729 |       .filter({ hasText: tenderMatch() })
  1730 |       .filter({ hasText: 'Upload Appointment letter' })
  1731 |       .first();
  1732 |     await expect(targetRow).toBeVisible({ timeout: 30000 });
  1733 |     // Open the row by navigating to its href, not a positional click: the Workflows accordion
  1734 |     // flyout ("My Items" nav-link) can overlap the table and intercept the click. goto avoids that.
  1735 |     const rowHref = await targetRow.getByRole('link').first().getAttribute('href');
  1736 |     await page.goto(rowHref.startsWith('http') ? rowHref : `${APP_URL.replace('/login', '')}${rowHref}`);
  1737 |     await page.waitForURL(/workflow-action/, { timeout: 30000 });
  1738 | 
  1739 |     // ASSERT (BLOCKING) the item opens on the "Upload Appointment letter" page
  1740 |     await expectOnPage(page, 'Upload Appointment letter:');
  1741 | 
  1742 |     // NEGATIVE (opt-in SEND_BACKS): send this stage back to "Approve Recommendation from BAC", have that actor re-action
  1743 |     // it, then return here and carry on with the happy path — the chain still completes.
  1744 |     await sendBackAndReturn(page, { stageNo: 15, stage: 'Upload Appointment letter', previous: 'Approve Recommendation from BAC', actor: PUBLISHER });
  1745 |     await expect(page.getByText('Fetching data...').first()).toBeHidden({ timeout: 30000 });
  1746 | 
  1747 |     // STEP: upload the Appointment Letter (required) and confirm the file surfaces.
  1748 |     await uploadFile(page, page.getByRole('button', { name: /press to upload/i }), PDF_FIXTURE);
  1749 |     await expect(page.getByTitle('pdf-test.pdf').first()).toBeVisible({ timeout: 30000 });
  1750 | 
  1751 |     // STEP: pick a Contract Management Unit Email (required AntD select), e.g. Andrew Jack.
  1752 |     await formItem(page, 'Contract Management Unit Email').getByRole('combobox').click();
  1753 |     await page.getByTitle('Andrew Jack', { exact: true }).first().click();
  1754 | 
  1755 |     // STEP: tick the Confirm checkbox ("I confirm that the appointment letter has been compiled and signed").
  1756 |     await page.locator('div')
  1757 |       .filter({ hasText: 'appointment letter has been compiled and signed' })
  1758 |       .filter({ has: page.getByRole('checkbox') })
  1759 |       .last()
  1760 |       .getByRole('checkbox')
  1761 |       .check();
  1762 | 
  1763 |     // STEP: Submit → awards the tender and advances it out of the stage. Retry against the slow app until the
  1764 |     // status flips to "Awarded" or we leave the page.
  1765 |     const submit = page.getByRole('button', { name: 'Submit', exact: true });
  1766 |     await expect(submit).toBeEnabled({ timeout: 15000 });
  1767 |     await clickOnceAndAwait(submit, async () => {
  1768 |       const awarded = await page.getByText('Awarded', { exact: false }).first().isVisible().catch(() => false);
  1769 |       const capture = await page.getByText('Capture Order Details', { exact: false }).first().isVisible().catch(() => false);
  1770 |       return awarded || capture || /workflows-(my-items|inbox)/.test(page.url());
  1771 |     }, 'Upload Appointment letter');
  1772 |   });
  1773 | 
  1774 |   // ADO Test Case #60848: https://dev.azure.com/boxfusion/PD-SupplyChainManagement/_workitems/edit/60848
  1775 |   // Happy path VERIFIED LIVE 2026-06-04 against REF2026-1399 (Awarded by TC-15). Logged in as TumisangM (same
  1776 |   // user who uploaded the appointment letter) — switch users via clearLocalStorage + /login. ADO Maanda-awe login
  1777 |   // + Export-to-Excel steps are stale. Open the Inbox item (form tender-wf-captureorder-details), capture the four
  1778 |   // required Order Details fields (PO number, date, amount, attachment), then Submit → the tender leaves the
```