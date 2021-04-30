---
description: >-
  Tabs organize content across different screens, data sets, and other
  interactions.
---

# Tab

## [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#tab-wrapper)

### Horizontal tabs - Default

By default tabs are aligned to left. If it needs to be centered or right aligned, change "&lt;`ul class="nav nav-tabs left` to `ul class="nav nav-tabs center` **or** `ul class="nav nav-tabs right`

![](../.gitbook/assets/image%20%2816%29.png)

```text
<div class="horizontal-tab">
  <ul class="nav nav-tabs left">
    <li class="nav-item "><a class="nav-link active" data-toggle="tab" href="#h-tab-1">Tab 1</a></li>
    <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#h-tab-2">Tab 2</a></li>
    <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#h-tab-3">Tab 3</a></li>
    <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#h-tab-4">Tab 4</a></li>
    <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#h-tab-5">Tab 5</a></li>
  </ul>
          
  <!-- Tab panes -->
  <div class="tab-content">
    <div class="tab-pane active" id="h-tab-1">
      <h3 class="tab-title">Tab 1 Content</h3>
      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
    </div>
    <div class="tab-pane " id="h-tab-2">
      <h3 class="tab-title">Tab 2 Content</h3>
      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
    </div>
    <div class="tab-pane " id="h-tab-3">
      <h3 class="tab-title">Tab 3 Content</h3>
      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
    </div>
    <div class="tab-pane " id="h-tab-4">
      <h3 class="tab-title">Tab 4 Content</h3>
      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
    </div>
    <div class="tab-pane " id="h-tab-5">
      <h3 class="tab-title">Tab 5 Content</h3>
      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
    </div>
  </div>
</div>
```

### Horizontal tabs with icon - Centered

![Note: To align the tabs to center , replace left with center in the &apos;ul&apos; tag. Change &amp;lt;ul class=&quot;nav nav-tabs left&quot;&amp;gt; to &amp;lt;ul class=&quot;nav nav-tabs center&quot;&amp;gt;.  If the icon is not required in the tab, remove has-icon class &amp;lt;div class=&quot;horizontal-tab has-icon&quot;&amp;gt; is not needed.](../.gitbook/assets/image%20%2862%29.png)

### Horizontal boxed tabs with icon

![](../.gitbook/assets/image%20%2811%29.png)

```text
<div class="horizontal-boxed-tab has-icon">
    <ul class="nav nav-tabs left">
      <li class="nav-item "><a class="nav-link active" data-toggle="tab" href="#hb-tab-1"><span><i class="fal fa-briefcase"></i></span>Tab 1</a></li>
      <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#hb-tab-2"><span><i class="fal fa-briefcase"></i></span>Tab 2</a></li>
      <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#hb-tab-3"><span><i class="fal fa-briefcase"></i></span>Tab 3</a></li>
      <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#hb-tab-4"><span><i class="fal fa-briefcase"></i></span>Tab 4</a></li>
      <li class="nav-item"><a class="nav-link" data-toggle="tab" href="#hb-tab-5"><span><i class="fal fa-briefcase"></i></span>Tab 5</a></li>
    </ul>
    
    <!-- Tab panes -->
    <div class="tab-content">
      <div class="tab-pane active" id="hb-tab-1">
        <h3 class="tab-title">Tab 1 Content</h3>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
      </div>
      <div class="tab-pane " id="hb-tab-2">
        <h3 class="tab-title">Tab 2 Content</h3>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
      </div>
      <div class="tab-pane " id="hb-tab-3">
        <h3 class="tab-title">Tab 3 Content</h3>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
      </div>
      <div class="tab-pane " id="hb-tab-4">
        <h3 class="tab-title">Tab 4 Content</h3>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
      </div>
      <div class="tab-pane " id="hb-tab-5">
        <h3 class="tab-title">Tab 5 Content</h3>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
      </div>
    </div>
