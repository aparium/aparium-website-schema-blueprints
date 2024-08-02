---
layout: post
title: "starRating"
categories: schema.org/Hotel
---

An official rating for a lodging business or food establishment, e.g. from national associations or standards bodies. Use the author property to indicate the rating organization, e.g. as an Organization with name such as (e.g. HOTREC, DEHOGA, WHR, or Hotelstars).

###### Values expected to be one of these types
- Rating
- Text

###### Used on these types
- FoodEstablishment
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
  "starRating": {
    "@type": "Rating",
    "ratingValue": "4",
    "bestRating": "5"
  }
}
</script>

```

## Microdata Embedded in HTML

```html

<div itemscope itemtype="https://schema.org/Hotel">
  <h1><span itemprop="name">Hotel</span></h1>
  <span itemprop="description">Hotel Description</span>
  Star rating: <span itemprop="starRating" itemscope itemtype="https://schema.org/Rating">
    <meta itemprop="ratingValue" content="4">****</span>
  Room rates: <span itemprop="priceRange">$100 - $240</span>
</div>

```
