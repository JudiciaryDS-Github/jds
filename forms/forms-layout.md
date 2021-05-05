---
description: >-
  Examples and usage guidelines for form control styles, layout options, and
  custom components for creating a wide variety of forms.
---

# Form - Layout

## [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/page-with-form.html)

![](../.gitbook/assets/image%20%28129%29.png)

![](../.gitbook/assets/image%20%2847%29.png)

![](../.gitbook/assets/image%20%2862%29.png)

## Form Panel Title \(Label on Top\)

Form fields are grouped and wrapped inside `form-panel`div

![](../.gitbook/assets/image%20%28132%29.png)

![](../.gitbook/assets/image%20%28128%29.png)

```text
<div class="form-panel">
          <div class="form-panel-header">
            <h2>Form Panel  Title (Label on Top) </h2>
            <p>Form fields are grouped and wrapped inside <code>form-panel</code> div.</p>
          </div>
          <div class="form-panel-body">
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label class="col-form-label">Full Name</label>
                  <input class="form-control" type="text">
                  <small class="form-text text-muted">Please enter your full name</small> </div>
                <div class="form-group">
                  <label class="col-form-label">Email Address</label>
                  <input class="form-control" id="email" name="email" type="email" aria-describedby="email" autocomplete="email" spellcheck="false">
                  <small class="form-text text-muted">We will never share your email with anyone else</small> </div>
                <div class="form-group">
                  <label class="col-form-label">Postal code</label>
                  <div class="input-group">
                    <input type="text" class="form-control form-control-xsm" placeholder="" aria-label="" aria-describedby="">
                    <div class="input-group-append">
                      <button class="btn btn-primary" type="button">Find</button>
                    </div>
                  </div>
                  <small class="form-text text-muted">This is example helper text!</small> </div>
                <div class="form-group">
                  <label class="col-form-label">Block / house no.</label>
                  <input type="text" value="53A" class="form-control form-control-sm">
                </div>
                <div class="form-group">
                  <label class="col-form-label">Street Name</label>
                  <input type="text" value="Tampines Street 12" class="form-control">
                </div>
                <div class="multi-field">
                  <div class="form-group">
                    <label class="col-form-label">Floor no.<br>
                      (optional)</label>
                    <input type="text" value="12" class="form-control form-control-sm">
                  </div>
                  <div class="form-group">
                    <label class="col-form-label">Unit no.<br>
                      (optional)</label>
                    <input type="text" value="12" class="form-control form-control-sm">
                  </div>
                </div>
                <div class="form-group">
                  <label class="col-form-label">Subscription</label>
                  <div class="input-group">
                    <div class="input-group-prepend"> <span class="input-group-text" id="inputGroup-sizing-sm"><i class="far fa-dollar-sign"></i></span> </div>
                    <input type="text" class="form-control form-control-sm">
                  </div>
                </div>
                <div class="form-group">
                  <label class="col-form-label">Communication</label>
                  <div>
                    <div class="form-check">
                      <label class="form-check-label">
                        <input class="form-check-input" type="checkbox" name="Communication">
                        Email <span class="checkbox-overlay "></span> </label>
                    </div>
                    <div class="form-check">
                      <label class="form-check-label">
                        <input class="form-check-input" type="checkbox" name="Communication">
                        SMS <span class="checkbox-overlay "></span> </label>
                    </div>
                    <div class="form-check">
                      <label class="form-check-label">
                        <input class="form-check-input" type="checkbox" name="Communication">
                        Phone <span class="checkbox-overlay "></span> </label>
                    </div>
                  </div>
                </div>
                <div class="form-group required">
                  <label class="col-form-label">Communication</label>
                  <div>
                    <div class="form-check">
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
                  </div>
                  <span class="message text-danger">Error message</span> </div>
                <div class="form-group required">
                  <label class="col-form-label">Input with success message</label>
                  <div class="field-icon field-success">
                    <input class="form-control" type="text">
                  </div>
                  <span class="message text-success">This is a success message.</span> <small class="form-text text-muted">Example help text which will remains unchanged</small> </div>
                <div class="form-group required">
                  <label class="col-form-label">Input with error</label>
                  <div class="field-icon field-danger">
                    <input class="form-control" type="text">
                  </div>
                  <span class="message text-danger">This is an error message. </span> <small class="form-text text-muted">Example help text which will remains unchanged</small> </div>
              </div>
            </div>
          </div>
          <div class="form-panel-footer text-center">
            <button type="button" class="btn btn-primary my-1">Action</button>
            <button type="button" class="btn btn-dark my-1">Action</button>
          </div>
        </div>
```

## Form Panel Boxed

![](../.gitbook/assets/image%20%2877%29.png)

```text
<div class="form-panel-boxed">
          <div class="form-panel-header">
            <h2>Form Panel Title (Label on left)</h2>
            <p>Form fields are grouped and wrapped inside <code>form-panel-boxed</code> div.</p>
          </div>
          <div class="form-panel-body">
            <div class="form-group row">
              <label class="col-form-label col-lg-4">Full Name</label>
              <div class="col-lg-6">
                <input class="form-control" type="text">
                <small class="form-text text-muted">Please enter your full name</small> </div>
            </div>
            <div class="form-group row">
              <label class="col-form-label col-lg-4">Email Address</label>
              <div class="col-lg-6">
                <input class="form-control" id="email2" name="email" type="email" aria-describedby="email" autocomplete="email" spellcheck="false">
                <small class="form-text text-muted">We will never share your email with anyone else</small> </div>
            </div>
            <div class="form-group row">
              <label class="col-form-label col-lg-4">Subscription</label>
              <div class="col-lg-6">
                <div class="input-group">
                  <div class="input-group-prepend"> <span class="input-group-text" id="sizing-sm"><i class="far fa-dollar-sign"></i></span> </div>
                  <input type="text" class="form-control form-control-sm">
                </div>
              </div>
            </div>
            <div class="form-group row">
              <label class="col-form-label col-lg-4">Communication</label>
              <div class="col-lg-6">
                <div class="form-check form-check-inline">
                  <label class="form-check-label">
                    <input class="form-check-input" type="checkbox" name="Communication">
                    Email <span class="checkbox-overlay "></span> </label>
                </div>
                <div class="form-check form-check-inline">
                  <label class="form-check-label">
                    <input class="form-check-input" type="checkbox" name="Communication">
                    SMS <span class="checkbox-overlay "></span> </label>
                </div>
                <div class="form-check form-check-inline">
                  <label class="form-check-label">
                    <input class="form-check-input" type="checkbox" name="Communication">
                    Phone <span class="checkbox-overlay "></span> </label>
                </div>
              </div>
            </div>
            <div class="form-group row required">
              <label class="col-form-label col-lg-4">Communication</label>
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
            <div class="form-group required row">
              <label class="col-form-label col-lg-4">Input with success message</label>
              <div class="col-lg-6">
                <div class="field-icon field-success">
                  <input class="form-control" type="text">
                </div>
                <span class="message text-success">This is a success message.</span> <small class="form-text text-muted">Example help text which will remains unchanged</small> </div>
            </div>
            <div class="form-group required row">
              <label class="col-form-label col-lg-4">Input with success message</label>
              <div class="col-lg-6">
                <div class="field-icon field-danger">
                  <input class="form-control" type="text">
                </div>
                <span class="message text-danger">This is an error message. </span> <small class="form-text text-muted">Example help text which will remains unchanged</small> </div>
            </div>
          </div>
          
 </div>
```

