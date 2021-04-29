---
description: >-
  A breadcrumb displays the current location within a hierarchy. It allows going
  back to states higher up in the hierarchy.
---

# Breadcrumb

## [Interactive](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#breadcrumb-wrapper) [demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#breadcrumb-wrapper)

![](../.gitbook/assets/image%20%2821%29.png)

```text
<nav aria-label="Full path to the current page">
          <ol class="breadcrumb">
            <li class="breadcrumb-item"><a href="#">Home</a></li>
            <li class="breadcrumb-item"><a href="#">Application Center</a></li>
            <li class="breadcrumb-item"><a href="#">Application List</a></li>
            <li class="breadcrumb-item active" aria-current="page">An Application</li>
          </ol>
        </nav>
<!--Breadcrumb with icon-->
<nav aria-label="Full path to the current page">
          <ol class="breadcrumb has-icon">
            <li class="breadcrumb-item"><a href="#"><i class="fal fa-home"></i><span class="sr-only">Home</span></a></li>
            <li class="breadcrumb-item"><a href="#"><i class="fal fa-list-alt"></i>Application Center</a></li>
            <li class="breadcrumb-item"><a href="#"><i class="fal fa-list-alt"></i>Application List</a></li>
            <li class="breadcrumb-item active" aria-current="page">An Application</li>
          </ol>
</nav>
```

