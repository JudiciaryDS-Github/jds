---
description: >-
  Text area specifies a control that allows user to write text over multiple
  rows. Used when the expected user input is long
---

# Text Area

## [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#textarea-wrapper)

### Default Form

![](../.gitbook/assets/image%20%2829%29.png)

### Horizontal Form 

![](../.gitbook/assets/image%20%2826%29.png)

```text
<div class="form-group required">
    <label class="col-form-label">Text area label</label>
    <textarea class="form-control form-control-lg" placeholder="Enter text  here" rows="5"></textarea>
</div>

<!--Horizontal Form-->
<div class="form-group row required">
  <label class="col-form-label col-md-3">Text area label</label>
  <div class="col-md-9">
    <textarea class="form-control form-control-lg" placeholder="Enter text  here" rows="5"></textarea>
  </div>
</div>
```

### When to use

* Use for freeform data entry when you need to let users enter an amount of text that’s longer than a single line.

### When not to use

* Avoid using textarea to answer open-ended questions as it is difficult answer.
* We recommend that you break your questions up into a series of simpler questions instead. For example, consider using the checkbox component if you want users to give multiple answers from a predetermined set of options.

### ﻿

