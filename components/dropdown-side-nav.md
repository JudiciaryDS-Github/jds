---
description: Dropdowns menus allow users to read or select different options.
---

# Dropdown / Side Nav

## [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#dropdown-wrapper)

### Example

![](../.gitbook/assets/image%20%2887%29.png)

```text
<div class="row">
   <div class="col-md-4 col-lg-3">
            <div class="side-nav">
                <ul>
                  <li><a href="#"><span>Main menu(no icon)</span></a></li>
                 
                  <li class="dropdown-cust"><a href="javascript:void(0)" class="dropdown-toggle-cust"><span>Main menu + sub nav (no icon)</span></a>
                    <div class="dropdown-menu-cust"> <a class="dropdown-item active" href="#">Sub menu one</a> <a class="dropdown-item" href="#">Sub menu two</a> <a class="dropdown-item" href="#">Sub menu three</a> </div>
                  </li>
				  <li><a href="#"><i class="fal fa-briefcase"></i><span>Main menu(has icon)</span></a></li>
                  <li class="dropdown-cust"><a href="javascript:void(0)" class="dropdown-toggle-cust"><i class="fal fa-briefcase"></i><span>Main menu + sub nav (has icon)</span></a>
                    <div class="dropdown-menu-cust"> <a class="dropdown-item active" href="#">Sub menu one</a> <a class="dropdown-item" href="#">Sub menu two</a> <a class="dropdown-item" href="#">Sub menu three</a> </div>
                  </li>
            
                </ul>
              </div>
   </div>
</div>
```

### When to use

**Dropdowns should be used:**

* When you have limited space or your list is too long.
* For example, having more than 7 items in a predetermined list.
* For bringing users to a different page, or section within a page.

**Dropdowns should not be used:**

* When requiring users to select from a predetermined list of answers.
* Better alternatives would be the checkbox or radios component.
* for including checkboxes as users may not know how to select multiple options presented to them in a dropdown.

