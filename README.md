Faruukh Nadeem — Official Portfolio
Static multi-page portfolio website for Faruukh Nadeem, educational leader, institution builder, and school-management professional.
Live website
https://faruukhnadeem.com
Hosting and deployment
Hosting: Netlify
Production branch: `main`
Build command: none
Publish directory: `.`
Deployment: automatic after every push to `main`
Main pages
`/` — Home
`/about/`
`/educational-leadership/`
`/institution-building/`
`/experience-achievements/`
`/training-social-impact/`
`/international-experience/`
`/gallery/`
`/insights/`
`/travel-media/`
`/contact/`
Important files
`sitemap.xml` — public URLs submitted to Google and Bing
`robots.txt` — crawler instructions
`netlify.toml` — Netlify configuration and redirects
`_redirects` — route rules
`form-definitions.html` — Netlify form detection blueprint
`404.html` — custom error page
Update checklist
When adding a public page:
Create the page folder and `index.html`.
Add internal navigation links where relevant.
Add the URL to `sitemap.xml`.
Add a unique title, meta description, canonical URL, Open Graph metadata, and structured data.
Commit the change and push to `main`.
Confirm the Netlify deployment succeeds.
Notify Google/Bing only when the page is new or meaningfully updated.
When removing or renaming a public page:
Add a permanent `301` redirect in `_redirects` or `netlify.toml`.
Remove the old URL from `sitemap.xml` and navigation.
Check for internal links pointing to the old URL.
Contact forms
The website contains two Netlify Forms:
`homepage-contact`
`portfolio-contact`
Both redirect to `/thank-you/` after successful submission.
Security
Do not commit passwords, API keys, private documents, identity records, or other confidential data to this repository.

Media and Press update - 17 July 2026
Added `/media/` with approved biographies, downloadable media kit, professional headshots, brand assets, expertise topics, verified career facts and press contact information. Updated the sitemap and site-wide footer links.

Cornerstone article added — 2026-07-17
URL: /insights/building-educational-institution-underserved-rural-community/
Title: Building an Educational Institution in an Underserved Rural Community: Lessons from Dhudray Sharqi
Article schema and breadcrumb schema included
Insights page, homepage and sitemap updated
