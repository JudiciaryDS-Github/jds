---
description: >-
  A basic widget for getting the user input is a text field. Keyboard and mouse
  can be used for providing or changing data.
---

# Text Input

## [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#textinput-wrapper)

![](../.gitbook/assets/image%20%2851%29.png)

![](../.gitbook/assets/image%20%2825%29.png)

```text
<div class="container-fluid">
        <div class="form-panel-boxed">
          <div class="form-panel-body">
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label class="col-form-label">Default</label>
                  <input class="form-control" type="text">
                  <small class="form-text text-muted">This is example helper text!</small> </div>
                
                <div class="form-group">
                  <label class="col-form-label">Default small</label>
                  <input class="form-control form-control-sm" type="text">
                  <small class="form-text text-muted">This is example helper text!</small> </div>
                <div class="form-group">
                  <label class="col-form-label">Default extra small</label>
                  <input class="form-control form-control-xsm" type="text">
                  <small class="form-text text-muted">This is example helper text!</small> </div>
                <div class="form-group disabled">
                  <label class="col-form-label">Disabled</label>
                  <input class="form-control" type="text">
                  <small class="form-text text-muted">This is example helper text!</small> </div>
                
                <div class="form-group  required">
                  <label class="col-form-label">Input with success message</label>
                  <div class="field-icon field-icon-md field-success">
                    <input class="form-control" type="text">
                  </div>
                  <span class="message text-success">This is a success message.</span> <small class="form-text text-muted">This is example helper text!</small> </div>
                
                
                <div class="form-group required">
                  <label class="col-form-label">Input with error</label>
                  <div class="field-icon field-danger">
                    <input class="form-control" type="text">
                  </div>
                  <span class="message text-danger">This is an error message. </span> <small class="form-text text-muted">This is example helper text!</small> </div>
                <div class="form-group">
                  <label class="col-form-label">Inline button</label>
                  <div class="input-group">
                    <input type="text" class="form-control" placeholder="" aria-label="" aria-describedby="">
                    <div class="input-group-append">
                      <button class="btn btn-primary" type="button">Find</button>
                    </div>
                  </div>
                  <small class="form-text text-muted">This is example helper text!</small> </div>
                
                
                <div class="form-group">
                  <label class="col-form-label">Inline button extra small</label>
                  <div class="input-group">
                    <input type="text" class="form-control form-control-xsm" placeholder="" aria-label="" aria-describedby="">
                    <div class="input-group-append">
                      <button class="btn btn-primary" type="button">Find</button>
                    </div>
                  </div>
                  <small class="form-text text-muted">This is example helper text!</small> </div>
                <div class="form-group">
                  <label class="col-form-label">With icon</label>
                  <div class="input-group input-group-with-icon">
                    <input type="text" class="form-control" placeholder="" aria-label="" aria-describedby="">
                    <div class="input-group-append">
                      <button class="btn" type="button"><i class="fal fa-search"></i></button>
                    </div>
                  </div>
                  <small class="form-text text-muted">This is example helper text!</small> </div>
                
                
                
              </div>
            </div>
          </div>
        </div>
  </div>
```

### Usability Guidelines

* Use the appropriate field length for the input
* Length provides the users with an idea of how much text to input E.g. a postal code text input should only be 6 numbers long
* Avoid using label as placeholder text inside of the text field. This ensures that the hint text is available, and users can review their answers if need be. Clear labelling would also help users to understand better what to input.
* If hint text is used, give examples to show users how you’ll like them to enter their answers or how you will be using their information E.g. for emails, a useful hint text would be "We will only use your email for receipts." or specify the date format

### When to use

Use the text input component when you need to let users enter text that’s no longer than a single line, such as their name or phone number

### When not to use

Do not use the text input component if you need to let users enter longer answers that might span multiple lines. In this case, you should use the text area component.

