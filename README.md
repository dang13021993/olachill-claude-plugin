# OlaChill Travel — Claude Directory Plugin

Publisher: **MIA Co., Ltd. (MIA株式会社), Osaka, Japan**  
Website: https://olachill.com  
Support: partners@olachill.com  
Privacy: https://olachill.com/en/privacy-policy  
Terms: https://olachill.com/en/terms-of-service

This standalone Claude plugin connects to the already established public remote MCP at **https://olachill.com/mcp**. It includes three skills for Japan travel discovery, private transfers and charter quotes, and existing booking-status checks. It does **not** include OlaChill website source code, any tokens or credentials, or any new backend.

## Claude Directory submission

1. Create a new small **public** GitHub repository named `olachill-claude-plugin` under `dang13021993` (do not make the large `olachill-monorepo` public).
2. Unzip this package and upload **the contents of the `olachill-claude-plugin` folder** to the new repository's root. Preserve the hidden `.claude-plugin` directory and `.mcp.json` file.
3. In Claude's plugin submission form, use `https://github.com/dang13021993/olachill-claude-plugin`, branch `main`, and leave the plugin path empty.
4. Click Validate; continue with the listing, data handling, compliance and final review steps when the portal validates.

### Test prompts

- Find a Mt Fuji day tour from Tokyo under ¥15,000.
- Find an airport transfer from Narita to Shinjuku for 4 adults and 4 large bags.
- Estimate a 45-seat bus from Tokyo to Hakone for 2027-03-20; do not submit a request.
- What options does OlaChill offer for helicopter sightseeing over Tokyo?

Prices and dated availability are verified only where the tools provide them. A charter quote request is sent only on the customer's explicit instruction; it is not a booking or payment. An earlier approval of the remote MCP connector is **not** approval of this newly packaged Claude plugin.
