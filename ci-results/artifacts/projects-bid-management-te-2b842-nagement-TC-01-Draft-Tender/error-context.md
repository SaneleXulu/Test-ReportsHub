# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: projects/bid-management/test-plans/tender-process/bid-supply-chain-management.spec.ts >> BID-SCM — BID: Supply Chain Management >> TC-01: Draft Tender
- Location: projects/bid-management/test-plans/tender-process/bid-supply-chain-management.spec.ts:816:7

# Error details

```
Test timeout of 180000ms exceeded.
```

```
Error: locator.click: Test timeout of 180000ms exceeded.
Call log:
  - waiting for locator('.ant-picker-dropdown:not(.ant-picker-dropdown-hidden)').last().locator('td[title="2026-10-29"]')

```

# Page snapshot

```yaml
- generic [ref=e1]:
  - generic [ref=e4]:
    - complementary [ref=e5]:
      - menu [ref=e9]:
        - menuitem "menu-unfold SupplyChain Management" [ref=e10] [cursor=pointer]:
          - img "menu-unfold" [ref=e11]
          - generic [ref=e14]: SupplyChain Management
        - menuitem "container Bid Management" [ref=e15] [cursor=pointer]:
          - img "container" [ref=e16]
          - generic [ref=e19]: Bid Management
        - menuitem "file-text Contract Management" [ref=e20] [cursor=pointer]:
          - img "file-text" [ref=e21]
          - generic [ref=e24]: Contract Management
        - menuitem "account-book Requisition" [ref=e25] [cursor=pointer]:
          - img "account-book" [ref=e26]
          - generic [ref=e29]: Requisition
        - menuitem "apartment Workflows" [ref=e30] [cursor=pointer]:
          - img "apartment" [ref=e31]
          - generic [ref=e34]: Workflows
        - menuitem "setting Configurations" [ref=e35] [cursor=pointer]:
          - img "setting" [ref=e36]
          - generic [ref=e39]: Configurations
        - menuitem "tool Administration" [ref=e40] [cursor=pointer]:
          - img "tool" [ref=e41]
          - generic [ref=e44]: Administration
      - img "menu-unfold" [ref=e47] [cursor=pointer]
    - generic [ref=e50]:
      - banner [ref=e51]:
        - generic [ref=e57]:
          - generic [ref=e59]:
            - button [ref=e60] [cursor=pointer]:
              - img "edit" [ref=e61]
            - paragraph [ref=e64] [cursor=pointer]: Shesha/header v9
            - generic [ref=e65]:
              - generic [ref=e66]: Live
              - img "close" [ref=e67] [cursor=pointer]
          - generic [ref=e78]:
            - link [ref=e84] [cursor=pointer]:
              - /url: /
            - generic [ref=e96]:
              - generic [ref=e97]:
                - generic [ref=e99]:
                  - generic [ref=e100]: Live Mode
                  - switch "Switch to Edit mode" [ref=e102] [cursor=pointer]
                - generic "Click to change view mode" [ref=e106] [cursor=pointer]:
                  - img "block" [ref=e107]
                  - generic [ref=e110]: Latest
              - generic [ref=e112]:
                - generic [ref=e113] [cursor=pointer]:
                  - text: Maand-awe Mamathuntsha
                  - img "down" [ref=e114]
                - img "user" [ref=e118]
      - main [ref=e121]:
        - generic [ref=e126]:
          - generic [ref=e127]:
            - generic [ref=e130]:
              - heading [level=4] [ref=e132]:
                - strong [ref=e133]: "Capture Tender Details:"
              - generic [ref=e134]: Draft
            - generic [ref=e138]:
              - generic [ref=e139]: "Ref No: REF2026-1991"
              - generic [ref=e140]: "Created by: Maand-awe Mamathuntsha in 2 hours"
          - generic [ref=e144]:
            - generic [ref=e146]:
              - button [ref=e147] [cursor=pointer]:
                - img "edit" [ref=e148]
              - paragraph [ref=e151] [cursor=pointer]: Shesha.SupplyChainManagement/capture-tender-details v48
              - generic [ref=e152]:
                - generic [ref=e153]: Live
                - img "close" [ref=e154] [cursor=pointer]
            - generic [ref=e167]:
              - generic [ref=e168]:
                - generic [ref=e169]:
                  - generic [ref=e171]:
                    - generic [ref=e172]: "1"
                    - generic [ref=e173]: Tender Details
                  - generic [ref=e176]:
                    - generic [ref=e177]: "2"
                    - generic [ref=e178]: Tender Documents
                  - generic [ref=e181]:
                    - generic [ref=e182]: "3"
                    - generic [ref=e183]: Response Documents
                  - generic [ref=e186]:
                    - generic [ref=e187]: "4"
                    - generic [ref=e188]: Technical Evaluation
                  - generic [ref=e191]:
                    - generic [ref=e192]: "5"
                    - generic [ref=e193]: Summary
                - generic [ref=e198]:
                  - generic [ref=e203]:
                    - generic [ref=e204]:
                      - img "right" [ref=e206] [cursor=pointer]
                      - generic [ref=e209]: Tender Information
                    - generic [ref=e217]:
                      - generic [ref=e219]:
                        - generic "Tender Number" [ref=e221]:
                          - text: Tender Number
                          - generic [ref=e222]: "*"
                        - generic [ref=e223]: REF2026-1991
                      - generic [ref=e227]:
                        - generic "Tender Name" [ref=e229]:
                          - text: Tender Name
                          - generic [ref=e230]: "*"
                        - textbox [ref=e235]: TC-01 Automated Draft Tender run-mvory0ul - 90/10 Compulsory Hybrid
                      - generic [ref=e237]:
                        - generic "Description" [ref=e239]:
                          - text: Description
                          - generic [ref=e240]: "*"
                        - textbox [ref=e244]: Automated TC-01 draft tender created via Playwright on the QA site.
                      - generic [ref=e246]:
                        - generic "Evaluation Criteria" [ref=e248]
                        - generic [ref=e253]:
                          - generic [ref=e255] [cursor=pointer]:
                            - radio "90/10" [checked] [ref=e257]
                            - generic [ref=e259]: 90/10
                          - generic [ref=e261] [cursor=pointer]:
                            - radio "80/20" [ref=e263]
                            - generic [ref=e265]: 80/20
                      - generic [ref=e267]:
                        - generic "Is On Procurement Plan" [ref=e269]
                        - checkbox [ref=e275] [cursor=pointer]
                      - generic [ref=e278]:
                        - generic "Procurement plan" [ref=e280]
                        - button "upload (press to upload)" [ref=e288] [cursor=pointer]:
                          - img "upload" [ref=e290]
                          - generic [ref=e293]: (press to upload)
                  - generic [ref=e300]:
                    - generic [ref=e301]:
                      - img "right" [ref=e303] [cursor=pointer]
                      - generic [ref=e306]: Tender Publication
                    - generic [ref=e311]:
                      - generic [ref=e314]:
                        - heading "Briefing Session" [level=5] [ref=e320]
                        - generic [ref=e322]:
                          - generic [ref=e324]:
                            - generic "Briefing Session Requirement" [ref=e326]
                            - generic [ref=e331]:
                              - generic [ref=e333] [cursor=pointer]:
                                - radio "Not Required" [ref=e335]
                                - generic [ref=e337]: Not Required
                              - generic [ref=e339] [cursor=pointer]:
                                - radio "Compulsory" [checked] [ref=e341]
                                - generic [ref=e343]: Compulsory
                              - generic [ref=e345] [cursor=pointer]:
                                - radio "Non Compulsory" [ref=e347]
                                - generic [ref=e349]: Non Compulsory
                          - generic [ref=e351]:
                            - generic "Briefing Session Start Time" [ref=e353]:
                              - text: Briefing Session Start Time
                              - generic [ref=e354]: "*"
                            - generic [ref=e359]:
                              - textbox [ref=e360]
                              - generic:
                                - img "calendar"
                          - generic [ref=e362]:
                            - generic "Briefing Method" [ref=e364]:
                              - text: Briefing Method
                              - generic [ref=e365]: "*"
                            - generic [ref=e370]:
                              - generic [ref=e372] [cursor=pointer]:
                                - radio "Online" [ref=e374]
                                - generic [ref=e376]: Online
                              - generic [ref=e378] [cursor=pointer]:
                                - radio "Physical" [ref=e380]
                                - generic [ref=e382]: Physical
                              - generic [ref=e384] [cursor=pointer]:
                                - radio "Hybrid" [checked] [ref=e386]
                                - generic [ref=e388]: Hybrid
                          - generic [ref=e390]:
                            - generic "Meeting link" [ref=e392]:
                              - text: Meeting link
                              - generic [ref=e393]: "*"
                            - textbox [ref=e398]: https://teams.microsoft.com/l/meetup-join/tc02-automated
                          - generic [ref=e400]:
                            - generic "Briefing Session Venue" [ref=e402]:
                              - text: Briefing Session Venue
                              - generic [ref=e403]: "*"
                            - textbox [ref=e408]: Boardroom A, Head Office
                      - generic [ref=e411]:
                        - heading "Publication Dates" [level=5] [ref=e417]
                        - generic [ref=e419]:
                          - generic [ref=e421]:
                            - generic "Bid publication Date" [ref=e423]:
                              - text: Bid publication Date
                              - generic [ref=e424]: "*"
                            - generic [ref=e429]:
                              - textbox [ref=e430]
                              - generic:
                                - img "calendar"
                          - generic [ref=e432]:
                            - generic "Bid closing Date" [ref=e434]:
                              - text: Bid closing Date
                              - generic [ref=e435]: "*"
                            - generic [ref=e440]:
                              - textbox [ref=e441]
                              - generic:
                                - img "calendar"
                      - generic [ref=e444]:
                        - heading "Contact Details" [level=5] [ref=e450]
                        - generic [ref=e452]:
                          - generic [ref=e454]:
                            - generic "Contact person name" [ref=e456]:
                              - text: Contact person name
                              - generic [ref=e457]: "*"
                            - textbox [ref=e462]: Maanda Mamathuntsha
                          - generic [ref=e464]:
                            - generic "Telephone" [ref=e466]:
                              - text: Telephone
                              - generic [ref=e467]: "*"
                            - textbox [ref=e472]: "0123456789"
                          - generic [ref=e474]:
                            - generic "Email" [ref=e476]:
                              - text: Email
                              - generic [ref=e477]: "*"
                            - textbox [ref=e482]: maanda.test@example.com
                  - generic [ref=e487]:
                    - generic [ref=e488]:
                      - img "right" [ref=e490] [cursor=pointer]
                      - generic [ref=e493]: Supporting Documents
                    - generic [ref=e497]:
                      - alert [ref=e498]:
                        - img "info-circle" [ref=e499]
                        - generic [ref=e502]: Attach all documents demonstrating that all necessary processes were followed and approvals granted.
                        - button [ref=e505] [cursor=pointer]:
                          - img "close" [ref=e506]
                      - generic [ref=e512]:
                        - generic "Supporting documents" [ref=e514]
                        - button "upload (press to upload)" [ref=e522] [cursor=pointer]:
                          - img "upload" [ref=e524]
                          - generic [ref=e527]: (press to upload)
              - generic [ref=e529]:
                - button "Close" [ref=e530] [cursor=pointer]
                - button "Next" [disabled] [ref=e532]
  - alert [ref=e533]
  - generic [ref=e536]:
    - generic [ref=e538]:
      - generic [ref=e539]:
        - generic [ref=e540]:
          - button [ref=e541] [cursor=pointer]
          - button [ref=e543] [cursor=pointer]
          - generic [ref=e545]:
            - button "Oct" [ref=e546] [cursor=pointer]
            - button "2028" [ref=e547] [cursor=pointer]
          - button [active] [ref=e548] [cursor=pointer]
          - button [ref=e550] [cursor=pointer]
        - table [ref=e553]:
          - rowgroup [ref=e554]:
            - row [ref=e555]:
              - columnheader "Su" [ref=e556]
              - columnheader "Mo" [ref=e557]
              - columnheader "Tu" [ref=e558]
              - columnheader "We" [ref=e559]
              - columnheader "Th" [ref=e560]
              - columnheader "Fr" [ref=e561]
              - columnheader "Sa" [ref=e562]
          - rowgroup [ref=e563]:
            - row [ref=e564]:
              - cell "1" [ref=e565] [cursor=pointer]
              - cell "2" [ref=e567] [cursor=pointer]
              - cell "3" [ref=e569] [cursor=pointer]
              - cell "4" [ref=e571] [cursor=pointer]
              - cell "5" [ref=e573] [cursor=pointer]
              - cell "6" [ref=e575] [cursor=pointer]
              - cell "7" [ref=e577] [cursor=pointer]
            - row [ref=e579]:
              - cell "8" [ref=e580] [cursor=pointer]
              - cell "9" [ref=e582] [cursor=pointer]
              - cell "10" [ref=e584] [cursor=pointer]
              - cell "11" [ref=e586] [cursor=pointer]
              - cell "12" [ref=e588] [cursor=pointer]
              - cell "13" [ref=e590] [cursor=pointer]
              - cell "14" [ref=e592] [cursor=pointer]
            - row [ref=e594]:
              - cell "15" [ref=e595] [cursor=pointer]
              - cell "16" [ref=e597] [cursor=pointer]
              - cell "17" [ref=e599] [cursor=pointer]
              - cell "18" [ref=e601] [cursor=pointer]
              - cell "19" [ref=e603] [cursor=pointer]
              - cell "20" [ref=e605] [cursor=pointer]
              - cell "21" [ref=e607] [cursor=pointer]
            - row [ref=e609]:
              - cell "22" [ref=e610] [cursor=pointer]
              - cell "23" [ref=e612] [cursor=pointer]
              - cell "24" [ref=e614] [cursor=pointer]
              - cell "25" [ref=e616] [cursor=pointer]
              - cell "26" [ref=e618] [cursor=pointer]
              - cell "27" [ref=e620] [cursor=pointer]
              - cell "28" [ref=e622] [cursor=pointer]
            - row [ref=e624]:
              - cell "29" [ref=e625] [cursor=pointer]
              - cell "30" [ref=e627] [cursor=pointer]
              - cell "31" [ref=e629] [cursor=pointer]
              - cell "1" [ref=e631] [cursor=pointer]
              - cell "2" [ref=e633] [cursor=pointer]
              - cell "3" [ref=e635] [cursor=pointer]
              - cell "4" [ref=e637] [cursor=pointer]
            - row [ref=e639]:
              - cell "5" [ref=e640] [cursor=pointer]
              - cell "6" [ref=e642] [cursor=pointer]
              - cell "7" [ref=e644] [cursor=pointer]
              - cell "8" [ref=e646] [cursor=pointer]
              - cell "9" [ref=e648] [cursor=pointer]
              - cell "10" [ref=e650] [cursor=pointer]
              - cell "11" [ref=e652] [cursor=pointer]
      - generic [ref=e657]:
        - list [ref=e658]:
          - listitem [ref=e659]:
            - generic [ref=e660] [cursor=pointer]: "00"
          - listitem [ref=e661]:
            - generic [ref=e662] [cursor=pointer]: "01"
          - listitem [ref=e663]:
            - generic [ref=e664] [cursor=pointer]: "02"
          - listitem [ref=e665]:
            - generic [ref=e666] [cursor=pointer]: "03"
          - listitem [ref=e667]:
            - generic [ref=e668] [cursor=pointer]: "04"
          - listitem [ref=e669]:
            - generic [ref=e670] [cursor=pointer]: "05"
          - listitem [ref=e671]:
            - generic [ref=e672] [cursor=pointer]: "06"
          - listitem [ref=e673]:
            - generic [ref=e674] [cursor=pointer]: "07"
          - listitem [ref=e675]:
            - generic [ref=e676] [cursor=pointer]: "08"
          - listitem [ref=e677]:
            - generic [ref=e678] [cursor=pointer]: "09"
          - listitem [ref=e679]:
            - generic [ref=e680] [cursor=pointer]: "10"
          - listitem [ref=e681]:
            - generic [ref=e682] [cursor=pointer]: "11"
          - listitem [ref=e683]:
            - generic [ref=e684] [cursor=pointer]: "12"
          - listitem [ref=e685]:
            - generic [ref=e686] [cursor=pointer]: "13"
          - listitem [ref=e687]:
            - generic [ref=e688] [cursor=pointer]: "14"
          - listitem [ref=e689]:
            - generic [ref=e690] [cursor=pointer]: "15"
          - listitem [ref=e691]:
            - generic [ref=e692] [cursor=pointer]: "16"
          - listitem [ref=e693]:
            - generic [ref=e694] [cursor=pointer]: "17"
          - listitem [ref=e695]:
            - generic [ref=e696] [cursor=pointer]: "18"
          - listitem [ref=e697]:
            - generic [ref=e698] [cursor=pointer]: "19"
          - listitem [ref=e699]:
            - generic [ref=e700] [cursor=pointer]: "20"
          - listitem [ref=e701]:
            - generic [ref=e702] [cursor=pointer]: "21"
          - listitem [ref=e703]:
            - generic [ref=e704] [cursor=pointer]: "22"
          - listitem [ref=e705]:
            - generic [ref=e706] [cursor=pointer]: "23"
        - list [ref=e707]:
          - listitem [ref=e708]:
            - generic [ref=e709] [cursor=pointer]: "00"
          - listitem [ref=e710]:
            - generic [ref=e711] [cursor=pointer]: "01"
          - listitem [ref=e712]:
            - generic [ref=e713] [cursor=pointer]: "02"
          - listitem [ref=e714]:
            - generic [ref=e715] [cursor=pointer]: "03"
          - listitem [ref=e716]:
            - generic [ref=e717] [cursor=pointer]: "04"
          - listitem [ref=e718]:
            - generic [ref=e719] [cursor=pointer]: "05"
          - listitem [ref=e720]:
            - generic [ref=e721] [cursor=pointer]: "06"
          - listitem [ref=e722]:
            - generic [ref=e723] [cursor=pointer]: "07"
          - listitem [ref=e724]:
            - generic [ref=e725] [cursor=pointer]: "08"
          - listitem [ref=e726]:
            - generic [ref=e727] [cursor=pointer]: "09"
          - listitem [ref=e728]:
            - generic [ref=e729] [cursor=pointer]: "10"
          - listitem [ref=e730]:
            - generic [ref=e731] [cursor=pointer]: "11"
          - listitem [ref=e732]:
            - generic [ref=e733] [cursor=pointer]: "12"
          - listitem [ref=e734]:
            - generic [ref=e735] [cursor=pointer]: "13"
          - listitem [ref=e736]:
            - generic [ref=e737] [cursor=pointer]: "14"
          - listitem [ref=e738]:
            - generic [ref=e739] [cursor=pointer]: "15"
          - listitem [ref=e740]:
            - generic [ref=e741] [cursor=pointer]: "16"
          - listitem [ref=e742]:
            - generic [ref=e743] [cursor=pointer]: "17"
          - listitem [ref=e744]:
            - generic [ref=e745] [cursor=pointer]: "18"
          - listitem [ref=e746]:
            - generic [ref=e747] [cursor=pointer]: "19"
          - listitem [ref=e748]:
            - generic [ref=e749] [cursor=pointer]: "20"
          - listitem [ref=e750]:
            - generic [ref=e751] [cursor=pointer]: "21"
          - listitem [ref=e752]:
            - generic [ref=e753] [cursor=pointer]: "22"
          - listitem [ref=e754]:
            - generic [ref=e755] [cursor=pointer]: "23"
          - listitem [ref=e756]:
            - generic [ref=e757] [cursor=pointer]: "24"
          - listitem [ref=e758]:
            - generic [ref=e759] [cursor=pointer]: "25"
          - listitem [ref=e760]:
            - generic [ref=e761] [cursor=pointer]: "26"
          - listitem [ref=e762]:
            - generic [ref=e763] [cursor=pointer]: "27"
          - listitem [ref=e764]:
            - generic [ref=e765] [cursor=pointer]: "28"
          - listitem [ref=e766]:
            - generic [ref=e767] [cursor=pointer]: "29"
          - listitem [ref=e768]:
            - generic [ref=e769] [cursor=pointer]: "30"
          - listitem [ref=e770]:
            - generic [ref=e771] [cursor=pointer]: "31"
          - listitem [ref=e772]:
            - generic [ref=e773] [cursor=pointer]: "32"
          - listitem [ref=e774]:
            - generic [ref=e775] [cursor=pointer]: "33"
          - listitem [ref=e776]:
            - generic [ref=e777] [cursor=pointer]: "34"
          - listitem [ref=e778]:
            - generic [ref=e779] [cursor=pointer]: "35"
          - listitem [ref=e780]:
            - generic [ref=e781] [cursor=pointer]: "36"
          - listitem [ref=e782]:
            - generic [ref=e783] [cursor=pointer]: "37"
          - listitem [ref=e784]:
            - generic [ref=e785] [cursor=pointer]: "38"
          - listitem [ref=e786]:
            - generic [ref=e787] [cursor=pointer]: "39"
          - listitem [ref=e788]:
            - generic [ref=e789] [cursor=pointer]: "40"
          - listitem [ref=e790]:
            - generic [ref=e791] [cursor=pointer]: "41"
          - listitem [ref=e792]:
            - generic [ref=e793] [cursor=pointer]: "42"
          - listitem [ref=e794]:
            - generic [ref=e795] [cursor=pointer]: "43"
          - listitem [ref=e796]:
            - generic [ref=e797] [cursor=pointer]: "44"
          - listitem [ref=e798]:
            - generic [ref=e799] [cursor=pointer]: "45"
          - listitem [ref=e800]:
            - generic [ref=e801] [cursor=pointer]: "46"
          - listitem [ref=e802]:
            - generic [ref=e803] [cursor=pointer]: "47"
          - listitem [ref=e804]:
            - generic [ref=e805] [cursor=pointer]: "48"
          - listitem [ref=e806]:
            - generic [ref=e807] [cursor=pointer]: "49"
          - listitem [ref=e808]:
            - generic [ref=e809] [cursor=pointer]: "50"
          - listitem [ref=e810]:
            - generic [ref=e811] [cursor=pointer]: "51"
          - listitem [ref=e812]:
            - generic [ref=e813] [cursor=pointer]: "52"
          - listitem [ref=e814]:
            - generic [ref=e815] [cursor=pointer]: "53"
          - listitem [ref=e816]:
            - generic [ref=e817] [cursor=pointer]: "54"
          - listitem [ref=e818]:
            - generic [ref=e819] [cursor=pointer]: "55"
          - listitem [ref=e820]:
            - generic [ref=e821] [cursor=pointer]: "56"
          - listitem [ref=e822]:
            - generic [ref=e823] [cursor=pointer]: "57"
          - listitem [ref=e824]:
            - generic [ref=e825] [cursor=pointer]: "58"
          - listitem [ref=e826]:
            - generic [ref=e827] [cursor=pointer]: "59"
    - list [ref=e829]:
      - listitem [ref=e830]:
        - button "OK" [disabled] [ref=e831]
```

