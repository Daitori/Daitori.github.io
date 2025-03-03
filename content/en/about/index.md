---
title: About me
linkTitle: About me
menu: {main: {weight: 10}}
resources:
  - src: "**.{png,jpg}"
    title: "Image #:counter"
---

{{% blocks/cover title="About me" image_anchor="bottom" height="auto" %}}

A sample site using the Docsy Hugo theme.
{.mt-5}

{{% /blocks/cover %}}

{{% blocks/lead %}}

<div class="row">
  <div class="col-lg-6 col-md-6 col-sm-12">
    Goldydocs is a sample site using the [Docsy](https://github.com/google/docsy)
    Hugo theme that shows what it can do and provides you with a template site
    structure. It’s designed for you to clone and edit as much as you like. See the
    different sections of the documentation and site for more ideas.
  </div>
  <div class="col-lg-6 col-md-6 col-sm-12">
    {{< imgproc esiea Fill "600x300" >}}
    Fetch and scale an image in the upcoming Hugo 0.43.
    {{< /imgproc >}}
  </div>
</div>

<div class="row mt-4">
  <div class="col-lg-6 col-md-6 col-sm-12">
    {{< imgproc esiea Fill "600x300" >}}
    Fetch and scale an image in the upcoming Hugo 0.43.
    {{< /imgproc >}}
  </div>
  <div class="col-lg-6 col-md-6 col-sm-12">
    Goldydocs is a sample site using the [Docsy](https://github.com/google/docsy)
    Hugo theme that shows what it can do and provides you with a template site
    structure. It’s designed for you to clone and edit as much as you like. See the
    different sections of the documentation and site for more ideas.
  </div>
</div>

{{% /blocks/lead %}}