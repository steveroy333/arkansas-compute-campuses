# Custom domain (ready, not activated)

When Steve approves connecting campuses.greyswancapital.ai:

1. In GoDaddy DNS for greyswancapital.ai, add:
   - Type: CNAME
   - Name/Host: campuses
   - Value/Points to: steveroy333.github.io
   - TTL: 1 hour (or default)

2. In this repo, add a file named `CNAME` (no extension) containing exactly:
   campuses.greyswancapital.ai

3. In GitHub Pages settings, set Custom domain to campuses.greyswancapital.ai and enable Enforce HTTPS.

Do NOT add the CNAME file until DNS is ready — adding it early can break the temporary github.io URL.
