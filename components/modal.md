---
description: >-
  The modal component inform users about a specific task and may contain
  critical information, require decisions, or involve multiple tasks.
---

# Modal

JDS extends Bootstrap Modal component with a variety of options to provide unique looking Modal components that matches SCJDS's design standards.

For more info on Bootstrap Modal please visit the official [Bootstrap Documentation](https://getbootstrap.com/docs/4.5/components/modal/).

## [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#notfication-wrapper)

### Modals

![Modals have few optional sizes, available via modifier classes to be placed on a .modal-dialog. These sizes triggers on at certain breakpoints to avoid horizontal scrollbars on narrower viewports.](../.gitbook/assets/image%20%2837%29.png)

```text
 <!-- Button trigger modal-->
            <button type="button" class="btn btn-primary mr-2" data-toggle="modal" data-target="#jdsModalSizeSm">Modal - Small</button>
            <button type="button" class="btn btn-primary mr-2" data-toggle="modal" data-target="#jdsModalSizeDefault">Modal - Default</button>
            <button type="button" class="btn btn-primary mr-2" data-toggle="modal" data-target="#jdsModalSizeLg">Modal - Large</button>
            <button type="button" class="btn btn-primary mr-2" data-toggle="modal" data-target="#jdsModalSizeXl">Modal - Extra Large</button>
            <button type="button" class="btn btn-primary mr-2" data-toggle="modal" data-target="#jdsModalSizeFullwidth">Modal - Full Width</button>
            <!--begin::Modal-->
            <div class="modal fade" id="jdsModalSizeSm" tabindex="-1" aria-labelledby="jdsModalSizeSm" aria-hidden="true" style="display: none;">
              <div class="modal-dialog modal-dialog-centered modal-sm" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <h5 class="modal-title" id="jdsModalLabel">Modal Title</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"> <i aria-hidden="true" class="ki ki-close"></i> </button>
                  </div>
                  <div class="modal-body">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</div>
                  <div class="modal-footer">
                    <button type="button" class="btn btn-light-primary font-weight-bold" data-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary font-weight-bold">Save changes</button>
                  </div>
                </div>
              </div>
            </div>
            <!--end::Modal--> 
            <!--begin::Modal-->
            <div class="modal fade" id="jdsModalSizeDefault" tabindex="-1" aria-labelledby="jdsModalSizeDefault" aria-hidden="true" style="display: none;">
              <div class="modal-dialog modal-dialog-centered" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <h5 class="modal-title" id="jdsModalLabe3l">Modal Title</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"> <i aria-hidden="true" class="ki ki-close"></i> </button>
                  </div>
                  <div class="modal-body">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</div>
                  <div class="modal-footer">
                    <button type="button" class="btn btn-light-primary font-weight-bold" data-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary font-weight-bold">Save changes</button>
                  </div>
                </div>
              </div>
            </div>
            <!--end::Modal--> 
            <!--begin::Modal-->
            <div class="modal fade" id="jdsModalSizeLg" tabindex="-1" aria-labelledby="jdsModalSizeLg" aria-hidden="true" style="display: none;">
              <div class="modal-dialog modal-dialog-centered modal-lg" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <h5 class="modal-title" id="jdsModalLabel5">Modal Title</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"> <i aria-hidden="true" class="ki ki-close"></i> </button>
                  </div>
                  <div class="modal-body">
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
                  </div>
                  <div class="modal-footer">
                    <button type="button" class="btn btn-light-primary font-weight-bold" data-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary font-weight-bold">Save changes</button>
                  </div>
                </div>
              </div>
            </div>
            <!--end::Modal--> 
            <!--begin::Modal-->
            <div class="modal fade" id="jdsModalSizeXl" tabindex="-1" aria-labelledby="jdsModalSizeXl" aria-hidden="true" style="display: none;">
              <div class="modal-dialog modal-dialog-centered modal-xl" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <h5 class="modal-title" id="jdsModalLabel2">Modal Title</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"> <i aria-hidden="true" class="ki ki-close"></i> </button>
                  </div>
                  <div class="modal-body">
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
                  </div>
                  <div class="modal-footer">
                    <button type="button" class="btn btn-light-primary font-weight-bold" data-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary font-weight-bold">Save changes</button>
                  </div>
                </div>
              </div>
            </div>
            <!--end::Modal--> 
            <!--begin::Modal-->
            <div class="modal fade" id="jdsModalSizeFullwidth" tabindex="-1" aria-labelledby="jdsModalSizeFullwidth" aria-hidden="true" style="display: none;">
              <div class="modal-dialog modal-dialog-centered modal-fullwidth" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <h5 class="modal-title" id="jdsModalLabel7">Modal Title</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"> <i aria-hidden="true" class="ki ki-close"></i> </button>
                  </div>
                  <div class="modal-body">
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
                  </div>
                  <div class="modal-footer">
                    <button type="button" class="btn btn-light-primary font-weight-bold" data-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary font-weight-bold">Save changes</button>
                  </div>
                </div>
              </div>
            </div>
            <!--end::Modal--> 
```

### Confirmation Dialogs

![](../.gitbook/assets/image%20%2842%29.png)

#### Default

![](../.gitbook/assets/image%20%2829%29.png)

```text
<!--Buttons to trigger confirmation dialogs-->
<button type="button" class="btn btn-outline-primary" data-toggle="modal" data-target="#default">Default</button>
<button type="button" class="btn btn-outline-success" data-toggle="modal" data-target="#success">Success</button>
<button type="button" class="btn btn-outline-warning" data-toggle="modal" data-target="#warning">Warning</button>
<button type="button" class="btn btn-outline-error" data-toggle="modal" data-target="#error">Error</button>
<button type="button" class="btn btn-outline-example" data-toggle="modal" data-target="#example">Example</button>
<!--Confirmation dialog modals-->
<div class="modal fade" id="default" tabindex="-1" aria-labelledby="default" style="display: block;" aria-modal="true" role="dialog">
    <div class="modal-dialog modal-dialog-centered modal-lg" role="document">
      <div class="modal-content has-icon alert alert-default">
        <div class="modal-header">
          <h3 class="modal-title"><i class="fas fa-info-circle"></i>Confirm Action</h3>
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"> <i aria-hidden="true" class="fal fa-times"></i> </button>
        </div>
        <div class="modal-body">
          <p>Are you sure you want to take this <strong>Specific Action</strong> ?</p>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-outline" data-dismiss="modal">Cancel</button>
          <button type="button" class="btn btn-primary btn-action">OK</button>
        </div>
      </div>
    </div>
  </div>
  <div class="modal fade" id="success" tabindex="-1" aria-labelledby="success" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-lg" role="document">
      <div class="modal-content has-icon alert alert-success">
        <div class="modal-header">
          <h3 class="modal-title"><i class="fas fa-check-circle"></i>Confirm Action</h3>
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"> <i aria-hidden="true" class="fal fa-times"></i> </button>
        </div>
        <div class="modal-body">
          <p>Are you sure you want to take this <strong>Specific Action</strong> ?</p>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-outline" data-dismiss="modal">Cancel</button>
          <button type="button" class="btn btn-success btn-action">OK</button>
        </div>
      </div>
    </div>
  </div>
  <div class="modal fade" id="warning" tabindex="-1" aria-labelledby="warning" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-lg" role="document">
      <div class="modal-content has-icon alert alert-warning">
        <div class="modal-header">
          <h3 class="modal-title"><i class="fas fa-exclamation-circle"></i>Confirm Action</h3>
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"> <i aria-hidden="true" class="fal fa-times"></i> </button>
        </div>
        <div class="modal-body">
          <p>Are you sure you want to take this <strong>Specific Action</strong> ?</p>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-outline" data-dismiss="modal">Cancel</button>
          <button type="button" class="btn btn-warning btn-action">OK</button>
        </div>
      </div>
    </div>
  </div>
  <div class="modal fade" id="error" tabindex="-1" aria-labelledby="error" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-lg" role="document">
      <div class="modal-content has-icon alert alert-error">
        <div class="modal-header">
          <h3 class="modal-title"><i class="fas fa-times-circle"></i>Confirm Action</h3>
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"> <i aria-hidden="true" class="fal fa-times"></i> </button>
        </div>
        <div class="modal-body">
          <p>Are you sure you want to take this <strong>Specific Action</strong> ?</p>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-outline" data-dismiss="modal">Cancel</button>
          <button type="button" class="btn btn-error btn-action">OK</button>
        </div>
      </div>
    </div>
  </div>
  <div class="modal fade" id="example" tabindex="-1" aria-labelledby="example" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-lg" role="document">
      <div class="modal-content has-icon alert alert-example">
        <div class="modal-header">
          <h3 class="modal-title"><i class="fal fa-lightbulb-on"></i>Confirm Action</h3>
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"> <i aria-hidden="true" class="fal fa-times"></i> </button>
        </div>
        <div class="modal-body">
          <p>Are you sure you want to take this <strong>Specific Action</strong> ?</p>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-outline" data-dismiss="modal">Cancel</button>
          <button type="button" class="btn btn-example btn-action">OK</button>
        </div>
      </div>
    </div>
  </div>
```

