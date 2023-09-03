# Swiper + ".ion-activatable" issue reproduction

This is a reproduction of an issue with the `ion-activatable` class and the `swiper` library.

## Bug description

When using the `ion-activatable` class on an element inside a `swiper-slide` element, the "ion-activated" class is added to the element only on touch devices.

## Possible workaround

Adding the `swiper-no-swiping` class to the element with the `ion-activatable` class fixes the issue. However, it blocks the swipe gesture on the element, so it is not possible to swipe to another slide by swiping on the element.
