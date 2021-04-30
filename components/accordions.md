---
description: >-
  Accordions are interactive elements that allow users to either show or hide
  related content, through a dropdown mechanism.
---

# Accordion

## [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#accordion-wrapper)

### Types

![Accordion collapsed](../.gitbook/assets/image%20%2815%29.png)

![Accordion opened](../.gitbook/assets/image%20%2846%29.png)

```text
<div class="accordion">
   <div class="card">
      <div class="card-header">
         <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#accordion-content1" aria-expanded="false" aria-controls="accordion-content1" href="#accordion-content1" title="Toggle Accordion">Accordion bar 1</button>
      </div>
      <div id="accordion-content1" class="collapse">
         <div class="card-body">
            <h4>This is an example of a open section</h4>
            Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS. 
         </div>
      </div>
   </div>
   <div class="card ">
      <div class="card-header">
         <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#accordion-content2" aria-expanded="false" aria-controls="accordion-content2" href="#accordion-content2" title="Toggle Accordion">Accordion bar 2</button>
      </div>
      <div id="accordion-content2" class="collapse">
         <div class="card-body">
            <h4>This is an example of a open section</h4>
            Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS. 
         </div>
      </div>
   </div>
   <div class="card">
      <div class="card-header">
         <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#accordion-content3" aria-expanded="false" aria-controls="accordion-content3" href="#accordion-content3" title="Toggle Accordion" s="">Accordion bar 3</button>
      </div>
      <div id="accordion-content3" class="collapse">
         <div class="card-body">
            <h4>This is an example of a open section</h4>
            Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS. 
         </div>
      </div>
   </div>
</div>
```

### When to use

#### Accordions should be used when:

There is insufficient space within the page to display the necessary information.

* Users require an overview of specific content that’s related to one another.

#### Accordions should not be used when:

They contain information that is essential to your users.

* Accordions hide content, and there may be users who may miss the content or not understand how accordions work.
* If users need to see all information in a single page, you can consider reducing your content, splitting them into smaller sections, or use well-formatted text \(e.g. headers, contents, section\)

Accordions increases the cognitive load for users, as decisions have to be made when clicking on the headers. Users may also ignore important information if it is hidden in an accordion.

