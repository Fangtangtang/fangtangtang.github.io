# Shihan Fang - Personal Academic Page

A personal academic website built with Jekyll and Bootstrap 4, hosted on GitHub Pages. Based on the [academic-jekyll](https://github.com/vsimkus/academic-jekyll) template.

## Project Structure

```
.
├── index.html                 # Home page (bio, publications, awards)
├── blog.html                  # Blog listing page
├── gallery.html               # Art gallery page with carousel
├── _config.yml                # Jekyll site configuration
├── style.scss                 # Main stylesheet
├── publication_effects.js     # JS for publication bib copy & hover effects
├── favicon.ico                # Site favicon
├── CNAME                      # Custom domain config (GitHub Pages)
│
├── _layouts/
│   ├── default.html           # Base layout (nav + footer + scripts)
│   └── post.html              # Blog post layout
│
├── _includes/
│   ├── navigation.html        # Top navbar
│   ├── footer.html            # Page footer
│   ├── publications.html      # Publications section template
│   └── award.html             # Awards & honors section template
│
├── _data/
│   ├── navigation.yml         # Navigation menu items
│   └── gallery.yml            # Gallery artwork entries
│
├── _sass/
│   ├── _reset.scss            # CSS reset
│   └── _variables.scss        # Sass variables (colors, fonts, sizes)
│
├── publications/_posts/       # Publication entries (markdown + front matter)
├── award/_posts/              # Award entries (markdown + front matter)
├── blog/_posts/               # Blog posts (markdown)
│
├── images/                    # Site images (bio photo, etc.)
├── gallery/                   # Gallery artwork images
└── uploads/                   # Uploaded files (posters, slides)
```
