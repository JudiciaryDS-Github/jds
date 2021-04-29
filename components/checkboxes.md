---
description: >-
  Checkboxes are most commonly used to give users a way to make a range of
  selections ( one or more). They may also be used as a way to have users
  indicate they agree to specific terms and services.
---

# Checkboxes

## [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#checkbox-wrapper)

## Example

![](../.gitbook/assets/image%20%2813%29.png)

```text
<!--Checkboxes Stacked-->
<div class="form-group">
   <label class="col-form-label">Stacked Checkboxes</label>
   <div>
      <div class="form-check">
         <label class="form-check-label">
         <input class="form-check-input" type="checkbox" name="Checkbox 1">Checkbox 1<span class="checkbox-overlay "></span> </label>
      </div>
      <div class="form-check">
         <label class="form-check-label">
         <input class="form-check-input" type="checkbox" name="Checkbox 2">Checkbox 2<span class="checkbox-overlay "></span> </label>
      </div>
      <div class="form-check">
         <label class="form-check-label">
         <input class="form-check-input" disabled="" type="checkbox" name="Checkbox 3">Checkbox 3 (Disabled)<span class="checkbox-overlay "></span> </label>
      </div>
      <div class="form-check">
         <label class="form-check-label">
         <input class="form-check-input" checked="" disabled="" type="checkbox" name="Checkbox 4">Checkbox 4<span class="checkbox-overlay "></span> </label>
      </div>
   </div>
</div>
<!--Checkboxes Horizontal-->
<div class="form-group row">
   <label class="col-form-label col-lg-4">Communication</label>
   <div class="col-lg-6">
      <div class="form-check form-check-inline">
         <label class="form-check-label">
         <input class="form-check-input" type="checkbox" name="Checkbox 1">Checkbox 1<span class="checkbox-overlay "></span> </label>
      </div>
      <div class="form-check form-check-inline">
         <label class="form-check-label">
         <input class="form-check-input" type="checkbox" name="Checkbox 2">Checkbox 2<span class="checkbox-overlay "></span> </label>
      </div>
      <div class="form-check form-check-inline">
         <label class="form-check-label">
         <input class="form-check-input" disabled="" type="checkbox" name="Checkbox 3">Checkbox 3<span class="checkbox-overlay "></span> </label>
      </div>
      <div class="form-check form-check-inline">
         <label class="form-check-label">
         <input class="form-check-input" disabled="" type="checkbox" name="Checkbox 4">Checkbox 4<span class="checkbox-overlay "></span> </label>
      </div>
   </div>
</div>
```

### When to use

**Checkboxes should be used when:**

* You want users to select multiple items from a predetermined list of items.
* Your users need to see all available options at once.
* When users need to agree to terms and conditions

**Checkboxes should not be used for:**

* If user needs to select 1 option from a predetermined list of items, using radio buttons would be more appropriate.

