---
title: scrollTime
---

Determines how far forward the scroll pane is initially scrolled.

<div class='spec' markdown='1'>
[Duration](duration-object), *default*: `'06:00:00'` (6am)
</div>

The user will be able to scroll back to see events before this time. If you want to prevent users from doing this, use the [minTime](minTime) option instead.

Example:


var date = new Date();
var now = d.getTime();
var calendar = new Calendar(calendarEl, {
  scrollTime: now,
});
