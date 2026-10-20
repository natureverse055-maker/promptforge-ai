# PromptForge AI — Professional SEO Starter

## Files included
- `index.html` — working browser-based prompt generator
- `about.html` — About page
- `privacy.html` — privacy policy starter template
- `terms.html` — terms of use starter template
- `contact.html` — contact page template
- `guides/ai-video-prompt-guide.html` — original SEO-friendly tutorial
- `assets/site.css` — shared navigation styles
- `assets/favicon.svg` — site icon
- `robots.txt` and `sitemap.xml` — search crawler setup templates

## Test locally
Extract the ZIP and open `index.html` in your browser. Click the generator, copy, download, and sample buttons. Open each extra HTML page from the file explorer to test its links.

## Free deployment with Cloudflare Pages
1. Create a GitHub repository and upload all files/folders, preserving their paths.
2. In Cloudflare Dashboard, open Workers & Pages and create a Pages project connected to the Git repository.
3. Choose no framework for this plain static HTML project.
4. If the setup requires a build command, use `exit 0`; set the output directory to the repository root (usually `/` or `.` as the UI accepts).
5. Deploy and test every page at the generated `*.pages.dev` URL.
6. Replace `YOUR-SITE.pages.dev` in `robots.txt` and `sitemap.xml` with your actual hostname, then commit and redeploy.
7. Submit `https://YOUR-SITE.pages.dev/sitemap.xml` in Google Search Console after replacing the placeholder hostname.

## Before launch
- In `contact.html`, replace `your-email@example.com` with a contact address you control.
- Review the Privacy Policy and Terms. They are templates, not legal advice. Update privacy details if you add analytics, ads, accounts, payments, or AI API calls.
- Add a custom domain only if/when your budget allows. The free Pages subdomain is enough for initial testing.
- Do not add placeholder ad scripts. Apply to AdSense only after the site has useful original content and is ready for review.
- Never click your own ads or encourage users to click ads.
- This project currently creates prompts with local JavaScript rules; it is not connected to an AI model or database.

## SEO checklist
- Each page has a unique title and meta description.
- Use one clear H1 per page and descriptive internal links.
- Keep the tutorial useful and original; don't publish many thin, repetitive pages just to target keywords.
- After launch, verify the site in Google Search Console and monitor indexing. SEO does not guarantee rankings or traffic.
