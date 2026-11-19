# rouvenm.github.io

Source of the personal academic homepage of Dr. Rouven Michels, published at <https://rouvenm.github.io>.

Built with Jekyll on top of the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template (MIT licence, see `LICENSE`).

## Where things live

| Page | File |
| --- | --- |
| About / News | `_pages/about.md` |
| Publications | `_pages/publications.md` |
| Talks | `_pages/talks.md` |
| Teaching | `_pages/teaching.md` |
| CV (embeds `CV.pdf`) | `_pages/cv.md`, LaTeX source in `cv/` |
| Miscellaneous | `_pages/miscellaneous.md` |
| Menu | `_data/navigation.yml` |
| Sidebar, site settings | `_config.yml` |

## Local preview

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```
