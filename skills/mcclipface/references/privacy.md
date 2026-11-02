# McClipFace 3.1.1: what McClipFace receives
Loaded on demand from SKILL.md. SKILL.md core rules win over anything here.
## What McClipFace receives
- Lookup sends only store name/domain or short product name, currency, version, install ID; deep link adds product-page address.
- client_install_id: random UUID v4 at install, never user-derived; keep on updates, else omit if not retainable. Lookups keep only a monthly-salted hash to count installs, never linked to codes/reports; wish-list checks: counts/30-day hash markers only, testable by server keys till salt deletion.
- No carts/prices/totals/order/payment details/browsing history sent; no account needed, no identity sent.
- IP: one-way keyed hash for rate limits/counts, never with lookups. https://mcclipface.com/privacy.html
