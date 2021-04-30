---
description: >-
  Callouts are an excerpt of text or an article that has been pulled out and
  used as a visual clue to draw the eye to the text. Callout helps in directing 
  user's attention to important pieces of info.
---

# Callout

## [Interactive](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#callouts-wrapper) [demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#callouts-wrapper)

### Example

![](../.gitbook/assets/image%20%2825%29.png)

```text
<!--Call out Default-->
<div class="alert alert-default has-icon alert-large" role="alert" > <span><i class="fal fa-info-circle"></i></span>
  <div class="alert-content">
    <h4>Title / Heading of the alert</h4>
    <p>Description will be shown here. This can be a combination of dismissible and link.</p>
  </div>
</div>
<!-- Call out Info-->
<div class="alert alert-info has-icon alert-large" role="alert" > <span><i class="fal fa-info-circle"></i></span>
  <div class="alert-content">
    <h4>Info or Notes</h4>
    <p>Description will be shown here. This can be a combination of dismissible and link.</p>
  </div>
</div>
```

### When to use

**Callouts should be used for:**

* Highlighting very specific information within a page by differentiating it from surrounding content. For example, quotes or additional information.

**Callouts should not be used for:**

* Information presented in complex pages.
* Readers will be distracted by the other visually prominent elements.

For important or critical information use the **notification component** with the correct color state.

