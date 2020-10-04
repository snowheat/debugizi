# debugizi
Headless CMS for static site generator with continuous delivery

## Features
- Option for auto publish static site pages to remote repository
- Built-in SEO configuration
- Sitemap generator
- Lightweight JSON search engine

## Roadmap Oct - Dec 2020
1. - [ ] Using **POST** to **/posts**, publish a new content as a static site page to remote Git repository (path, title, content)
2. - [ ] Using **PUT** to **/posts/:post_id**, modify a static site page content on remote Git repository
3. - [ ] Using **DELETE** to **/posts/:post_id**, delete a static site page content on remote Git repository
4. - [ ] Using **POST** to **/templates**, publish a new Handlebars HTML template for specific path / page
5. - [ ] Using **PUT** to **/templates/:template_id**, modify a Handlebars HTML template for specific path / page
6. - [ ] Using **DELETE** to **/templates/:template_id**, delete a Handlebars HTML template for specific path / page
7. - [ ] Using **GET** to **/posts**, search contents by title
