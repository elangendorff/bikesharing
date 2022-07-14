# Bikesharing Potential

## Overview

Conduct an analysis of a New York City bikesharing program to see how it's used and whether it shows potential for a similar program in Des Moines, Iowa.

## Resources

- CitiBike bikesharing data from August, 2019
- Tableau Public visualization software

## Results

A Tableau story visualization of August, 2019, New York City CitiBike data can be seen [here](https://public.tableau.com/app/profile/eric.langendorff/viz/CitiBikeChallenge_16575223205370/NYCCitiBike?publish=yes "link to dashboard").

### Visualization Challenges

Text elements on the Web-published story visualization do not appear in the same locations in which they were placed in the Tableau software. This is a technical issue, not a design issue, and, at this point, I do not know how to rectify it.

The text elements are, however, at least *near* where they were originally placed, and so their intent can most-likely be inferred despite their inaccurate locations.

### Effect by Gender

In general, how and when riders use CitiBike services in New York City does not appear to be greatly affected by gender. Males tend to subscribe more, but given that more than 80% of users are subscribers to begin with, it's difficult to draw any meaningful conclusion from that.

### Effect by Subscription Type

Whether a rider is a subscriber or a single-use customer, however, seems to have a much greater effect on when and how they use CitiBikes. The riding patters of the two demographics exhibit very different behaviors, with subscribers using the service mostly during weekday commute times and non-subscribers using it more on weekends.

## Summary

New York City is one of the largest tourist destinations in the World. Des Moines, Iowa, is not. As such, results from non-tourist New York City data will have much greater predictive power relating to potential expansion of CitiBike to Des Moines.

From what we can see, the most relevant variable is whether or not the customer is a subscriber.

Some additional visualizations to examine that might give further insight are:
- subscribers' time-of-use behavior by age
  - This data is the provided dataset is suspect because there are far too many riders—both subscribers and non-subscribers—that are more than 100 years old!
- proportion of one-way vs. round trips
  - This could help in understanding which trips are commute trips (more likely to be one-way) and which are tourism trips (more likely to be round trips).