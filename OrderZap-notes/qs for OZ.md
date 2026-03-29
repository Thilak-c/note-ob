|#|Question|Answer Baked In|
|---|---|---|
|1|Order appears on Chef screen|1-3 sec via Convex reactive|
|2|Mixed category orders|Yes — JSONB items array|
|3|Edit order|Yes — pending status only|
|4|Multiple active orders per table|Yes|
|5|Who changes status|Chef + Waiter + Admin|
|6|Role system|Customer, Waiter, Chef, Admin|
|7|Price history|price_snapshot in JSONB|
|8|Stock quantity|quantity column + decrement on order|
|9|Payment flow|3 options on cart page|
|10|Chef view|All orders, one live feed|
|11|Table system|Dynamic QR code per table|
|12|Order history|Full history with date filter|
|13|Branches|Multi-branch with branch_id everywhere|
|14|Boot sync|Upsert only — safe strategy chosen|
|15|Push notifications|Expo Push — 4 trigger events|
|16|REST rate limiting|100/IP/15min → HTTP 429|
|17|Audit log|Full audit_log table|
|18|pg retry|Auto retry × 3 then fail|
|19|Menu images|image_url column|
|20|Dashboard in prod|nginx Basic Auth protection|