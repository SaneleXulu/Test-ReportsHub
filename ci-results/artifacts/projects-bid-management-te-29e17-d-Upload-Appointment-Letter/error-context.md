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

Locator: getByRole('row').filter({ hasText: 'REF2026-0928' }).filter({ hasText: 'Upload Appointment letter' }).first()
Expected: visible
Timeout: 30000ms
Error: element(s) not found

Call log:
  - Expect "toBeVisible" with timeout 30000ms
  - waiting for getByRole('row').filter({ hasText: 'REF2026-0928' }).filter({ hasText: 'Upload Appointment letter' }).first()

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
    - listitem: 1-10 of 154 items
    - listitem "Previous Page":
      - button "left" [disabled]:
        - img "left"
    - listitem "1"
    - listitem "2"
    - listitem "3"
    - listitem "Next 3 Pages":
      - img "double-right"
      - text: •••
    - listitem "16"
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
      - row "search REF2026-1876 Maand-awe Mamathuntsha Tender Process Tender REF2026-1876 - testing the supplier portal Consolidate Responses 31/08/2026 Advertised 4 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=bc0d396b-b67f-463a-8b5f-a6c234a031fe&todoid=152d70f9-cab0-4b7a-b3e5-1e25330d734a
            - img "search"
        - cell "REF2026-1876"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1876 - testing the supplier portal"
        - cell "Consolidate Responses"
        - cell "31/08/2026"
        - cell
        - cell "Advertised"
        - cell "4 day(s) ago"
      - row "search REF2026-1790 Maand-awe Mamathuntsha Tender Process Tender REF2026-1790 - TC-01 Automated Draft Tender run-mtgmjbs0 - 90/10 Compulsory Hybrid Capture Order Details 31/08/2026 Awarded 4 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=f7b74c9a-3229-422d-96e0-8a36f2c227ce&todoid=c9b1d19e-89ca-4373-8ba5-699bc7d4bcf9
            - img "search"
        - cell "REF2026-1790"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1790 - TC-01 Automated Draft Tender run-mtgmjbs0 - 90/10 Compulsory Hybrid"
        - cell "Capture Order Details"
        - cell "31/08/2026"
        - cell
        - cell "Awarded"
        - cell "4 day(s) ago"
      - row "search REF2026-1758 Maand-awe Mamathuntsha Tender Process Tender REF2026-1758 - TC-01 Automated Draft Tender run-mtf738zp - 90/10 Compulsory Hybrid Capture Order Details 30/08/2026 Awarded 5 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=bc3ae043-e1fd-4c8b-91b3-40416eb32c26&todoid=ad7edb71-34d8-4619-9573-83242a0b3f86
            - img "search"
        - cell "REF2026-1758"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1758 - TC-01 Automated Draft Tender run-mtf738zp - 90/10 Compulsory Hybrid"
        - cell "Capture Order Details"
        - cell "30/08/2026"
        - cell
        - cell "Awarded"
        - cell "5 day(s) ago"
      - row "search REF2026-1752 Maand-awe Mamathuntsha Tender Process Tender REF2026-1752 - TC-01 Automated Draft Tender run-mtdrblfn - 90/10 Compulsory Hybrid Capture Order Details 29/08/2026 Awarded 6 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=5acbd489-27de-4fa5-ac15-e63eb5b5b954&todoid=8c19f15f-a1b1-4dfa-9362-83b90c973622
            - img "search"
        - cell "REF2026-1752"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1752 - TC-01 Automated Draft Tender run-mtdrblfn - 90/10 Compulsory Hybrid"
        - cell "Capture Order Details"
        - cell "29/08/2026"
        - cell
        - cell "Awarded"
        - cell "6 day(s) ago"
      - row "search REF2026-1718 Maand-awe Mamathuntsha Tender Process Tender REF2026-1718 - TC-01 Automated Draft Tender run-mtch883q - 90/10 Compulsory Hybrid Capture Order Details 28/08/2026 Awarded 7 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=19d28f4a-b9e5-4558-84a4-801d50f314ea&todoid=1e59db22-32b9-45a2-ad2a-8fabb4fb018a
            - img "search"
        - cell "REF2026-1718"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1718 - TC-01 Automated Draft Tender run-mtch883q - 90/10 Compulsory Hybrid"
        - cell "Capture Order Details"
        - cell "28/08/2026"
        - cell
        - cell "Awarded"
        - cell "7 day(s) ago"
      - row "search REF2026-1655 Maand-awe Mamathuntsha Tender Process Tender REF2026-1655 - TC-01 Automated Draft Tender run-mt9g9tsu - 90/10 Compulsory Hybrid Capture Order Details 26/08/2026 Awarded 9 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=a3da82ca-b086-4518-8f5d-55c75c8be6b1&todoid=f11ec7d2-ad98-482b-ad53-4e2122dc0272
            - img "search"
        - cell "REF2026-1655"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1655 - TC-01 Automated Draft Tender run-mt9g9tsu - 90/10 Compulsory Hybrid"
        - cell "Capture Order Details"
        - cell "26/08/2026"
        - cell
        - cell "Awarded"
        - cell "9 day(s) ago"
      - row "search REF2026-1267 Maand-awe Mamathuntsha Tender Process Tender REF2026-1267 - supplier portral7 (not required. Publish to all 3) Consolidate Responses 20/08/2026 Advertised 15 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=2945e0d4-193d-4f81-9706-5b8c041bee99&todoid=881cf0ac-c905-402e-a153-215fb1ee29a5
            - img "search"
        - cell "REF2026-1267"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1267 - supplier portral7 (not required. Publish to all 3)"
        - cell "Consolidate Responses"
        - cell "20/08/2026"
        - cell
        - cell "Advertised"
        - cell "15 day(s) ago"
      - row "search REF2026-1296 Maand-awe Mamathuntsha Tender Process Tender REF2026-1296 - TC-01 Automated Draft Tender run-mszemfq3 - 90/10 Compulsory Hybrid Capture Order Details 19/08/2026 Awarded 16 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=f1bd0958-cce5-4cd0-82b2-b53b3088eb9a&todoid=73f08ed8-3147-4fdb-90a4-bb932b4e62b4
            - img "search"
        - cell "REF2026-1296"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1296 - TC-01 Automated Draft Tender run-mszemfq3 - 90/10 Compulsory Hybrid"
        - cell "Capture Order Details"
        - cell "19/08/2026"
        - cell
        - cell "Awarded"
        - cell "16 day(s) ago"
      - row "search REF2026-1262 Maand-awe Mamathuntsha Tender Process Tender REF2026-1262 - supplier portal6 Consolidate Responses 14/08/2026 Advertised 21 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=d2d4b587-53da-4b5a-ba72-9379a5785c3a&todoid=16b2c1f4-8748-4bf6-8bc8-c4d47afad366
            - img "search"
        - cell "REF2026-1262"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1262 - supplier portal6"
        - cell "Consolidate Responses"
        - cell "14/08/2026"
        - cell
        - cell "Advertised"
        - cell "21 day(s) ago"
      - row "search REF2026-1257 Maand-awe Mamathuntsha Tender Process Tender REF2026-1257 - supplier portal 5 Consolidate Responses 14/08/2026 Advertised 21 day(s) ago":
        - cell "search":
          - link "search":
            - /url: /shesha/workflow-action?id=25093164-f744-477f-8895-c70d6516551b&todoid=66ed533a-294a-4be7-8259-df7e17662235
            - img "search"
        - cell "REF2026-1257"
        - cell "Maand-awe Mamathuntsha"
        - cell "Tender Process"
        - cell "Tender REF2026-1257 - supplier portal 5"
        - cell "Consolidate Responses"
        - cell "14/08/2026"
        - cell
        - cell "Advertised"
        - cell "21 day(s) ago"
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