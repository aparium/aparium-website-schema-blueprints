---
layout: post
title: "numberOfRooms"
categories: schema.org/Hotel
---

The number of rooms (excluding bathrooms and closets) of the accommodation or lodging business. Typical unit code(s): ROM for room or C62 for no unit. The type of room can be put in the unitText property of the QuantitativeValue.

Values expected to be one of these types:
Number
QuantitativeValue



## JSON-LD Code Snippet

```html

<script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Hotel",
    "name": "Your Hotel Name",
    "checkinTime": "15:00:00",
    "checkoutTime": "11:00:00"
  }
  </script>

```

## Microdata Embedded in HTML

```html

<div itemscope itemtype="https://schema.org/Hotel">
  <h1><span itemprop="name">Your Hotel Name</span></h1>
  Check-in: <meta itemprop="checkinTime" content="15:00:00">3:00 PM
  Check-out: <meta itemprop="checkoutTime" content="11:00:00">11:00 AM
</div>

```
