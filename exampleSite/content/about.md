+++
date  = "2015-08-22"
title = "Link custom pages"
menu  = "main"
url = "about/"
hide = "true"
+++

You can add custom pages like this by adding `menu = "main"` in the frontmatter:

```toml
+++
date  = "2015-08-22"
title = "About me"
menu  = "main"
url = "about/"
+++
```

This site is just a usual document. Create a new file, e.g. `about.md` in the `content` content directory. The `url` variable in the frontmatter allows you to define the final url of the about page.