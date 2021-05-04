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
<div id="datatables-example_wrapper" class="dataTables_wrapper no-footer">
	<div class="dataTables_length" id="datatables-example_length">
		<label>Show 
			<select name="datatables-example_length" aria-controls="datatables-example" class="">
				<option value="10">10</option>
				<option value="25">25</option>
				<option value="50">50</option>
				<option value="100">100</option>
			</select> entries
		</label>
	</div>
	<div id="datatables-example_filter" class="dataTables_filter">
		<label>Search:
			<input type="search" class="" placeholder="" aria-controls="datatables-example">
			</label>
		</div>
		<table id="datatables-example" class="display nowrap dataTable dtr-inline no-footer" style="width: 100%;" role="grid" aria-describedby="datatables-example_info">
			<thead>
				<tr role="row">
					<th class="sorting_asc" tabindex="0" aria-controls="datatables-example" rowspan="1" colspan="1" data-column-index="0" style="width: 207px;" aria-sort="ascending" aria-label="Name: activate to sort column descending">Name</th>
					<th class="sorting" tabindex="0" aria-controls="datatables-example" rowspan="1" colspan="1" data-column-index="1" style="width: 309px;" aria-label="Position: activate to sort column ascending">Position</th>
					<th class="sorting" tabindex="0" aria-controls="datatables-example" rowspan="1" colspan="1" data-column-index="2" style="width: 156px;" aria-label="Office: activate to sort column ascending">Office</th>
					<th class="text-center sorting" tabindex="0" aria-controls="datatables-example" rowspan="1" colspan="1" data-column-index="3" style="width: 72px;" aria-label="Age: activate to sort column ascending">Age</th>
					<th style="width: 120px" class="sorting" tabindex="0" aria-controls="datatables-example" rowspan="1" colspan="1" data-column-index="4" aria-label="Start date: activate to sort column ascending">Start date</th>
					<th style="width: 100px" class="sorting" tabindex="0" aria-controls="datatables-example" rowspan="1" colspan="1" data-column-index="5" aria-label="Salary: activate to sort column ascending">Salary</th>
				</tr>
			</thead>
			<tbody>
				<tr role="row" class="odd">
					<td class="sorting_1 dtr-control">Airi Satou</td>
					<td>Accountant</td>
					<td>Tokyo</td>
					<td class="text-center">33</td>
					<td>2008/11/28</td>
					<td class="text-right">$162,700</td>
				</tr>
				<tr role="row" class="even">
					<td class="sorting_1 dtr-control">Angelica Ramos</td>
					<td>Chief Executive Officer (CEO)</td>
					<td>London</td>
					<td class="text-center">47</td>
					<td>2009/10/09</td>
					<td class="text-right">$1,200,000</td>
				</tr>
				<tr role="row" class="odd">
					<td class="sorting_1 dtr-control">Ashton Cox</td>
					<td>Junior Technical Author</td>
					<td>San Francisco</td>
					<td class="text-center">66</td>
					<td>2009/01/12</td>
					<td class="text-right">$86,000</td>
				</tr>
				<tr role="row" class="even">
					<td class="sorting_1 dtr-control">Bradley Greer</td>
					<td>Software Engineer</td>
					<td>London</td>
					<td class="text-center">41</td>
					<td>2012/10/13</td>
					<td class="text-right">$132,000</td>
				</tr>
				<tr role="row" class="odd">
					<td class="sorting_1 dtr-control">Brenden Wagner</td>
					<td>Software Engineer</td>
					<td>San Francisco</td>
					<td class="text-center">28</td>
					<td>2011/06/07</td>
					<td class="text-right">$206,850</td>
				</tr>
				<tr role="row" class="even">
					<td class="sorting_1 dtr-control">Brielle Williamson</td>
					<td>Integration Specialist</td>
					<td>New York</td>
					<td class="text-center">61</td>
					<td>2012/12/02</td>
					<td class="text-right">$372,000</td>
				</tr>
				<tr role="row" class="odd">
					<td class="sorting_1 dtr-control">Bruno Nash</td>
					<td>Software Engineer</td>
					<td>London</td>
					<td class="text-center">38</td>
					<td>2011/05/03</td>
					<td class="text-right">$163,500</td>
				</tr>
				<tr role="row" class="even">
					<td class="sorting_1 dtr-control">Caesar Vance</td>
					<td>Pre-Sales Support</td>
					<td>New York</td>
					<td class="text-center">21</td>
					<td>2011/12/12</td>
					<td class="text-right">$106,450</td>
				</tr>
				<tr role="row" class="odd">
					<td class="sorting_1 dtr-control">Cara Stevens</td>
					<td>Sales Assistant</td>
					<td>New York</td>
					<td class="text-center">46</td>
					<td>2011/12/06</td>
					<td class="text-right">$145,600</td>
				</tr>
				<tr role="row" class="even">
					<td class="sorting_1 dtr-control">Cedric Kelly</td>
					<td>Senior Javascript Developer</td>
					<td>Edinburgh</td>
					<td class="text-center">22</td>
					<td>2012/03/29</td>
					<td class="text-right">$433,060</td>
				</tr>
			</tbody>
			<!-- Table footer
               <tfoot><tr><th>Name</th><th>Position</th><th>Office</th><th class="text-center">Age</th><th>Start date</th><th>Salary</th></tr></tfoot>
               -->
		</table>
		<div class="dataTables_info" id="datatables-example_info" role="status" aria-live="polite">Showing 1 to 10 of 57 entries</div>
		<div class="dataTables_paginate paging_simple_numbers" id="datatables-example_paginate">
			<a class="paginate_button previous disabled" aria-controls="datatables-example" data-dt-idx="0" tabindex="-1" id="datatables-example_previous">
				<i class="fal fa-chevron-left"></i>
			</a>
			<span>
				<a class="paginate_button current" aria-controls="datatables-example" data-dt-idx="1" tabindex="0">1</a>
				<a class="paginate_button " aria-controls="datatables-example" data-dt-idx="2" tabindex="0">2</a>
				<a class="paginate_button " aria-controls="datatables-example" data-dt-idx="3" tabindex="0">3</a>
				<a class="paginate_button " aria-controls="datatables-example" data-dt-idx="4" tabindex="0">4</a>
				<a class="paginate_button " aria-controls="datatables-example" data-dt-idx="5" tabindex="0">5</a>
				<a class="paginate_button " aria-controls="datatables-example" data-dt-idx="6" tabindex="0">6</a>
			</span>
			<a class="paginate_button next" aria-controls="datatables-example" data-dt-idx="7" tabindex="0" id="datatables-example_next">
				<i class="fal fa-chevron-right"></i>
			</a>
		</div>
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

