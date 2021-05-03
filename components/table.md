---
description: >-
  Tables display sets of data across rows and columns. The features of table
  include record count, search, column sorting, page count, pagination.
---

# Table

## [Interactive Demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#static-table-wrapper)

### Static Table

![](../.gitbook/assets/image%20%28113%29.png)

```text
<div class="static-table">
          <div class="table-responsive">
            <table class="table table-striped table-hover">
              <thead>
                <tr>
                  <th scope="col">#</th>
                  <th scope="col">First</th>
                  <th scope="col">Last</th>
                  <th scope="col">Status</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td data-title="#">1</td>
                  <td data-title="First">Mark</td>
                  <td data-title="Last">Otto</td>
                  <td data-title="Status"><span class="jds-tag has-success-light">Approved</span></td>
                </tr>
                <tr>
                  <td data-title="#">2</td>
                  <td data-title="First">Jacob</td>
                  <td data-title="Last">Thornton</td>
                  <td data-title="Status"><span class="jds-tag has-error-light">Rejected</span></td>
                </tr>
                <tr>
                  <th data-title="#">3</th>
                  <td data-title="First">Larry</td>
                  <td data-title="Last">the Bird</td>
                  <td data-title="Status"><span class="jds-tag has-example-light">Example</span></td>
                </tr>
              </tbody>
            </table>
            <div class="'pagination-container'">
              <ul class="pagination justify-content-end">
                <li class="page-item disabled"><a class="page-link" href="#"><i class="fal fa-chevron-left"></i><span class="sr-only">Previous</span></a></li>
                <li class="page-item active"><a class="page-link" href="#">1</a></li>
                <li class="page-item"><a class="page-link" href="#">2</a></li>
                <li class="page-item"><a class="page-link" href="#">3</a></li>
                <li class="page-item"><a class="page-link" href="#"><i class="fal fa-chevron-right"></i><span class="sr-only">Next</span></a></li>
              </ul>
            </div>
          </div>
 </div>
```

### Data Table -  Desktop View

![](../.gitbook/assets/image%20%28107%29.png)

```text
<div class="container-fluid text-left" id="section-datatables">
  <table id="datatables-example" class="display nowrap dataTable dtr-inline collapsed" style="width:100%">
    <thead>
      <tr>
        <th>Name</th>
        <th>Position</th>
        <th>Office</th>
        <th class="text-center">Age</th>
        <th style="width: 120px">Start date</th>
        <th style="width: 100px">Salary</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Tiger Nixon</td>
        <td>System Architect</td>
        <td>Edinburgh</td>
        <td class="text-center">61</td>
        <td>2011/04/25</td>
        <td class="text-right">$320,800</td>
      </tr>
      <tr>
        <td>Garrett Winters</td>
        <td>Accountant</td>
        <td>Tokyo</td>
        <td class="text-center">63</td>
        <td>2011/07/25</td>
        <td class="text-right">$170,750</td>
      </tr>
      <tr>
        <td>Ashton Cox</td>
        <td>Junior Technical Author</td>
        <td>San Francisco</td>
        <td class="text-center">66</td>
        <td>2009/01/12</td>
        <td class="text-right">$86,000</td>
      </tr>
      <tr>
        <td>Cedric Kelly</td>
        <td>Senior Javascript Developer</td>
        <td>Edinburgh</td>
        <td class="text-center">22</td>
        <td>2012/03/29</td>
        <td class="text-right">$433,060</td>
      </tr>
      <tr>
        <td>Airi Satou</td>
        <td>Accountant</td>
        <td>Tokyo</td>
        <td class="text-center">33</td>
        <td>2008/11/28</td>
        <td class="text-right">$162,700</td>
      </tr>
      <tr>
        <td>Brielle Williamson</td>
        <td>Integration Specialist</td>
        <td>New York</td>
        <td class="text-center">61</td>
        <td>2012/12/02</td>
        <td class="text-right">$372,000</td>
      </tr>
      <tr>
        <td>Herrod Chandler</td>
        <td>Sales Assistant</td>
        <td>San Francisco</td>
        <td class="text-center">59</td>
        <td>2012/08/06</td>
        <td class="text-right">$137,500</td>
      </tr>
      <tr>
        <td>Rhona Davidson</td>
        <td>Integration Specialist</td>
        <td>Tokyo</td>
        <td class="text-center">55</td>
        <td>2010/10/14</td>
        <td class="text-right">$327,900</td>
      </tr>
    </tbody>
  </table>
</div>
```

### Data Table - Mobile View

![](../.gitbook/assets/image%20%28110%29.png)

{% hint style="info" %}
Note: This component requires third party component related js and css which was included in the package.
{% endhint %}

### When to use

Tables should be used for:

* Displaying tabular information such as statistics.
* Making comparisons between information.

Tables should not be used for:

* Displaying non-tabular data \(Using lists would be more appropriate\).
* Laying out a page.
* Large sections within a page.

