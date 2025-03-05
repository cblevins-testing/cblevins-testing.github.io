---
title: "Frontmatter for a Jupyter Notebook"
permalink: /notebook-frontmatter/
layout: page
---

After saving a Jupyter Notebook as an HTML file it can be rendered on your portfolio page. To do so, you'll just need to add "frontmatter" at the very top of the document. Copy and paste the following code at the top of your HTML file and make sure to change the `title`, `permalink`, `date`, and `description` fields.

```yaml
---
layout: notebook
title: "Example Title You Can Change"
permalink: /example-jupyter-notebook-2/
showcase: true
tools: ["Python"]
date: 2021-12-10
description: >
  This is an example of a Jupyter Notebook that shows images.
---
```
