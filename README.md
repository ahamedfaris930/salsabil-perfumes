A single-page site for Salsabil Perfumes (index.html), ready to host on GitHub Pages.
Put it on GitHub
Create a new repository on GitHub, e.g. salsabil-perfumes.
Upload index.html to the root of the repo (drag-and-drop on the GitHub web UI works, or git add / commit / push).
Go to Settings → Pages in the repo.
Under Build and deployment, set Source to "Deploy from a branch," branch main, folder / (root).
Save. Your site will be live in a minute or two at:
https://<your-username>.github.io/salsabil-perfumes/
What's in the page
Hero, brand story, three product collections (Al-Oud, Ward, Dukhan) with real scent notes, a craftsmanship section, four bestseller cards, testimonials, and a contact section.
All content is real draft copy, not lorem ipsum — swap in your actual prices, contact details, and social links (search hello@salsabilperfumes.com, +971 00 000 0000, and the # placeholders in the footer's Follow section).
The contact form doesn't submit anywhere yet — it's front-end only. To make it work you'd need a form backend (e.g. Formspree, Netlify Forms) or your own server.
No build step, no dependencies beyond Google Fonts — it's one self-contained HTML file.
Customizing
Colors and fonts are set as CSS variables at the top of the <style> block in index.html — change --ink, --gold, --ivory, etc. to retheme the whole site.
Product images: currently the bottle cards use a plain gradient placeholder (.glass). Replace with <img src="..."> once you have real product photography.
