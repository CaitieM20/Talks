## Building the Halo 4 Services with Orleans
Given at QCon London 2015 [[Video](https://www.infoq.com/presentations/halo-4-orleans)] [[Slides](https://speakerdeck.com/caitiem20/qcon-london-2015-building-the-halo-4-services-with-orleans)]

### Summary
Caitie McCaffrey does an overview of Orleans, the challenges faced when building the Halo 4 services, and why the Actor Model and Orleans in particular were utilized to solve these problems.

## Architecting and Launching the Halo 4 Services
Given as a the evening Keynote at SRECon 2015 [[Video](https://www.usenix.org/conference/srecon15/program/presentation/mccaffrey)] [[Slides](https://speakerdeck.com/caitiem20/architecting-and-launching-the-halo-4-services-sre-con-15)]

### Abstract
Halo 4 is a first-person shooter on the Xbox 360, with fast-paced, competitive gameplay. To complement the code on disc, a set of services were developed and deployed in Azure to store player statistics, display player presence information, deliver daily challenges, modify playlists, catch cheaters, and more.  As of June 2013, Halo 4 had 11.6 million players who played 1.5 billion games, logging 270 million hours of gameplay.

The Halo 4 services were built from the ground up to support high demand, low latency, and high availability.  In addition, video games have unique load patterns where the majority of the traffic and sales occurs within the first few weeks after launch, making this a critical time period for the game and supporting services. Halo 4 went from 0 to 1 million users on day 1, and 4 million users within the first week.

This talk will discuss the architectural challenges faced when building these services and how they were solved using Windows Azure and Project Orleans. In addition, we'll discuss the path to production, some of the difficulties faced, and the tooling and practices that made the launch successful.

