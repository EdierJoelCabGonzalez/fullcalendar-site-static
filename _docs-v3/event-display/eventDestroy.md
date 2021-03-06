---
title: eventDestroy
type: callback
---

Called before an event's element is removed from the DOM.

<div class='spec' markdown='1'>
function( *event*, *element*, *view* ) { }
</div>

`event` is the [Event Object](event-object)

`element` is a jQuery element that will be removed

This callback gets called once for every event element. It is a great way to tear down any plugins you might have applied in [eventRender](eventRender).