</div>
```

### Vertical tabs with icon - Default

![](../.gitbook/assets/image%20%2863%29.png)

```text
<div class="vertical-tab d-flex">
          <div class="nav-left">
            <ul class="nav nav-tabs">
              <li class="nav-item"> <a class="nav-link active" data-toggle="tab" href="#vtab1"><span><i class="fal fa-briefcase"></i></span>Tab 1</a> </li>
              <li class="nav-item"> <a class="nav-link" data-toggle="tab" href="#vtab2"><span><i class="fal fa-briefcase"></i></span>Tab 2</a> </li>
              <li class="nav-item"> <a class="nav-link" data-toggle="tab" href="#vtab3"><span><i class="fal fa-briefcase"></i></span>Tab 3</a> </li>
              <li class="nav-item"> <a class="nav-link" data-toggle="tab" href="#vtab4"><span><i class="fal fa-briefcase"></i></span>Tab 4</a> </li>
              <li class="nav-item"> <a class="nav-link" data-toggle="tab" href="#vtab5"><span><i class="fal fa-briefcase"></i></span>Tab 5</a> </li>
            </ul>
          </div>
          <!-- Tab panes -->
          <div class="tab-content">
            <div class="tab-pane container active" id="vtab1">
              <h3 class="tab-title">Tab 1</h3>
              <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled
                it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
                Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </p>
            </div>
            <div class="tab-pane container" id="vtab2">
              <h3 class="tab-title">Tab 2</h3>
              <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled
                it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
                Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </p>
            </div>
            <div class="tab-pane container" id="vtab3">
              <h3 class="tab-title">Tab 3</h3>
              <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled
                it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
                Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </p>
            </div>
            <div class="tab-pane container" id="vtab4">
              <h3 class="tab-title">Tab 4</h3>
              <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled
                it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
                Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </p>
            </div>
            <div class="tab-pane container" id="vtab5">
              <h3 class="tab-title">Tab 5</h3>
              <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled
                it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
                Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </p>
            </div>
          </div>
 </div>
```

### Vertical tabs with icon - Boxed

![](../.gitbook/assets/image%20%2873%29.png)

```text
<div class="vertical-boxed-tab has-icon d-flex">
          <div class="nav-left">
            <ul class="nav nav-tabs">
              <li class="nav-item"> <a class="nav-link active" data-toggle="tab" href="#vbtab1"><span><i class="fal fa-briefcase"></i></span>Tab 1</a> </li>
              <li class="nav-item"> <a class="nav-link" data-toggle="tab" href="#vbtab2"><span><i class="fal fa-briefcase"></i></span>Tab 2</a> </li>
              <li class="nav-item"> <a class="nav-link" data-toggle="tab" href="#vbtab3"><span><i class="fal fa-briefcase"></i></span>Tab 3</a> </li>
              <li class="nav-item"> <a class="nav-link" data-toggle="tab" href="#vbtab4"><span><i class="fal fa-briefcase"></i></span>Tab 4</a> </li>
              <li class="nav-item"> <a class="nav-link" data-toggle="tab" href="#vbtab5"><span><i class="fal fa-briefcase"></i></span>Tab 5</a> </li>
            </ul>
          </div>
          <!-- Tab panes -->
          <div class="tab-content">
            <div class="tab-pane container active" id="vbtab1">
              <h3 class="tab-title">Tab 1</h3>
              <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled
                it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
                Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </p>
            </div>
            <div class="tab-pane container" id="vbtab2">
              <h3 class="tab-title">Tab 2</h3>
              <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled
                it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
                Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </p>
            </div>
            <div class="tab-pane container" id="vbtab3">
              <h3 class="tab-title">Tab 3</h3>
              <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled
                it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
                Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </p>
            </div>
            <div class="tab-pane container" id="vbtab4">
              <h3 class="tab-title">Tab 4</h3>
              <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled
                it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
                Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </p>
            </div>
            <div class="tab-pane container" id="vbtab5">
              <h3 class="tab-title">Tab 5</h3>
              <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled
                it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of
                Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </p>
            </div>
          </div>
        </div>
```

