+++
date  = "2015-08-22"
title = "Link custom pages"
menu  = "main"
+++

You can add custom pages like this by adding `menu = "main"` in the frontmatter:

```toml
+++
date  = "2015-08-22"
title = "About me"
menu  = "main"
+++
```

This site is just a usual document. Create a new subfolder in `content` and name this document `index.md`. For example, I'm located under `content/about/index.md` to add indicate the subsection `/about` in the URL. 

But you can also link posts that way without moving them.

If no document contains `menu = "main"` in the frontmatter the navigation will not be shown. Sounds easy, right?
