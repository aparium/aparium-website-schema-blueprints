---
layout: post
title: "checkinTime"
categories: schema.org/Hotel
---

The latest someone may check out of a lodging establishment. When users find accurate check-in and check-out times easily, it streamlines their decision-making process, potentially leading to higher booking rates and better customer satisfaction.

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
