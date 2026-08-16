g# QA Test Log — Task #15

**Member:** Member 4 (QA/UI)  
**Project:** Northstar QuickHelp  
**Scope:** Return rules and eligibility test cases


| Test ID | Test Description                            | Expected Result                  | Actual Result | Pass/Fail | Notes |
| ------- | ------------------------------------------- | -------------------------------- | ------------- | --------- | ----- |
| TC-01   | Delivered 5 days ago, unused, changed mind  | Eligible                         |               |           |       |
| TC-02   | Delivered 35 days ago, unused, changed mind | Not eligible                     |               |           |       |
| TC-03   | Final sale, changed mind                    | Not eligible                     |               |           |       |
| TC-04   | Final sale, damaged 3 days after delivery   | Exception/priority review        |               |           |       |
| TC-05   | Used/washed item                            | Not auto-approved; escalate      |               |           |       |
| TC-06   | Return initiated, not received              | Refund not due yet               |               |           |       |
| TC-07   | Return received, inspection pending         | Explain inspection window        |               |           |       |
| TC-08   | Card refund issued 2 days ago               | Explain 5–10 business day window |               |           |       |
| TC-09   | Card refund issued 12 business days ago     | Escalate                         |               |           |       |
| TC-10   | Cancelled order, refund issued              | Show confirmation                |               |           |       |
| TC-11   | Order not delivered                         | Return cannot start yet          |               |           |       |
| TC-12   | Order not found                             | Escalate                         |               |           |       |


