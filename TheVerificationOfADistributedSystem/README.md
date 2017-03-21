# The Verification of a Distributed System
Accompanying Repository for The Verification of a Distributed System Talk to be given at 
* [GOTO Chicago 2016](http://gotocon.com/chicago-2016): [[Slides](https://speakerdeck.com/caitiem20/the-verification-of-a-distributed-system)][[Video](https://youtu.be/kDh5BrqiGhI?list=PLEx5khR4g7PIfvppVcaTPa5IKWTjoASRU)] 
* [Qcon New York 2016](https://qconnewyork.com/ny2016/presentation/verification-distributed-system) [[Slides](https://speakerdeck.com/caitiem20/qcon-newyork-2016-the-verification-of-a-distributed-system)][[Video](https://www.infoq.com/presentations/distributed-systems-verification)]
* [YOW Melbourne 2016](http://melbourne.yowconference.com.au/) [[Slides](https://speakerdeck.com/caitiem20/the-verification-of-a-distributed-system-1)]
* [YOW Brisbane 2016](http://brisbane.yowconference.com.au/) [[Slides](https://speakerdeck.com/caitiem20/the-verification-of-a-distributed-system-2)] 
* [YOW Sydney 2016](http://sydney.yowconference.com.au/) [[Slides](https://speakerdeck.com/caitiem20/the-verification-of-a-distributed-system-3)]

## Abstract
Distributed Systems are difficult to build and test for two main reasons: partial failure & asynchrony.  These two realities of distributed systems must be addressed to create a correct system, and often times the resulting systems have a high degree of complexity.  Because of this complexity, testing and verifying these systems is critically important.  In this talk we will discuss strategies for proving a system is correct, like formal methods, and less strenuous methods of testing which can help increase our confidence that our systems are doing the right thing.

## References
* [The Verification of a Distributed System](http://queue.acm.org/detail.cfm?id=2889274)
* Formal Specifications
  * [Specifying Systems](http://research.microsoft.com/en-us/um/people/lamport/tla/book-02-08-08.pdf)
  * [Use of Formal Methods at Amazon Web Services](http://research.microsoft.com/en-us/um/people/lamport/tla/formal-methods-amazon.pdf)
  * [The Coq Proof Assistant](https://coq.inria.fr/)
* [Simple Testing Can Prevent Most Critical Failures](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-yuan.pdf)
* Property Based Testing
  * [Haskell: Quick Check](https://hackage.haskell.org/package/QuickCheck)
  * [Erlang: Quick Check](http://www.quviq.com/products/erlang-quickcheck/)
  * [Other Quick Check Implementations](https://en.wikipedia.org/wiki/QuickCheck)
  * [ScalaCheck](https://www.scalacheck.org/)
  * [29 GIFs only ScalaCheck Witches will Understand](http://nerd.kelseyinnis.com/blog/2015/01/14/29-GIFs-only-scalacheck-witches-will-understand/)
  * [Quick Checking Riak](https://skillsmatter.com/skillscasts/4505-quickchecking-riak)
  * [Testing Eventual Consistency in Riak](https://www.youtube.com/watch?v=x9mW54GJpG0)
  * [Combining Model Checking and Testing](http://research.microsoft.com/pubs/200544/main.pdf)
  * [Testing AUTOSTAR Software with QuickCheck](http://ieeexplore.ieee.org/xpl/login.jsp?reload=true&tp=&arnumber=7107466&url=http%3A%2F%2Fieeexplore.ieee.org%2Fxpls%2Fabs_all.jsp%3Farnumber%3D7107466)
  * [Modeling Eventual Consistency Databases with QuickCheck](https://vimeo.com/23220830)
  * [The Mysteries of Dropbox](https://vimeo.com/158002499)
* Fault Injection
  * [Jepsen](http://jepsen.io/)
  * [Netflix Simian Army](http://techblog.netflix.com/2011/07/netflix-simian-army.html)
  * Game Days
    * [Resilience Engineering: Learning to Embrace Failure](https://queue.acm.org/detail.cfm?id=2371297)
    * [Game Day Exercises at Stripe: Learning from `kill-9`](https://stripe.com/blog/game-day-exercises-at-stripe)
* Systems Complexity Model from [Architectural Patterns of Resillent Distributed Systems](https://github.com/Randommood/YOW2016)
* Areas of Research
  * [Cause I'm Strong Enough: Reasoning about Consistency Choices in Distributed Systems](https://pages.lip6.fr/Marc.Shapiro/papers/CISE-POPL-2016.pdf) 
    * [The CISE Tool: Proving Weakly Consistent Applications Correct](https://hal.inria.fr/hal-01279495v1/document)
    * [CISE Tool Demo](https://www.youtube.com/watch?v=HJjWqNDh-GA)
    * [Github: Syncfree/CISE](https://github.com/SyncFree/CISE)
    * [Syncfree CISE website](https://syncfree.lip6.fr/index.php/2-uncategorised/51-cise)
 * [IronFleet: Proving Practical Distributed Systems Correct](http://research.microsoft.com/apps/pubs/default.aspx?id=255833)
   * [Dafny](http://research.microsoft.com/en-us/projects/dafny/)
 * Lineage-Driven Fault Injection aka Molly
    * [Lineage-Driven Fault Injection](http://people.ucsc.edu/~palvaro/molly.pdf)
    * [Sigmod 2015 Slides](http://www.slideshare.net/palvaro/lineagedriven-fault-injection-sigmod15)
    * [Automated Failure Testing at Netflix](http://techblog.netflix.com/2016/01/automated-failure-testing.html)
    * ["Monkeys in Lab Coats": Applied Failure Testing Research at Netflix](http://www.infoq.com/presentations/failure-test-research-netflix)
    * [Automating Failure Testing Research at Internet Scale](https://people.ucsc.edu/~palvaro/socc16.pdf)
    * [Orchestrated Chaos: Applying Failure Testing Research at Scale](https://www.youtube.com/watch?v=QOTNBKx9Irc)
 * [Towards Property Based Consistency Verification](http://www.eurecom.fr/fr/publication/4874/download/ds-publi-4874.pdf)
 * [Certified Causally Consistent Distributed Key Value Stores](http://people.csail.mit.edu/lesani/companion/popl16/POPL16.pdf)
 * [Planning for Change in a Formal Verification of the Raft Consensus Protocol](https://homes.cs.washington.edu/~mernst/pubs/raft-proof-cpp2016.pdf)


## Bio
Caitie McCaffrey is a Backend Brat and Distributed Systems Diva at Twitter.  Prior to that she spent the majority of her career building large scale services and systems that power the entertainment industry at 343 Industries, Microsoft Game Studios, and HBO.  Caitie has a degree in Computer Science from Cornell University, and has worked on several video games including Gears of War 2, Gears of War 3, Halo 4, and Halo 5.  She maintains a blog at [CaitieM.com](https://caitiem.com/) and frequently discusses technology on Twitter [@Caitie](https://twitter.com/caitie)
