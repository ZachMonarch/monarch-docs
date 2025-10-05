# Monarch Documentation System
Mintlify-powered documentation portal for Monarch Property Management Group.

## Quick Start
1. Create a GitHub repo named `monarch-docs`.
2. Upload *all files* from this folder into that repo.
3. In GitHub: Settings → Secrets → Actions → **New repository secret**:
   - `MINTLIFY_API_KEY` = your key from Mintlify dashboard
   - `MONARCH_DOCS_PASS` = a strong password for internal pages
4. In Mintlify dashboard:
   - New Project → Import from GitHub → select `monarch-docs`.
   - Set Custom Domain: `docs.monarchpropertymmgt.com` (optional now; add DNS CNAME to `cname.mintlify.dev` when ready).
5. Push changes to `main` → auto-deploy runs.

## Edit Content
- Homepage: `docs/index.mdx`
- About: `docs/about-monarch.mdx`
- Vendor Guides: `docs/user-guides/*`
- Admin Guides: `docs/admin-guides/*`
- Legal: `docs/legal-library/*`

## Branding
- Colors are set in `styles/monarch.css`
- Logo in `assets/monarch-logo.png`

© 2025 Monarch Property Management Group
