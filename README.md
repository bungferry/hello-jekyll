
# Hello, Jekyll! Theme - Get Started in 60 Seconds


Setup Jekyll with GitHub Pages in 60 Seconds


### Step 1 - Create the Jekyll Configuration / Settings File

Add your site title e.g. Your Site Title

`_config.yml`:

```
title: Your Site Title
```

### Step 2 - Create the Index Page

Add your index (front) page with a page title e.g. Welcome and using the default layout (to be created in Step 3):

`index.md`:

```
---
title: Welcome
layout: default
---

Hello, Jekyll!
```


### Step 3 -  Create the Master Layout

`_layouts/default.html`

```
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>{{ page.title }} - {{site.title}}</title>
</head>
<body>

  {{ content }}

</body>
</html>
```

That's it. Ready for serving.

Go on GitHub in your repos **Settings** tab to the **GitHub Pages** sections and pick **Use the master branch** in **Select Source**.
Save. Enjoy. Happy Jekylling!

### Live Demo

See a live demo @ [`bungferry.github.io/hello-jekyll/` »](https://bungferry.github.io/hello-jekyll/)
