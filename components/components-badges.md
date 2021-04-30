---
description: >-
  Small numerical value or status descriptor for UI elements. Badge normally
  appears in proximity to notifications or user avatars with eye-catching
  appeal, typically displaying unread messages count.
---

# Badge

## [Interactive demo](http://cloud.crimsonlogic.com/2021/website/jds/v1/components.html#badge-wrapper)

## Examples

Badges scale to match the size of the immediate parent element by using relative font sizing and em units.

![](../.gitbook/assets/image%20%2885%29.png)

```text
<h3>Example heading <span class="badge badge-primary">New</span></h3>
```

### For notification count or new notification

Unread messages count or new message notification appears close to button or icon.

![Used for record count in Tabs](../.gitbook/assets/image%20%287%29.png)

```text
<span class="badge badge-primary">04</span>
<!--Notifications-->
<a href="javascript:void(0);" class="notification" title="Notification"> 
<i class="fal fa-bell"></i> <sup>1</sup>
</a>
 <span class="mx-3"></span> 
<a href="javascript:void(0);" class="notification has-notification" title="Notification">
<i class="fal fa-bell"></i>
</a>
```

### To indicate the status

Appears next to user avatars with eye-catching appeal. Status shown below are Available, Away, Busy and Offline.

![](../.gitbook/assets/image%20%2824%29.png)

```text
<a href="javascript:void(0);" class="user-status available" title="Available">
	<i class="fas fa-user"></i>
</a>

<a href="javascript:void(0);" class="user-status away" title="Away">
	<i class="fas fa-user"></i>
</a>

<a href="javascript:void(0);" class="user-status busy" title="Busy">
	<i class="fas fa-user"></i>
</a>

<a href="javascript:void(0);" class="user-status offline" title="Offline">
	<i class="fas fa-user"></i>
</a>
```

### When to use

#### Can be used to

"Stamp" another piece of UI, such as an Avatar, a text title or inside a button

* When an element needs to be highlighted or two items need to be differentiated from each other.

#### Should not be used

* Do not use too long labels or whole sentences.
* Avoid numbers longer than 3 digits when possible.



