# uncoast-unconf

Repo for website for the Uncoast Unconf (coming 2019)

# How-to
(In Sam's understanding)

1. First, get blogdown: `install.packages("blogdown")`
2. Don't put public folder on repo: "Basically, you have to host all source files of your website in a GIT repository. You do not need to put the public/ directory under version control because it will be automatically generated. Currently, Netlify supports GIT repositories hosted on GitHub, GitLab, and BitBucket. With any of these accounts, you can log into Netlify from its homepage and follow the guide to create a new site from your GIT repository." [(from blogdown book)](https://bookdown.org/yihui/blogdown/netlify.html) Sam T has a Netlify account when we are ready to launch.
3. To edit, only edit specific files: "A theme author who is aware of the fact that users may customize her theme will typically provide two ways: one is to provide options in config.toml, so that you can change these options without touching the template files; the other is to leave a few lightweight template files under layouts/ in the theme, so that you can override them without touching the core template files." [(from blogdown book)](https://bookdown.org/yihui/blogdown/custom-layouts.html). See theme/vex-hugo/layouts and theme/vex-hugo/static/css/style.css.
4. More coming later probably.

