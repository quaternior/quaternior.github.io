# Jinhyeok Kim — personal website

https://quaternior.github.io/

Built from [Minimal Light](https://github.com/yaoyao-liu/minimal-light) by Yaoyao Liu, upstream commit `1ea07f39518ac44644406380c83da6f89037c4fc` (CC0-1.0). The original layout, Sass, fonts, and publication styling are retained. Small local adjustments add accessible link names, full publication resource links, uncropped research thumbnails, and mobile fixes.

## Edit content

- `_config.yml`: profile, contact links, theme settings.
- `index.md`: biography, research interests, news, education, experience.
- `_data/publications.yml`: publications and Paper / Project / Model / Code links.
- `assets/portrait.png`: displayed profile photograph, copied unchanged from the owner-provided `증명사진_edited.png`. Replace this file with your next photo.
- `assets/portrait.jpg`: previous original photograph retained as a backup. The current PNG has no additional image edits or custom CSS that shrinks the portrait.
- `assets/css/custom.css`: small overrides; upstream styles remain in `_sass/`.

Push to `main`. GitHub Pages builds Jekyll from the repository root. No custom domain is configured. The footer links to the actual template.

## Local preview

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

## Content sources

Biography and original publications: https://sites.google.com/view/jinhyeokkim/home

Dynin-Robotics metadata and links: user-provided citation, https://sites.google.com/view/hoeunlee/, and https://dynin.ai/robotics/. Code and model destinations currently announce a forthcoming release.

The July 2026 VLDB acceptance news was supplied by the owner. Dynin-Omni authors remain as listed on the owner's original homepage; its arXiv metadata differed when checked during the initial migration.

Research images come from the papers' official arXiv/GitHub materials: SPDP design overview, AIDASLab/Dynin-Robotics `assets/main.png`, and AIDASLab/Dynin-Omni `assets/main.jpg`. The profile photograph and research content belong to their respective owners; the included CC0 license covers the upstream template.
