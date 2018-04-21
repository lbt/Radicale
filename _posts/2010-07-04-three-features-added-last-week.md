---
layout: page
title: Three Features Added Last Week
---

Some features have been added in the git repository during the last weeks,
thanks to Jerome and Mariusz!

Personal Calendars
  Calendars accessed through the htpasswd ACL module can now be
  personal. Thanks to the ``personal`` option, a user called ``bob`` can access
  calendars at ``/bob/*`` but not to the ``/alice/*`` ones.

HEAD Requests
  Radicale can now answer HEAD requests. HTTP headers can be retrieved thanks
  to this request, without getting contents given by the GET requests.

Last-Modified HTTP header
  The Last-Modified header gives the last time when the calendar has been
  modified. This is used by some clients to cache the calendars and not
  retrieving them if they have not been modified.