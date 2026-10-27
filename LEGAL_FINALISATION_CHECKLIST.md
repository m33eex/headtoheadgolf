# HeadToHeadGolf — Legal and App Store Launch Checklist

**Status:** Website copy refreshed for the submitted HeadToHeadGolf 1.0 (build 6). Operational and legal verification items below remain to be confirmed; this is not a legal sign-off.

- [ ] Confirm operator's full legal name and postal contact address and whether any company exists.
- [ ] Confirm minimum user age, children policy and applicable parental-consent approach.
- [ ] Verify production Supabase data, storage, hosting region, processors, analytics and crash SDKs.
- [ ] Verify account deletion end-to-end, including timing, backups and historical records.
- [ ] Choose public permanent URLs for Privacy Policy, Terms, Subscription Terms and deletion information.
- [ ] Verify Apple App Store subscription product, UK and international price displays, grace period, restore behaviour and cancellation text.
- [x] Verify Sandbox purchase, server entitlement, Solo round beyond free allowance, and Restore Purchases on a physical iPhone.
- [ ] Verify expiry, renewal and revocation handling (not yet end-to-end tested).
- [x] Solo free-round enforcement is enabled in the LIVE project and Sandbox purchase-to-access has been tested.
- [ ] Verify separate competition-event expiry enforcement before enabling it.
- [ ] Confirm App Store Connect app privacy disclosures, age rating, export compliance and regions.
- [ ] Review privacy requirements for relevant launch regions (UK GDPR, EU GDPR, California and other applicable jurisdictions), including transfers and data-subject rights.
- [ ] Obtain qualified legal review for worldwide launch; local mandatory rights override generic terms.
- [ ] Add links in-app and to App Store Connect; verify links work without login.

## Website-specific launch checks
- [ ] Obtain qualified legal review of the updated public policies and confirm all factual disclosures.
- [ ] Set effective/publication dates and confirm the individual operator identity and required address details.
- [ ] Decide whether to show full contact address on the website or provide an appropriate compliant alternative.
- [ ] Check privacy rights/contact disclosures and international transfer disclosures for regions served.
- [ ] Verify account deletion against deployed Edge Function and database behaviour, not just intended design.
- [ ] Replace CSS logo placeholder with approved logo assets.
- [ ] Once App Store listing is live, add the official App Store badge and download link.
- [ ] Confirm all public links resolve without authentication and HTTPS works.
