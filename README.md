# cayzn_test

## Notes

### Feature 1

To construct the itinerary, I assumed that the legs array is not particularly ordered, meaning the first leg in legs is not necessarily the origin. This is why I opted for a general solution to get the itinerary even for unordered legs.

I also assumed that the start and destination station will be repeated one time across all legs.

**ASSUMPTION BASED ON:** Legs in a service are properly defined, without inconsistencies.

_Note:_ For the rest of the features, I assumed that the legs are actually sorted based on this hint: "You can use the `itinerary` property to find the index of the matching legs."
