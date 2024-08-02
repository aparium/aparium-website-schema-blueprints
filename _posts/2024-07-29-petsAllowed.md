---
layout: post
title: "petsAllowed"
categories: schema.org/Hotel
---

Indicates whether pets are allowed to enter the accommodation or lodging business. More detailed information can be put in a text value.

###### Values expected to be one of these types
- Boolean
- Text

###### Used on these types
- Accommodation
- ApartmentComplex
- FloorPlan
- LodgingBusiness


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

  <script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Hotel",
    "name": "Your Hotel Name",
  "numberOfRooms": [
    {
      "@type": "QuantitativeValue",
      "value": "45",
      "unitText": "double rooms"
    },
    {
      "@type": "QuantitativeValue",
      "value": "15",
      "unitText": "single rooms"
    }
  ],
  "petsAllowed": "true"
}
</script>
```

## Microdata Embedded in HTML

```html
<div itemscope itemtype="https://schema.org/Hotel">
  <h1><span itemprop="name">Hotel</span></h1>
  <span itemprop="description">Hotel Description</span>
  <div itemprop="numberOfRooms" itemscope itemtype="https://schema.org/QuantitativeValue">
    <span itemprop="value">45</span> <span itemprop="unitText">Room Type 1</span>
  </div>
  <div itemprop="numberOfRooms" itemscope itemtype="https://schema.org/QuantitativeValue">
    <span itemprop="value">15</span> <span itemprop="unitText">Room Type 2</span>
  </div>
  <div><meta itemprop="petsAllowed" content="true">The Property is Pet Friendly</div>
</div
```
