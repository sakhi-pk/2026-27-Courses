# UDW app — upload as the `udw/` folder in repo sakhi-pk/2026-27-Courses

IMPORTANT: do NOT put this index.html in the repo root — the root index.html is your live SAK Coaching course page (it has its own #udw section). This app goes in a folder:

    2026-27-Courses/
      index.html          <- existing course page (leave untouched)
      udw/
        index.html        <- this app
        data/ledger.json  <- referral ledger (you update via Studio)
        data/picks.json   <- Earn picks / new tokens (you update via Studio)

Live addresses once uploaded (GitHub → Add file → Upload files, drag the whole `udw` folder → Commit):
- App:     https://sakhi-pk.github.io/2026-27-Courses/udw/
- Studio:  https://sakhi-pk.github.io/2026-27-Courses/udw/#studio   (also #udw)
- Referral links look like: https://sakhi-pk.github.io/2026-27-Courses/udw/#invite?ref=CODE

Daily routine
1. Join request arrives on WhatsApp (name, Binance Pay Order ID, referral code). Verify the USDT in Binance Pay, add them to the community.
2. Studio → Referral ledger: add/update the record (pending → approved after you verify → paid after you send the bonus).
3. Studio → Export → download ledger.json / picks.json → upload into udw/data/ on GitHub → Commit (live in ~1 minute).
4. Weekly: Studio → Earn picks: add hot Earn products with the CURRENT APR from Binance Earn, and new tokens you recommend.

Notes
- Price is automatic: 26 USDT in 2026, 27 in 2027, 28 in 2028 ... The 2.6% bonus follows the price.
- The 24h high-volume alts table is live from Binance public data; everything else is what you publish.
- Studio is not password protected (it only produces files; nothing changes until you upload them). Never put payout IDs or full names in the public ledger.
