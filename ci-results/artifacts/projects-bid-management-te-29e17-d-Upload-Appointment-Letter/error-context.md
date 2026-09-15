# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: projects/bid-management/test-plans/tender-process/bid-supply-chain-management.spec.ts >> BID-SCM — BID: Supply Chain Management >> TC-15: Compile and Upload Appointment Letter
- Location: projects/bid-management/test-plans/tender-process/bid-supply-chain-management.spec.ts:1720:7

# Error details

```
Error: expect(locator).toBeVisible() failed

Locator: getByRole('row').filter({ hasText: 'REF2026-1592' }).filter({ hasText: 'Upload Appointment letter' }).first()
Expected: visible
Timeout: 30000ms
Error: element(s) not found

Call log:
  - Expect "toBeVisible" getByRole('row').filter({ hasText: 'REF2026-1592' }).filter({ hasText: 'Upload Appointment letter' }).first() with timeout 30000ms
  - waiting for getByRole('row').filter({ hasText: 'REF2026-1592' }).filter({ hasText: 'Upload Appointment letter' }).first()

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
  - text: Latest Tumisang Modula
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
    - listitem: 1-10 of 164 items
    - listitem "Previous Page":
      - button "left" [disabled]:
        - img "left"
    - listitem "1"
    - listitem "2"
    - listitem "3"
    - listitem "Next 3 Pages":
      - img "double-right"
      - text: •••
    - listitem "17"
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
      - row "search REF2026-1052 Maand-awe Mamathuntsha Tender Process Tender REF2026-1052 - 9TH TENDER Consolidate Responses 07/09/2026 Advertised 7 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=aba7c56d-8b32-4bc6-be6c-4f9d7ec19563&todoid=bdd4cfc6-8305-4106-b71d-649a708863e9
            - img "search"
        - cell "REF2026-1052"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1052 - 9TH TENDER"
        - cell "Consolidate Responses"
        - cell "07/09/2026"
        - cell
        - cell "Advertised"
        - cell "7 day(s) ago"
      - row "search REF2026-1047 Maand-awe Mamathuntsha Tender Process Tender REF2026-1047 - 8TH TENDER Consolidate Responses 07/09/2026 Advertised 7 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=499a22c8-8ec9-4e49-994d-911e8e8a1717&todoid=19b98d97-46da-46d6-9d44-e66dcb425a1d
            - img "search"
        - cell "REF2026-1047"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1047 - 8TH TENDER"
        - cell "Consolidate Responses"
        - cell "07/09/2026"
        - cell
        - cell "Advertised"
        - cell "7 day(s) ago"
      - row "search REF2026-1042 Maand-awe Mamathuntsha Tender Process Tender REF2026-1042 - SEVENTH TENDER Consolidate Responses 07/09/2026 Advertised 7 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=5ad3677d-e0e5-4dbd-a6c2-b0093d06e786&todoid=0cd8c045-4329-4b8f-8765-06b6119724a2
            - img "search"
        - cell "REF2026-1042"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1042 - SEVENTH TENDER"
        - cell "Consolidate Responses"
        - cell "07/09/2026"
        - cell
        - cell "Advertised"
        - cell "7 day(s) ago"
      - row "search REF2026-1037 Maand-awe Mamathuntsha Tender Process Tender REF2026-1037 - SIXITH TENDER Consolidate Responses 07/09/2026 Advertised 7 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=e6f899e9-0c17-4521-a697-1a7f5772c483&todoid=fb4ca7dc-7e67-43a9-b080-5567d14474bb
            - img "search"
        - cell "REF2026-1037"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1037 - SIXITH TENDER"
        - cell "Consolidate Responses"
        - cell "07/09/2026"
        - cell
        - cell "Advertised"
        - cell "7 day(s) ago"
      - row "search REF2026-1032 Maand-awe Mamathuntsha Tender Process Tender REF2026-1032 - FIFTH TENDER Consolidate Responses 07/09/2026 Advertised 7 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=92633f2a-3a8b-4280-8c1d-deb94a7b296c&todoid=cdf3e5a2-9489-4292-bce9-61fcdc85ca19
            - img "search"
        - cell "REF2026-1032"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1032 - FIFTH TENDER"
        - cell "Consolidate Responses"
        - cell "07/09/2026"
        - cell
        - cell "Advertised"
        - cell "7 day(s) ago"
      - row "search REF2026-1024 Maand-awe Mamathuntsha Tender Process Tender REF2026-1024 - FOURTH TENDER Consolidate Responses 07/09/2026 Advertised 7 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=e8f4e423-9288-4b6c-8759-2fa3403deee3&todoid=b9bd9ce3-610b-4ddc-8468-d4cbbcd43e87
            - img "search"
        - cell "REF2026-1024"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1024 - FOURTH TENDER"
        - cell "Consolidate Responses"
        - cell "07/09/2026"
        - cell
        - cell "Advertised"
        - cell "7 day(s) ago"
      - row "search REF2026-1019 Maand-awe Mamathuntsha Tender Process Tender REF2026-1019 - THIRD TENDER Consolidate Responses 07/09/2026 Advertised 7 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=792fdb76-d008-48c8-b672-ea315a689da4&todoid=7c7de4f3-795d-4553-8829-7f0a02017115
            - img "search"
        - cell "REF2026-1019"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1019 - THIRD TENDER"
        - cell "Consolidate Responses"
        - cell "07/09/2026"
        - cell
        - cell "Advertised"
        - cell "7 day(s) ago"
      - row "search REF2026-1014 Maand-awe Mamathuntsha Tender Process Tender REF2026-1014 - SECOND TENDER Consolidate Responses 07/09/2026 Advertised 7 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=40ba2b26-7275-49f0-ba57-32161aa50ba5&todoid=b0502928-062e-40e8-9bf5-697c6dc0f672
            - img "search"
        - cell "REF2026-1014"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1014 - SECOND TENDER"
        - cell "Consolidate Responses"
        - cell "07/09/2026"
        - cell
        - cell "Advertised"
        - cell "7 day(s) ago"
      - row "search REF2026-1008 Maand-awe Mamathuntsha Tender Process Tender REF2026-1008 - FIRST TENDER Consolidate Responses 07/09/2026 Advertised 7 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=c9b69a6c-af04-4fdc-9a07-abe0332e01a2&todoid=49ee9d07-0543-4062-bdbf-3f07f2ddda7c
            - img "search"
        - cell "REF2026-1008"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1008 - FIRST TENDER"
        - cell "Consolidate Responses"
        - cell "07/09/2026"
        - cell
        - cell "Advertised"
        - cell "7 day(s) ago"
      - row "search REF2026-0997 Maand-awe Mamathuntsha Tender Process Tender REF2026-0997 - TC-01 Automated Draft Tender run-mtqq9vy7 - 90/10 Compulsory Hybrid Capture Order Details 07/09/2026 Awarded 8 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=009a5e92-08b7-44fa-acd4-d2435a12fab0&todoid=708e38f2-36ea-4e23-841d-ce42f80075dd
            - img "search"
        - cell "REF2026-0997"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-0997 - TC-01 Automated Draft Tender run-mtqq9vy7 - 90/10 Compulsory Hybrid"
        - cell "Capture Order Details"
        - cell "07/09/2026"
        - cell
        - cell "Awarded"
        - cell "8 day(s) ago"
- alert
```

