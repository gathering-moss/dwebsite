+++
title = "todos"
description = "Drafted post, very drafty."
date = 2026-03-12
draft = true
+++

We're going to remove the blog for now, so you'll have to add this back into the config, ok?

Copied content from config

<ul>
  <li>
    <input type="checkbox" checked />
    <label>&nbsp;Copied content from config</label>
  </li>
  <li>
    <input type="checkbox" checked />
    <label>&nbsp;Pasted content from config into codeblock below</label>
  </li>
  <li>
    <input type="checkbox" />
    <label>&nbsp;Deleted blog url content from config</label>
  </li>
  <li>
    <input type="checkbox" />
    <label>&nbsp;Write a blog post</label>
  </li>
  <li>
    <input type="checkbox" />
    <label>&nbsp;Write another blog post</label>
  </li>
  <li>
    <input type="checkbox" />
    <label>&nbsp;Copy content from codeblock</label>
  </li>
  <li>
    <input type="checkbox" />
    <label>&nbsp;Paste content into config</label>
  </li>
</ul>

```
# Links used in the nav
# For local files use same link format as in Markdown, i.e. "@/blog/_index.md".
# See https://www.getzola.org/documentation/content/linking/#internal-links
links = [
	{ name = "Links", menu = [
		{ url = "@/about/_index.md", name = "About" },
		{ url = "@/work/_index.md", name = "Work" },
		{ url = "@/blog/_index.md", name = "Blog" },
		{ url = "@/colophon/_index.md", name = "Colophon"}
	] }
]

[extra.footer]
# Page links
links = [
	{ url = "@/about/_index.md", name = "About" },
	{ url = "@/work/_index.md", name = "Work" },
	{ url = "@/blog/_index.md", name = "Blog" }
]

```
