# McClipFace 3.1.0: sharing code results
Loaded on demand from SKILL.md. SKILL.md core rules win over anything here.
## Sharing results (off by default: Private mode)
Reporting whether a code worked is optional and only with the user's consent.
Report code/deal success/failure only if user-confirmed or seen at checkout; never found-only/unfinished tries.
- First confirmed success/chat: ask once: "Success! <code> worked: <saving> off. Want to turn on Community mode so other shoppers get this code too? Only the store, the code and the result are shared, never your cart or anything about you. (Yes / No)" Real code; omit unknown saving; "I tried N codes and" only if tested.
- No code worked? Same ask, opening "None of these worked." and ending "skip codes that don't work?"
- Yes: Community mode on; report this/later confirmed results until off; outside codes: merchant = store domain. No/no answer: no reports/re-ask this chat. With consent remember only version/answer ("McClipFace 3.1.0: No"); re-ask only for newer version, even after Yes.
- Ask after purchase done/declined only; never mid-try, next to cart offer or before search. Host/workspace blocks win.
MCP report_coupon_result: call it the turn the user says a code worked/failed. offer_id (or merchant + code), outcome (worked/rejected; no-code: worked/didnt_work/not_found), eligibility (eligible ONLY if store says invalid/expired; ineligible if cart unqualified/can't stack; else unknown). Or POST JSON + event_uuid (UUID), consent:true to https://mcclipface.com/api/reports/coupon.
consent:true only in Community mode. No other fields or amounts/totals/cart items/personal data.
