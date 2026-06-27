Drop real photos here, then wire them into the pages (see ../../README.md).

Recommended shots for Footehills of Alabama Realty:
  hero.jpg            a desirable Tennessee Valley / Decatur home
  sue.jpg             a real photo of Sue Foote / the team (owner section + about)
  decatur.jpg, hartselle.jpg, priceville.jpg, madison.jpg  town/community cards
  property-1..6.jpg   real listing photos for property cards

How to wire them in:
  - Hero: background-image on .hero__img
  - Owner: .owner__photo ; About feature also uses .owner__photo
  - Communities: replace c-1..c-4 classes with background-image
  - Property cards: replace each .property__media p-1..p-6 class with
      style="background-image:url('assets/images/property-1.jpg')"

Replace "Sue Foote · Broker/Owner" with the correct owner name/title if needed,
and connect a real MLS/IDX feed so listings stay current.
Tips: landscape orientation, ~1600px wide, compressed (JPG/WebP).
