##Applying the Saga Pattern
This talk was given at Craft Conf 2015 & Goto Chicago 2015.  [[Video](https://www.youtube.com/watch?v=xDuwrtwYHu8&index=46&list=PLEx5khR4g7PKFs3Y-gWd8TX4Y_5yTyUTP)] [[Slides](https://speakerdeck.com/caitiem20/applying-the-saga-pattern)]

###Abstract
As we build larger more complex applications and solutions that need to do collaborative processing the traditional ACID transaction model using coordinated 2-phase commit is often no longer suitable. More frequently we have long lived transactions or must act upon resources distributed across various locations and trust boundaries. The Saga Pattern is a useful model for long lived activities and distributed transactions without coordination.

Sagas split work into a set of transactions whose effects can be reversed even after the work has been performed or committed. If a failure occurs compensating transactions are performed to rollback the work. So at its core the Saga is a failure Management Pattern, making it particularly applicable to distributed systems.

In this talk, I'll discuss the fundamentals of the Saga Pattern, and how it can be applied to your systems. In addition we'll discuss how the Halo 4 Services successfully made use of the Saga Pattern when processing game statistics, and how we implemented it in production.
