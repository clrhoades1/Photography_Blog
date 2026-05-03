# Photography Blog Personalization To-Do List

Based on an exploration of the Bookworm Light Astro theme, this is a prioritized list of tasks to make the website "your own." Tasks are grouped by category, starting with high-priority items (branding and content) and ending with optional refinements. Each item includes why it's important and approximate effort level.

## 1. Site Branding and Configuration (High Priority - Do First)
- ~~**Update site title, description, and metadata in `src/config/config.json`**: Change "Bookworm Light Astro | Blog Template" to something like "[Your Name]'s Photography Blog", update the base URL to your domain (e.g., "https://yourphotoblog.com"), and replace placeholder meta descriptions, author name ("Themefisher"), and contact info (address, email, phone). This affects SEO, social sharing, and the site's identity. *Effort: Low (5-10 mins)*~~
- ~~**Replace logo and favicon**: Upload your own logo to `public/images/logo.png` (match the dimensions in config.json: 200x34px) and favicon to `public/images/favicon.png`. Update the logo text in config.json if needed. *Effort: Low (10-15 mins)*~~
- ~~**Customize theme colors and fonts in `src/config/theme.json`**: Adjust primary colors (e.g., to photography-themed tones like blues/greens), text colors, and fonts to match your style. The current font is "Mulish"—consider photography-friendly alternatives like "Playfair Display" for headings. *Effort: Low (10-15 mins)*~~
- ~~**Update package.json name and version**: Change "name" from "bookworm-light-astro" to something like "my-photography-blog" and bump the version to "1.0.0". *Effort: Low (2 mins)*~~

## 2. Content Replacement (High Priority - Core to Personalization)
- **Replace sample blog posts**: Delete or overwrite the 7 sample posts in `src/content/posts/` (e.g., post-1.md to post-7.md) with your own photography-related content. Each post has lorem ipsum text, generic titles (e.g., "How to make toys from old Olarpaper"), and placeholder images. Write original articles, add real photos, and update frontmatter (title, description, date, categories, tags, authors). Aim for photography niches like techniques, gear reviews, or photo stories. *Effort: High (1-2 hours per post, depending on writing)*
- **Update author profiles**: Replace "John Doe" and "Mark Dinn" in `src/content/authors/` with your details (or real co-authors). Update bios, social links, and profile images in `public/images/authors/`. If you're the only author, remove extras and update references in posts. *Effort: Medium (20-30 mins)*
- **Personalize the About page (`src/content/about/-index.md`)**: Rewrite the content from lorem ipsum to your bio, focusing on your photography background, style, and what readers can expect. Update the "What I Do" section to reflect photography services/skills (e.g., portrait photography, landscape shoots). *Effort: Medium (20-30 mins)*
- **Customize the Contact page (`src/content/contact/-index.md`)**: Add real contact details, a contact form integration (update the form action in config.json), and any photography-specific inquiries (e.g., booking shoots). *Effort: Low (10-15 mins)*
- **Update or remove sample pages**: Review `src/content/pages/` (e.g., elements.mdx, privacy-policy.md) and replace with your own content or delete if not needed. *Effort: Low (10-15 mins)*

## 3. Images and Media (Medium Priority - Visual Identity)
- **Replace placeholder images**: Swap out `public/images/author.JPG`, `public/images/image-placeholder.png`, and `public/images/logo.png` with your own. For posts, replace images in `public/images/posts/` with high-quality photos. Ensure images are optimized for web (use tools like ImageOptim or Astro's Sharp integration). *Effort: Medium (30-60 mins, plus photo editing)*
- **Add author photos**: Upload real headshots to `public/images/authors/` and update the author Markdown files to reference them. *Effort: Low (10 mins)*
- **Generate OG images**: Update `public/images/og-image.png` with a custom open-graph image for social sharing (e.g., your blog's logo or a signature photo). *Effort: Low (10-15 mins)*

## 4. Social and Navigation (Medium Priority - User Engagement)
- **Update social links in `src/config/social.json`**: Replace placeholder URLs (e.g., Facebook, Instagram) with your real social media profiles. Add/remove platforms as needed (e.g., keep Instagram for photography). *Effort: Low (5 mins)*
- **Customize the menu in `src/config/menu.json`**: Adjust navigation items if needed (e.g., add a "Portfolio" page or remove "Elements" if not using it). Ensure it fits a photography blog. *Effort: Low (5-10 mins)*

## 5. Deployment and Technical Setup (Medium Priority - Getting Live)
- **Update deployment configs**: If using Netlify, edit `netlify.toml` with your site settings. For Cloudflare Workers, update `wrangler.jsonc` with your account details. Change the base URL in `astro.config.mjs` (it pulls from config.json). *Effort: Low (10-15 mins)*
- **Set up Google Tag Manager**: Replace "GTM-XXXXXX" in `src/config/config.json` with your real GTM ID for analytics/tracking. *Effort: Low (5 mins)*
- **Test and build**: Run `yarn build` to ensure everything compiles. Fix any errors (e.g., broken image paths). *Effort: Low (10 mins)*

## 6. SEO and Performance Optimization (Low Priority - Polish)
- **Add structured data**: Consider adding JSON-LD schema for photography/blog posts in layouts (e.g., in `Base.astro`) to improve search visibility. *Effort: Medium (20-30 mins)*
- **Optimize for photography**: Ensure images are lazy-loaded and compressed. Add alt text to all images for accessibility. *Effort: Low (ongoing)*
- **Review and update copyright**: Change the copyright notice in `src/config/config.json` to your name/year. *Effort: Low (2 mins)*

## 7. Optional Enhancements (Low Priority - If Time Allows)
- **Add photography-specific features**: Integrate a lightbox/gallery component for post images, or add categories/tags tailored to photography (e.g., "Portraits", "Landscapes").
- **Customize components**: Tweak layouts like `Header.astro` or `Footer.astro` for a more photography-focused design (e.g., add a photo banner).
- **Enable drafts and pagination**: Use the draft feature in posts for unpublished work, and adjust pagination in config.json.
- **Add a portfolio page**: Create a new page under `src/pages/` for showcasing your best photos.

Start with categories 1-2 to establish your brand and content foundation. Test locally with `yarn dev` after each major change. If you need help with any specific task (e.g., writing content or image optimization), refer back to this list or ask for assistance.</content>
<parameter name="filePath">/Users/connorrhoades/Desktop/GitHub_Repositories/photography_blog/todo.md