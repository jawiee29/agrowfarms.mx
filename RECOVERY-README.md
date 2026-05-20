Agrow Farms Netlify Current Deploy Recovery

Source:
- Netlify site: agrowfarms-mx
- Site ID: bd5f024c-ef88-4679-81de-9fad0cef2196
- Deploy ID: 6a07b074c8008efdd4ffa044
- Published: 2026-05-15 17:47 local time
- Domain: https://agrowfarms.mx

Status:
- Netlify reports the deploy is ready.
- The domain currently returns a 503 usage_exceeded response because the Netlify team has exceeded the credit limit and projects are paused.
- The files in this folder are the current domain-linked deploy package recovered from Netlify's deploy file browser.

Photo fix:
- The deployed index.html references assets/photos/aerial-greenhouse-footprint.webp.
- Netlify's deploy file search did not contain that file, which can cause a missing image icon.
- To make the recovered package render cleanly, assets/photos/original-greenhouse-aerial.webp was copied to assets/photos/aerial-greenhouse-footprint.webp as a compatibility asset.

Deploying:
- Upload this whole folder, not only index.html.
- Keep the assets/photos folder beside index.html exactly as shown here.
