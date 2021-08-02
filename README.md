[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) ![Build and Deploy](https://github.com/solacese/faa-scds-feeds-gui/workflows/Build%20and%20Deploy/badge.svg)

# FAA SWIM Feed GUI

A browser application that implements a geo-filtering algorithm to dynamically generate topic subscriptions that attract pre-filtered sets of streaming GPS data from SCDS feeds.

This GUI displays data produced by [SWIM Feed Handler](https://github.com/solacese/swim-feed-handler), an application designed to relay messages from the FAA's publicly available US System Wide Information Management (SWIM) data feeds to a Solace PubSub+ Event Broker. The SWIM Feed Handler GitHub repository includes a thorough overview of the steps required to sign up with the FAA to receive SCDS data and to run the application locally.

## Public URL

[https://solacese.github.io/faa-scds-feeds-gui/](https://solacese.github.io/faa-scds-feeds-gui/)

## Resources

- [SWIM Flight Data Publication Service](https://www.faa.gov/air_traffic/technology/swim/sfdps/) - info about the data feeds this application uses for real-time aircraft position data
- [Topic Hierarchy and Topic Architecture Best Practices](https://solace.com/blog/topic-hierarchy-best-practices/) - a blog post dedicated to describing how to get the most out of your topic space (e.g. putting lat/lng values in the topic space enables geo-filtering).
- [Google Maps Marker Clustering](https://developers.google.com/maps/documentation/javascript/marker-clustering) - docs that help explain the aircraft marker clustering that improves map performance
- [solclientjs](https://docs.solace.com/API-Developer-Online-Ref-Documentation/nodejs/readme.html) - docs for Solace's native JavaScript API

**Original repo here: https://github.com/solacese/faa-scds-feeds-gui**