# Test source

```ts
  70  | // stores the full name here. Every downstream TC targets THIS tender (via tenderMatch()) instead of
  71  | // `.first()` at the stage — so a broken chain can't be masked by an unrelated leftover item passing
  72  | // in its place. Falls back to the generic name when TC-01 didn't run this session (single-TC runs).
  73  | const RUN_TAG = `run-${Date.now().toString(36)}`;
  74  | let RUN_TENDER = '';
  75  | // The app-assigned Ref No (e.g. REF2026-2160) of the tender TC-01 creates. The Evaluate-Tenders list
  76  | // (TC-09) is paginated and its search box matches the REF, NOT the tender name — so downstream
  77  | // evaluate-stage TCs must search by this REF to find the right card rather than scanning page 1.
  78  | // Can be seeded via the RUN_REF env var to validate the evaluate-stage TCs standalone (without TC-01).
  79  | let RUN_REF = process.env.RUN_REF || '';
  80  | 
  81  | // ⚠️ The REF must survive a WORKER RESTART. Playwright tears down the worker process after a test
  82  | // fails and starts a fresh one for the remaining tests — which re-imports this module and wipes every
  83  | // module-level `let`. On 2026-07-30 that silently broke the 80/20 chain: TC-04 failed, RUN_REF reset
  84  | // to '', tenderMatch() fell back to the generic name, and TC-05→TC-16 each grabbed whatever unrelated
  85  | // LEFTOVER tender happened to sit at their stage (they all "passed" against REF2026-0901 while our
  86  | // own REF2026-0999 sat untouched at Consolidate Responses). So the REF is persisted to disk and
  87  | // re-read on demand, and there is NO generic-name fallback unless it is explicitly opted into.
  88  | const CHAIN_REF_FILE = path.join(__dirname, '..', '..', 'test-results', 'chain-ref.json');
  89  | function persistChainRef(ref: string) {
  90  |   try {
  91  |     fs.mkdirSync(path.dirname(CHAIN_REF_FILE), { recursive: true });
  92  |     fs.writeFileSync(CHAIN_REF_FILE, JSON.stringify({ ref, tender: RUN_TENDER, pid: process.pid }));
  93  |   } catch { /* a non-writable path must never fail the run — tenderMatch() then throws instead */ }
  94  | }
  95  | function readChainRef(): string {
  96  |   try { return JSON.parse(fs.readFileSync(CHAIN_REF_FILE, 'utf8')).ref || ''; } catch { return ''; }
  97  | }
  98  | // Pin every downstream stage to the exact tender TC-01 created (or the one seeded via RUN_REF): inbox
  99  | // rows carry the Ref No and the REF is unique, so filtering rows by it can't drift onto a leftover.
  100 | // Order: in-memory REF → env RUN_REF → the REF persisted by TC-01 (survives worker restarts).
  101 | // If none is known the chain is NOT pinned, so throw rather than silently matching any tender —
  102 | // set ALLOW_ANY_TENDER=1 to opt into the old generic-name behaviour for exploratory single-TC runs.
  103 | function tenderMatch(): string {
  104 |   const ref = RUN_REF || readChainRef();
  105 |   if (ref) { RUN_REF = ref; return ref; }
  106 |   if (RUN_TENDER) return RUN_TENDER;
  107 |   if (process.env.ALLOW_ANY_TENDER === '1') return 'TC-01 Automated Draft Tender';
  108 |   throw new Error(
  109 |     'chain tender is UNKNOWN — refusing to target an arbitrary leftover tender. Either run TC-01 in '
  110 |     + 'the same invocation, pass RUN_REF=<REF2026-nnnn> to pin an existing tender, or set '
  111 |     + 'ALLOW_ANY_TENDER=1 to accept any "TC-01 Automated Draft Tender" at this stage.',
  112 |   );
  113 | }
  114 | // Evaluation Criteria split (price/functionality weighting). Default 90/10; override per run with the
  115 | // EVAL_CRITERIA env var (e.g. EVAL_CRITERIA=80/20). Drives the TC-01 radio + the TC-02/04 read-only checks.
  116 | const EVAL_CRITERIA = process.env.EVAL_CRITERIA || '90/10';
  117 | 
  118 | // Tender dates MUST be computed relative to today, never hardcoded. The AntD pickers render past day
  119 | // cells as `.ant-picker-cell-disabled`, and a disabled cell silently refuses the click — the run then
  120 | // dies on a 15 s click timeout rather than a clear assertion. That is exactly how this spec broke on
  121 | // 2026-07-29: it still asked for 2026-07-01, which had drifted into the past since the 2026-06-08 run.
  122 | // Offsets preserve the business ordering the app enforces: briefing < publication < closing.
  123 | function futureDay(offsetDays: number): string {
  124 |   const d = new Date();
  125 |   d.setDate(d.getDate() + offsetDays);
  126 |   const p = (n: number) => String(n).padStart(2, '0');
  127 |   return `${d.getFullYear()}-${p(d.getMonth() + 1)}-${p(d.getDate())}`;
  128 | }
  129 | const BRIEFING_DATE = futureDay(3);      // Briefing Session Start Time
  130 | const PUBLICATION_DATE = futureDay(4);   // Bid publication Date — after the briefing
  131 | const CLOSING_DATE = futureDay(30);      // Bid closing Date — well after publication
  132 | const BEC_MEETING_DATE = futureDay(5);   // TC-07 Invite BEC Members → Meeting date and time
  133 | 
  134 | // Recorded live: the header has a view-mode selector (tooltip "Click to change view mode")
  135 | // that toggles Live / Ready / Latest. The Draft-Tender form only renders its latest fields
  136 | // in "Latest" mode, so switch to it after login. Guarded — no-op if the control is absent.
  137 | async function switchToLatest(page: Page) {
  138 |   const selector = page.getByTitle('Click to change view mode');
  139 |   await selector.waitFor({ state: 'visible', timeout: 20000 });
  140 |   if ((await selector.innerText().catch(() => '')).includes('Latest')) return;
  141 |   // The dropdown occasionally drops the menu click, so retry open+select until it sticks.
  142 |   await expect(async () => {
  143 |     await selector.click();
  144 |     await page.getByRole('menuitem', { name: /^Latest/ }).click({ timeout: 5000 });
  145 |     await expect(selector).toContainText('Latest', { timeout: 5000 });
  146 |   }).toPass({ timeout: 30000 });
  147 |   // Switching view mode reloads configurable components (incl. the side menu); let it settle.
  148 |   await page.waitForLoadState('networkidle');
  149 | }
  150 | 
  151 | // Recorded live: the "(press to upload)" buttons open a native file chooser. Driving the
  152 | // chooser is more reliable than setInputFiles on the hidden AntD input (which intermittently
  153 | // fails to register the file). Then wait for the upload to surface before continuing.
  154 | async function uploadFile(page: Page, trigger: Locator, file: string) {
  155 |   const chooserPromise = page.waitForEvent('filechooser');
  156 |   await trigger.click();
  157 |   (await chooserPromise).setFiles(file);
  158 | }
  159 | 
  160 | // Recorded live: Ant DatePicker with showTime. .fill() does NOT commit to React state
  161 | // (a later re-render wipes it), so drive the panel: navigate to the month, click the day
  162 | // cell (td[title="YYYY-MM-DD"]), click the hour, then the enabled OK button.
  163 | async function pickAntDateTime(page: Page, field: Locator, dateTitle: string, hour: string) {
  164 |   await field.click();
  165 |   const dropdown = page.locator('.ant-picker-dropdown:not(.ant-picker-dropdown-hidden)').last();
  166 |   const cell = dropdown.locator(`td[title="${dateTitle}"]`);
  167 |   for (let i = 0; i < 24 && !(await cell.isVisible().catch(() => false)); i++) {
  168 |     await dropdown.locator('.ant-picker-header-next-btn').first().click();
  169 |   }
> 170 |   await cell.click();
      |              ^ Error: locator.click: Test timeout of 180000ms exceeded.
  171 |   await dropdown.locator('.ant-picker-time-panel-column').first()
  172 |     .locator('.ant-picker-time-panel-cell-inner')
  173 |     .filter({ hasText: new RegExp(`^${hour}$`) }).first().click();
  174 |   await page.locator('.ant-picker-dropdown:not(.ant-picker-dropdown-hidden) .ant-picker-ok button').click();
  175 | }
  176 | 
  177 | // Recorded live (Playwright MCP): Ant-Design form. Each field is its own .ant-form-item with a
  178 | // single input and no nesting; labels render as "<Label>*" (asterisk glued on), so match by
  179 | // substring on the form-item text and take the lone input inside it.
  180 | function formItem(page: Page, label: string) {
  181 |   return page.locator('.ant-form-item').filter({ hasText: label });
  182 | }
  183 | 
  184 | // Recorded: login fields expose only placeholders (no accessible name); button is "Sign In".
  185 | // The chain logs in ~16 times (once per TC) and on the slow QA app the login SPA sometimes has not
  186 | // hydrated when goto() resolves — TC-06 died on 2026-07-29 with `locator.fill` timing out on
  187 | // getByPlaceholder('Username') after 15 s. So wait explicitly for the field, and retry the whole
  188 | // navigation once before giving up rather than failing the TC (and cascading the rest of the chain).
  189 | async function loginAs(page: Page, creds: { user: string; password: string }) {
  190 |   const username = page.getByPlaceholder('Username');
  191 |   await expect(async () => {
  192 |     await page.goto(APP_URL, { waitUntil: 'domcontentloaded' });
  193 |     await expect(username).toBeVisible({ timeout: 20000 });
  194 |   }).toPass({ timeout: 70000 });
  195 |   await username.fill(creds.user);
  196 |   await page.getByPlaceholder('Password').fill(creds.password);
  197 |   await page.getByRole('button', { name: 'Sign In' }).click();
  198 |   await page.waitForURL(url => !url.href.includes('/login'), { timeout: 30000 });
  199 |   await page.waitForLoadState('networkidle');
  200 |   await switchToLatest(page);
  201 | }
  202 | async function loginAsAdmin(page: Page) {
  203 |   await loginAs(page, ADMIN);
  204 | }
  205 | 
  206 | // Recorded: Ant-Design accordion menu. Workflows expands to Inbox/My Items/Sent Items/Draft.
  207 | // The submenu animates open, so the Inbox click can hit an unstable / intercepted target —
  208 | // retry it (re-opening Workflows if the submenu collapsed) until the inbox actually loads.
  209 | // Same resilience as openInbox, for the "My Items" branch of the sidebar. TC-01 originally did a plain
  210 | // `myItems.click()`, which intermittently died on Playwright's stability check — the flyout is still
  211 | // animating, so the log reads "element is not stable" and then "element is not visible" once it
  212 | // collapses again (observed 2026-07-29: 30 retries over 15 s, TC-01 failed and the whole chain
  213 | // cascaded). Retry open+click until the URL actually changes.
  214 | async function openMyItems(page: Page) {
  215 |   const workflows = page.getByRole('menuitem', { name: 'Workflows' });
  216 |   const myItems = page.getByRole('menuitem', { name: 'My Items' });
  217 |   await workflows.click();
  218 |   await expect(async () => {
  219 |     if (!(await myItems.isVisible().catch(() => false))) {
  220 |       await workflows.click({ timeout: 5000 });
  221 |     }
  222 |     await myItems.click({ timeout: 5000 });
  223 |     await page.waitForURL(/workflows-my-items/, { timeout: 8000 });
  224 |   }).toPass({ timeout: 40000 });
  225 |   await page.waitForLoadState('networkidle');
  226 | }
  227 | 
  228 | async function openInbox(page: Page) {
  229 |   const workflows = page.getByRole('menuitem', { name: 'Workflows' });
  230 |   const inbox = page.getByRole('menuitem', { name: 'Inbox' });
  231 |   await workflows.click();
  232 |   await expect(async () => {
  233 |     if (!(await inbox.isVisible().catch(() => false))) {
  234 |       await workflows.click({ timeout: 5000 });
  235 |     }
  236 |     await inbox.click({ timeout: 5000 });
  237 |     await page.waitForURL(/workflows-inbox/, { timeout: 8000 });
  238 |   }).toPass({ timeout: 40000 });
  239 |   await page.waitForLoadState('networkidle');
  240 | }
  241 | 
  242 | // Recorded: Bid Management expands to Dashboard/Evaluate Tenders/Calibrate Scores/TenderType Documents/Suppliers.
  243 | async function openEvaluateTenders(page: Page) {
  244 |   await page.getByRole('menuitem', { name: 'Bid Management' }).click();
  245 |   await page.getByRole('menuitem', { name: 'Evaluate Tenders' }).click();
  246 |   await page.waitForLoadState('networkidle');
  247 | }
  248 | 
  249 | // Reusable assertion: the opened item lands on the expected workflow page.
  250 | // The QA app's dynamic (configurable) pages load slowly and variably, so allow 30s.
  251 | // Also runs the Send-Back probe (opt-in) — every stage TC calls this right after its item opens, so
  252 | // instrumenting here maps the whole workflow in a single chain run.
  253 | async function expectOnPage(page: Page, pageName: string) {
  254 |   await expect(page.getByText(pageName, { exact: false }).first()).toBeVisible({ timeout: 30000 });
  255 |   if (process.env.PROBE_SENDBACK === '1') await probeSendBack(page, pageName);
  256 | }
  257 | 
  258 | // ===========================================================================================
  259 | // SEND-BACK (negative) branches, opt-in via SEND_BACKS=all or SEND_BACKS=<n,n,…> (stage numbers).
  260 | //
  261 | // Mapped live 2026-07-30 (PROBE_SENDBACK=1): every stage after the draft offers **Send Back**, and the
  262 | // Step picker lists EVERY completed predecessor — Review&Approve offers 1 target, Publish 2, Consolidate
  263 | // 3, Verify Compliance 4, Calculate SGP 5, Invite BEC 6, and so on.
  264 | //
  265 | // Each instrumented stage does: **send back to the immediately preceding step** (cheapest, most realistic
  266 | // rework) → the previous actor **re-actions** that step → the tender returns here → the normal happy
  267 | // action runs and the chain CONTINUES to Capture Order Details. So one run exercises both paths.
  268 | //
  269 | // Recovery is simpler than the first pass because the captured data persists: for most stages it is
  270 | // "tick the confirmation again and Submit". The stages needing more (the draft wizard, Approve, Publish)
```