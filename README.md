# Ali Hassan | AI Automation Specialist site

Static site (no build step), deployed on Vercel.

- `index.html`: public landing page. Contact form posts to Supabase `contact_submissions`.
- `admin.html`: private admin panel (Supabase email/password + TOTP 2FA, RLS-protected).
- `vercel.json`: security headers and CSP. `robots.txt` and `sitemap.xml` for SEO.

Backend: Supabase project `ali-portfolio` (migrations already applied).
