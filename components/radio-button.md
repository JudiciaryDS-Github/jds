---
description: >-
  Use radio component when users can only select one option from a list. Always
  position radios to the left of their labels. This makes them easier to find,
  especially for users of screen magnifiers.
---

# Radio Button

## [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#radiobutton-wrapper)

### Examples

![](../.gitbook/assets/image%20%2834%29.png)

```text
<!--Radio Button group stacked-->
<div class="form-group">
   <label class="col-form-label">Label for Stacked Radio</label>
       <div class="form-check ">
         <label class="form-check-label" for="RadioDefault211">
         <input class="form-check-input" type="radio" name="RadioDefault111" id="RadioDefault211">
         Radio 1 (Default) <span class="radio-overlay "></span> </label>
      </div>
      <div class="form-check">
         <label class="form-check-label" for="RadioDefault212">
         <input class="form-check-input" type="radio" name="RadioDefault111" id="RadioDefault212">
         Radio 2 (Default) <span class="radio-overlay "></span> </label>
      </div>
      <div class="form-check">
         <label class="form-check-label" for="RadioDefault213">
         <input class="form-check-input" type="radio" name="RadioDefault111" id="RadioDefault213">
         Radio 3 (Default) <span class="radio-overlay "></span> </label>
      </div>
<!--if there is any error show the below span-->
   <span class="message text-danger">Error message</span> 
</div>
<!--Radio Button group inline-->
<div class="form-group row">
              <label class="col-form-label col-lg-4">Label for Inline Radio</label>
              <div class="col-lg-6">
                <div class="form-check form-check-inline">
                  <label class="form-check-label" for="RadioDefault2111">
                    <input class="form-check-input" type="radio" name="RadioDefault1111" id="RadioDefault2111">
                    Radio 1 (Default) <span class="radio-overlay "></span> </label>
                </div>
                <div class="form-check form-check-inline">
                  <label class="form-check-label" for="RadioDefault2122">
                    <input class="form-check-input" type="radio" name="RadioDefault1111" id="RadioDefault2122">
                    Radio 2 (Default) <span class="radio-overlay "></span> </label>
                </div>
                <div class="form-check form-check-inline">
                  <label class="form-check-label" for="RadioDefault2133">
                    <input class="form-check-input" type="radio" name="RadioDefault1111" id="RadioDefault2133">
                    Radio 3 (Default) <span class="radio-overlay "></span> </label>
                </div>
                <span class="message text-danger">Error message</span> </div>
            </div>
```

