---
description: 'Notifications provide short, timely, and relevant information for your users.'
---

# Notification

## [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#notfication-wrapper)

### Types

Notifications / Alerts are available for any length of text, as well as an optional dismiss button.

### Variants

For proper styling, use one of the required contextual classes \(e.g., .alert-success\). For inline dismissal, use the alerts you must use \( JS provided\).  


![](../.gitbook/assets/image%20%2838%29.png)

```text
<!--Default Alert-->
<div class="alert alert-default" role="alert"> This is a standard notification/alert. </div>
<!--Dismissable Alert-->
<div class="alert alert-default alert-dismissible fade show" role="alert"> This is a <strong>dismissable!</strong> notification/alert.
   <button type="button" class="close" data-dismiss="alert" aria-label="Close"> <span aria-hidden="true"><i class="fal fa-times-circle"></i></span> </button>
</div>
<!--With a link -->
<div class="alert alert-default" role="alert"> This is a notification/alert <a href="#" class="alert-link">with a link</a>. </div>
<!--With an icon -->
<div class="alert alert-default has-icon alert-dismissible fade show" role="alert"> <span><i class="fal fa-info-circle"></i></span> This is a notification/alert <a href="#" class="alert-link">with an icon</a>.
   <button type="button" class="close" data-dismiss="alert" aria-label="Close"> <span aria-hidden="true"><i class="fal fa-times-circle"></i></span> </button>
</div>
<div class="alert alert-default has-icon alert-large" role="alert">
   <span><i class="fal fa-info-circle"></i></span>
   <div class="alert-content">
      <h4>Title / Heading of the alert</h4>
      <p>Description will be shown here. This can be a combination of dismissible and link.</p>
   </div>
</div>
<!--Success-->
<div class="alert alert-success has-icon alert-large" role="alert">
   <span><i class="fal fa-check-circle"></i></span>
   <div class="alert-content">
      <h4>Success</h4>
      <p>Description will be shown here. This can be a combination of dismissible and link.</p>
   </div>
</div>
<!--Warning-->
<div class="alert alert-warning has-icon alert-large" role="alert">
   <span><i class="fal fa-exclamation-triangle"></i></span>
   <div class="alert-content">
      <h4>Warning</h4>
      <p>Description will be shown here. This can be a combination of dismissible and link.</p>
   </div>
</div>
<!--Warning-->
<div class="alert alert-error has-icon alert-large" role="alert">
   <span><i class="fal fa-times-circle"></i></span>
   <div class="alert-content">
      <h4>Error Message</h4>
      <p>Description will be shown here. This can be a combination of dismissible and link.</p>
   </div>
</div>
<!--Example-->
<div class="alert alert-example has-icon alert-large" role="alert">
   <span><i class="fal fa-lightbulb-on"></i></span>
   <div class="alert-content">
      <h4>Example</h4>
      <p>Description will be shown here. This can be a combination of dismissible and link.</p>
   </div>
</div>
```

![](../.gitbook/assets/image%20%2898%29.png)

```text
<!--Full width notification bar to show system down time, maintenance notices etc..-->
<div id="notification" class="notification_fw bg-primary" style="display: block;">
  <div class="container-fluid">
  <div class="notification_close" title="Dismiss Notification"><span class="fal fa-times"></span></div>
  <i class="fal fa-info-circle"></i> <strong>Important Notice:</strong> This is a full width notification bar. You have a notification! </div>
</div>
<div class="notification_fw bg-success d-block">
    <div class="container-fluid">
      <div class="notification_close" title="Dismiss Notification"><span class="fal fa-times"></span></div>
      <i class="fal fa-check-circle"></i> <strong>Success:</strong> This is a full width notification bar. You have a notification! </div>
  </div>
  <div class="notification_fw bg-warning d-block">
    <div class="container-fluid">
      <div class="notification_close" title="Dismiss Notification"><span class="fal fa-times"></span></div>
      <i class="fal fa-exclamation-circle"></i> <strong>Warning:</strong> This is a full width notification bar. You have a notification! </div>
  </div>
  <div class="notification_fw bg-error d-block">
    <div class="container-fluid">
      <div class="notification_close" title="Dismiss Notification"><span class="fal fa-times"></span></div>
      <i class="fal fa-times-circle"></i> <strong>Error:</strong> This is a full width notification bar. You have a notification! </div>
  </div>
```