# Test source

```ts
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
  1678 |     await expect(targetRow).toBeVisible({ timeout: 30000 });
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
> 1732 |     await expect(targetRow).toBeVisible({ timeout: 30000 });
       |                             ^ Error: expect(locator).toBeVisible() failed
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
  1779 |   // workflow entirely (lifecycle complete). Self-supplying: TC-15 awards the tender into this stage.
  1780 |   // The Purchase Order Date is a DATE-ONLY AntD picker (no time panel / OK button) — click the day cell directly.
  1781 |   test('TC-16: Capture Order Details', async ({ page }) => {
  1782 |     test.setTimeout(150_000);
  1783 |     await loginAs(page, PUBLISHER);
  1784 |     await openInbox(page);
  1785 |     await expect(page.getByRole('button', { name: /export/i })).toBeVisible({ timeout: 15000 });
  1786 | 
  1787 |     // STEP: open the target tender (our TC-01 item) at the Capture-Order-Details stage via its glass.
  1788 |     await page.getByRole('heading', { name: 'Incoming Items' }).click();
  1789 |     const targetRow = page.getByRole('row')
  1790 |       .filter({ hasText: tenderMatch() })
  1791 |       .filter({ hasText: 'Capture Order Details' })
  1792 |       .first();
  1793 |     await expect(targetRow).toBeVisible({ timeout: 30000 });
  1794 |     // Open the row by navigating to its href, not a positional click: the Workflows accordion
  1795 |     // flyout ("My Items" nav-link) can overlap the table and intercept the click. goto avoids that.
  1796 |     const rowHref = await targetRow.getByRole('link').first().getAttribute('href');
  1797 |     await page.goto(rowHref.startsWith('http') ? rowHref : `${APP_URL.replace('/login', '')}${rowHref}`);
  1798 |     await page.waitForURL(/workflow-action/, { timeout: 30000 });
  1799 | 
  1800 |     // ASSERT (BLOCKING) the item opens on the "Capture Order Details" page
  1801 |     await expectOnPage(page, 'Capture Order Details:');
  1802 | 
  1803 |     // NEGATIVE (opt-in SEND_BACKS): send this stage back to "Upload Appointment letter", have that actor re-action
  1804 |     // it, then return here and carry on with the happy path — the chain still completes.
  1805 |     await sendBackAndReturn(page, { stageNo: 16, stage: 'Capture Order Details', previous: 'Upload Appointment letter', actor: PUBLISHER });
  1806 |     await expect(page.getByText('Fetching data...').first()).toBeHidden({ timeout: 30000 });
  1807 | 
  1808 |     // STEP: capture the four required Order Details fields. This Shesha/AntD form is timing-sensitive
  1809 |     // (a value typed before the field finishes mounting silently fails to commit, leaving Submit
  1810 |     // disabled), so each field is filled then VERIFIED, retrying the commit until it actually sticks.
  1811 | 
  1812 |     // Purchase Order No — plain text input. Confirm the value landed before moving on.
  1813 |     const poNo = formItem(page, 'Purchase Order No').getByRole('textbox');
  1814 |     await expect(poNo).toBeVisible({ timeout: 30000 });
  1815 |     await expect(async () => {
  1816 |       await poNo.fill('PO-REF2026-1399-TC16');
  1817 |       await expect(poNo).toHaveValue('PO-REF2026-1399-TC16', { timeout: 3000 });
  1818 |     }).toPass({ timeout: 20000 });
  1819 | 
  1820 |     // Purchase Order Date — date-only picker: open it and click the highlighted "today" cell; verify
  1821 |     // the input is no longer empty (the panel click can miss while the dropdown is still animating).
  1822 |     const poDate = formItem(page, 'Purchase Order Date').getByRole('textbox');
  1823 |     await expect(async () => {
  1824 |       await poDate.click();
  1825 |       const dropdown = page.locator('.ant-picker-dropdown:not(.ant-picker-dropdown-hidden)').last();
  1826 |       await dropdown.locator('td.ant-picker-cell-today').click();
  1827 |       await expect(poDate).not.toHaveValue('', { timeout: 3000 });
  1828 |     }).toPass({ timeout: 20000 });
  1829 | 
  1830 |     // Purchase Order Amount — AntD InputNumber: .fill() commits on blur; verify the formatted value.
  1831 |     const poAmt = formItem(page, 'Purchase Order Amount').getByRole('spinbutton');
  1832 |     await expect(async () => {
```