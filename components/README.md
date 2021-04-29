---
description: >-
  Pagination is used for splitting up content or data into several pages, with a
  control for navigating to the next or previous page.
---

# Components

## [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#pagination-wrapper)

### Example

![](../.gitbook/assets/image%20%2853%29.png)

```text
<div class="pagination-container">
<!--Items per page .-->  
 <div class="item_per_page">
      <span>Show
         <select class="custom-select">
            <option selected="" value="10">10</option>
            <option value="20">20</option>
            <option value="50">50</option>
            <option value="100">100</option>
         </select>
         entries
      </span>
   </div>
<!--Current vs Total-->  
   <div class="item_count">1-20 of 85 items</div>
   <ul class="pagination">
      <li class="page-item disabled"><a class="page-link" href="#"><i class="fal fa-chevron-left"></i><span class="sr-only">Previous</span></a></li>
      <li class="page-item active"><a class="page-link" href="#">1</a></li>
      <li class="page-item"><a class="page-link" href="#">2</a></li>
      <li class="page-item"><a class="page-link" href="#">3</a></li>
      <li class="page-item"><a class="page-link" href="#"><i class="fal fa-chevron-right"></i><span class="sr-only">Next</span></a></li>
   </ul>
<!--Pagination and Jump to a page.-->  
   <div class="input-group input-group ml-4">
      <span class="mt-2">Go to</span>
      <input type="text" class="form-control ml-1" placeholder="Page#" aria-label="Jump to a page" aria-describedby="basic-addon2">
      <div class="input-group-append">
         <button class="btn btn-dark" type="button"><i class="fal fa-chevron-right"></i></button>
      </div>
   </div>
</div>
```

### When to use

#### Pagination should be used for:

* Displaying large amounts of related content that spans across multiple pages. For example, search results or forum posts.

#### Pagination should not be used for:

* Indicating progress, such as in a transaction.
* Replacing Navigation.

