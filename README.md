# Yash Raju Jungare — Resume

A static, responsive resume website built with HTML and CSS. Resume text is present in the initial HTML document, so the page remains readable without JavaScript. The source PDF is not included in this website because it contains private contact information.

## Preview locally

Open `index.html` in a browser, or use a local static server such as the Live Server extension in Visual Studio Code. No build step or package installation is required.

To verify the crawler-readable source, open the page and choose **View Page Source** (or press **Ctrl+U**). The resume headings and content should appear in the HTML.

## Deploy to Vercel

1. Push this repository to GitHub if it is not already there.
2. Sign in to Vercel, select **Add New → Project**, and import this GitHub repository.
3. In project configuration, select **Other** as the Framework Preset and keep the Root Directory as `./`.
4. Leave the Build Command empty. Set the Output Directory to `.` (the repository root); there is no build step.
5. Select **Deploy**. The site is static and does not require a backend or paid APIs. Vercel's Hobby plan is subject to Vercel's current eligibility and usage terms.
6. After deployment, add the actual deployed URL as the page's canonical link in `index.html`, add that same URL as a `<loc>` entry in `sitemap.xml`, and add the full sitemap URL to `robots.txt`. Do not use a placeholder URL.

## Content

The resume content was transcribed from the supplied PDF. Phone number and residential address are omitted. Projects, certifications, and achievements are not included because the supplied resume does not provide details for those sections.
