#Distributed System Course List




##Systems

* <a href="http://www.cs.cornell.edu/Courses/cs614/2007fa/">Cornell CS 614 - Advanced Course in Computer Systems</a> - Ken Birman teaches this course. The readings cover more distributed systems research than is typical (which I am in favour of!). In fact, there's barely anything on traditional internal OS topics like filesystems or memory management. There's some worthwhile commentary at the bottom of the page.

* <a href="http://www.cs.princeton.edu/courses/archive/fall05/cos518/">Princeton COS 518 - Advanced Operating Systems</a> - short and snappy reading list of two papers per topic, covering some interesting stuff like buffering inside the operating system, and L4. 

* <a href="http://www.stanford.edu/class/cs240/">Stanford CS240 - Advanced Topics in Operating Systems</a> - an interesting and concise set of readings. A presentation on Firefox internals is a course-specific highlight.

* <a href="http://www.eecs.harvard.edu/~mema/courses/cs264/cs264.html">Harvard CS264 - Peer-to-Peer Systems</a> - No notes but a useful collection of papers surveying from CAN and Chord to Skype.

* <a href="http://www.cs.washington.edu/education/courses/552/07sp/">CSE 552 - Distributed Systems</a> - University of Washington graduate distributed systems course. Thoughtfully selected readings.

* <a href="http://www.cs.cmu.edu/~15712/">CMU 15-712 - Advanced and Distributed Operating Systems</a>

* <a href="http://www.cs.uiuc.edu/class/sp09/cs525/sched.htm">UIUC CS 525 - Advanced Distributed Systems</a> - long list of readings, drawn mostly from the last ten years or so, focusing on applications.

* <a href="http://www.cs.cornell.edu/courses/cs6452/2012sp/lectures.php">Cornell CS6452 - Datacenter Networks and Services</a> - networking focused - but by no means exclusively.


##Databases

* <a href="http://www.cs.brown.edu/courses/cs227/papers.html">Brown CSCI 2270 - Advanced Topics in Database Management</a> - no notes but a good set of * <a href="http://www.cs.brown.edu/courses/cs227/papers.html">readings</a>. Does a good job of categorising the last ~15 years of distributed and parallel database research which has moved away from shared-something RDBMSs.



##Distributed Algorithms

* <a href="http://courses.csail.mit.edu/6.852/08/">MIT 6.852 - Distributed Algorithms</a> - Goodish lecture slides, detailed but manageable set of readings and some homework problems. Lectured by Professor Lynch at MIT, who literally wrote the book on the subject.

* <a href="http://citeseer.ist.psu.edu/120246.html">Distributed Algorithms Lecture Notes</a> - Very readable set of lecture notes on distributed algorithms, for a course given in 1993 at the Technion in Israel (I think).


* <a href="http://courses.csail.mit.edu/6.885/spring06/">MIT 6.885 - Distributed Algorithms for Mobile Wireless Ad-Hoc Networks</a> - One of the only courses on this particular niche subject. Taught simultaneously by Jennifer Welch and Nancy Lynch. Notes are very good, reading lists is very comprehensive and there are also some good handouts!




##Data Structures and Algorithms


* <a href="http://dspace.mit.edu/html/1721.1/36897/6-854JFall-1999/OcwWeb/Electrical-Engineering-and-Computer-Science/6-854JAdvanced-AlgorithmsFall1999/LectureNotes/index.htm">MIT 6.854J (OCW) - Advanced Algorithms</a> - A good first course after familiarity with Cormen et. al. is achieved. Topics include competitive queues, splay trees, six lectures on flow algorithms, linear programming and computational geometry. Lecturer's own notes are sparse, but the scribed notes are very useful.

* <a href="http://courses.csail.mit.edu/6.851/spring07/lec.html">MIT 6.851 - Advanced Data Structures</a> - supercedes the below course I think, both taught by the legendary Erik Demaine. Worth keeping the below one around as well, since the notes are slightly different as are the topics covered.

* <a href="http://courses.csail.mit.edu/6.897/spring05/index.html">MIT 6.897 - Advanced Data Structures</a> - good coverage of advanced topics including dynamic graphs, succinct data structures and data structures for integers. Scribe notes are excellent, lecturer's own hand-written notes less so.

* <a href="http://ttic.uchicago.edu/~prahladh/teaching/05spring/">Chicago CS369E - Expanders in Computer Science</a> - graduate level course on expander graphs and their applications to computer science. Notes are excellent.

* <a href="http://www.courses.fas.harvard.edu/~cs225/Lectures/">Harvard CS225 - Pseudorandomness</a> - good scribe notes, covers randomized algorithms, quite a lot on expander graphs etc.

* <a href="http://www.cs.yale.edu/homes/spielman/eigs/">Yale 500A - Spectral Graph Theory and its Applications</a> - slightly rambling but clear and interesting lecturer written notes.

* <a href="http://www.cs.uiuc.edu/homes/chekuri/teaching/spring2008/agt.htm">UIUC CS573: Algorithmic Game Theory</a> - good scribe notes and a pointer to a massive online text book.

* <a href="http://www.cs.cornell.edu/Courses/cs683/2001SP/Default.htm">Cornell CS683 - Advanced Algorithms</a> - detailed web page, notes and readings. Focus is on approximation algorithms, linear programming and randomisation.

* <a href="http://pages.cs.wisc.edu/~shuchi/courses/787-F07/">Wisconsin CS787 - Advanced Algorithms</a> - decent notes and readings. Linear programming, network flows, approximation and randomisation, plus some interesting stuff on online algorithms.

* <a href="http://compgeom.cs.uiuc.edu/~jeffe/teaching/373/">UIUC CS 373 - Combinatorial Algorithms</a> - a senior undergraduate course in mainly advanced topics from CLRS with outstanding notes.


##Discrete Mathematics and Probability


* <a href="http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/">MIT 6.042J (OCW)</a> - Elementary discrete maths, including graph theory and some combinatorics. Lecture slides are available, and good, but the real meat is in the readings.




#Paper List




##Thought Provokers

Ramblings that make you think about the way you design.  Not everything can be solved with big servers, databases and transactions.


* <a href="http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.33.411">Harvest,
Yield and Scalable Tolerant Systems</a>- Real world applications of
CAP from Brewer et al

* <a href="http://research.microsoft.com/~jamesrh/TalksAndPapers/JamesRH_Lisa.pdf">On Designing and Deploying Internet Scale Services</a> - James Hamilton

* <a href="http://www.addsimplicity.com/adding_simplicity_an_engi/2007/02/latency_exists_.html">Latency Exists, Cope!</a>
- Commentary on coping with latency and it's architectural impacts

* <a href="http://www.igvita.com/2012/07/19/latency-the-new-web-performance-bottleneck/">Latency - the new web performance bottleneck</a> - not at all new (see * <a href="http://dl.acm.org/citation.cfm?id=1022596">Patterson</a>), but noteworthy

* <a href="http://www.addsimplicity.com/adding_simplicity_an_engi/2006/12/the_perils_of_g.html">The Perils of Good Abstractions</a>- Building the perfect API/interface is difficult

* <a href="http://www.addsimplicity.com/adding_simplicity_an_engi/2007/05/chaotic_perspec.html">Chaotic Perspectives</a>
- Large scale systems are everything developers dislike - unpredictable, unordered and parallel

* <a href="http://poorbuthappy.com/ease/archives/2007/04/29/3616/the-top-10-presentation-on-scaling-websites-twitter-flickr-bloglines-vox-and-more">Website Architecture</a>
- A collection of scalable architecture papers from various of the large websites

* <a href="http://www.cidrdb.org/cidr2005/papers/P12.pdf">Data on the Outside versus Data on the Inside</a> - Pat Helland	

* <a href="http://blogs.msdn.com/pathelland/archive/2007/05/15/memories-guesses-and-apologies.aspx">Memories, Guesses and Apologies</a> - Pat Helland

* <a href="http://blogs.msdn.com/pathelland/archive/2007/05/20/soa-and-newton-s-universe.aspx">SOA and Newton's Universe</a> - Pat Helland

* <a href="http://arxiv.org/abs/0909.1788">Building on Quicksand</a> - Pat Helland

* <a href="http://www.artima.com/weblogs/viewpost.jsp?thread=4247">Why Distributed Computing?</a> - Jim Waldo

* <a href="http://research.sun.com/techrep/1994/abstract-29.html">A Note on Distributed Computing</a> - Waldo, Wollrath et al

* <a href="https://plus.google.com/112678702228711889851/posts/eVeouesvaVX">Stevey's Google Platforms Rant</a> - Yegge's SOA platform experience


##Amazon

Somewhat about the technology but more interesting is the culture and organization they've created to work with it.


* <a href="http://queue.acm.org/detail.cfm?id=1142065">A Conversation with Werner Vogels</a> - Coverage of Amazon's transition to a service-based architecture

* <a href="http://queue.acm.org/detail.cfm?id=1388773">Discipline and Focus</a> - Additional coverage of Amazon's transition to a service-based architecture

* <a href="http://www.itconversations.com/shows/detail1634.html">Vogels on Scalability</a>

* <a href="http://searchwebservices.techtarget.com/originalContent/0,289142,sid26_gci1195702,00.html">SOA creates order out of chaos @ Amazon</a>


##Google

Current "rocket science" in distributed systems.


* <a href="http://research.google.com/archive/mapreduce.html">MapReduce</a>

* <a href="http://research.google.com/archive/chubby.html">Chubby Lock Manager</a>

* <a href="http://research.google.com/archive/gfs.html">Google File System</a>

* <a href="http://research.google.com/archive/bigtable.html">BigTable</a>

* <a href="http://www.usenix.org/event/worlds06/tech/prelim_papers/perl/perl.pdf">Data Management for Internet-Scale Single-Sign-On</a>

* <a href="http://research.google.com/pubs/pub36632.html">Dremel: Interactive Analysis of Web-Scale Datasets</a>

* <a href="http://research.google.com/pubs/pub36726.html">Large-scale Incremental Processing Using Distributed Transactions and Notifications</a>

* <a href="http://www.cidrdb.org/cidr2011/Papers/CIDR11_Paper32.pdf">Megastore: Providing Scalable, Highly Available Storage for Interactive Services</a> - Smart design for low latency Paxos implementation across datacentres.

* <a href="http://research.google.com/archive/spanner.html">Spanner</a> - Google's scalable, multi-version, globally-distributed, and synchronously-replicated database.

* <a href="http://research.google.com/pubs/pub41318.html">Photon</a> -  Fault-tolerant and Scalable Joining of Continuous Data Streams. Joins are tough especially with time-skew, high availability and distribution.

* <a href="http://research.google.com/pubs/pub42851.html">Mesa: Geo-Replicated, Near Real-Time, Scalable Data Warehousing</a> - Data warehousing system that stores critical measurement data related to Google's Internet advertising business.


##eBay

Interesting they dumped most of J2EE and use a lot of db partitioning.  Check out their site upgrade tool as well.


* <a href="http://www.addsimplicity.com.nyud.net:8080/downloads/eBaySDForum2006-11-29.pdf">SD Forum 2006</a>


##Consistency Models

Key to building systems that suit their environments is finding the right tradeoff between consistency and availability.


* <a href="http://citeseer.ist.psu.edu/544596.html">CAP Conjecture</a> - Consistency, Availability, Parition Tolerance cannot all be satisfied at once

* <a href="http://www.cs.utexas.edu/users/princem/papers/cac-tr.pdf">Consistency, Availability, and Convergence</a> - Proves the upper bound for consistency possible in a typical system

* <a href="http://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed">CAP Twelve Years Later: How the "Rules" Have Changed</a> - Eric Brewer expands on the original tradeoff description

* <a href="http://www.infoq.com/news/2008/01/consistency-vs-availability">Consistency and Availability</a> - Vogels

* <a href="http://www.allthingsdistributed.com/2007/12/eventually_consistent.html">Eventual Consistency</a> - Vogels

* <a href="http://www.addsimplicity.com/adding_simplicity_an_engi/2006/12/avoiding_two_ph.html">Avoiding Two-Phase Commit</a>
- Two phase commit avoidance approaches

* <a href="http://www.addsimplicity.com/adding_simplicity_an_engi/2006/12/2pc_or_not_2pc_.html">2PC or not 2PC, Wherefore Art Thou XA?</a>
- Two phase commit isn't a silver bullet

* <a href="http://blogs.msdn.com/pathelland/archive/2007/05/16/link-to-life-beyond-distributed-transactions-an-apostate-s-opinion.aspx">Life Beyond Distributed Transactions</a>
- Helland
* <a href="http://queue.acm.org/detail.cfm?id=1953140">If you have
too much data, then 'good enough' is good enough</a> - NoSQL,
Future of data theory - Pat Helland

* <a href="http://www.enterpriseintegrationpatterns.com/docs/IEEE_Software_Design_2PC.pdf">Starbucks doesn't do two phase commit</a> - Asynchronous mechanisms at work

* <a href="http://codahale.com/you-cant-sacrifice-partition-tolerance/">You Can't Sacrifice Partition Tolerance</a> - Additional CAP commentary

* <a href="http://www.ysaito.com/survey.pdf">Optimistic Replication</a> - Relaxed consistency approaches for data replication


##Theory

Papers that describe various important elements of distributed systems design.


* <a href="http://research.microsoft.com/research/pubs/view.aspx?tr_id=655">Distributed Computing Economics</a> - Jim Gray

* <a href="http://research.microsoft.com/pubs/68636/ms_tr_99_100_rules_of_thumb_in_data_engineering.pdf">Rules of Thumb in Data Engineering</a> - Jim Gray and Prashant Shenoy

* <a href="http://en.wikipedia.org/wiki/Fallacies_of_Distributed_Computing">Fallacies of Distributed Computing</a> - Peter Deutsch

* <a href="http://doi.acm.org/10.1145/3149.214121">Impossibility of distributed consensus with one faulty process</a> - also known as FLP [access requires account and/or payment, a free version can be found * <a href="http://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf">here</a>]

* <a href="http://citeseer.ist.psu.edu/356748.html">Unreliable Failure Detectors for Reliable Distributed Systems.</a> A method for handling the challenges of FLP

* <a href="http://research.microsoft.com/users/lamport/pubs/time-clocks.pdf">Lamport Clocks</a> - How do you establish a global view of time when each computer's clock is independent

* <a href="http://research.microsoft.com/users/lamport/pubs/byz.pdf">The Byzantine Generals Problem</a>

* <a href="http://citeseer.nj.nec.com/ladin90lazy.html">Lazy Replication: Exploiting the Semantics of Distributed Services</a>

* <a href="http://www.usenix.org/event/hotdep10/tech/full_papers/Kapritsos.pdf">Scalable Agreement - Towards Ordering as a Service</a>

* <a href="http://arxiv.org/pdf/1307.3207v1.pdf">Scalable Eventually Consistent Counters over Unreliable Networks</a> - Scalable counting is tough in an unreliable world


##Languages and Tools

Issues of distributed systems construction with specific technologies.


* <a href="http://docmanual.com/Read/_vp.bWFuLmx1cGF3b3JsZC5jb20-_vp..sl_content.sl_develop.sl_p37-svensson.pdf">Programming Distributed Erlang Applications: Pitfalls and Recipes</a> - Building reliable distributed applications isn't as simple as merely choosing Erlang and OTP.



##Infrastructure

* <a href="http://queue.acm.org/detail.cfm?id=1773943">Principles of Robust Timing over the Internet</a> - Managing clocks is essential for even basics such as debugging


##Storage

* <a href="http://www.akamai.com/dl/technical_publications/ConsistenHashingandRandomTreesDistributedCachingprotocolsforrelievingHotSpotsontheworldwideweb.pdf">Consistent Hashing and Random Trees</a>

* <a href="http://www.allthingsdistributed.com/2007/10/amazons_dynamo.html">Amazon's Dynamo Storage Service</a>


##Paxos Consensus

Understanding this algorithm is the challenge.  I would suggest reading "Paxos Made Simple" before the other papers and again afterward.


* <a href="http://research.microsoft.com/users/lamport/pubs/lamport-paxos.pdf">The Part-Time Parliament</a> - Leslie Lamport

* <a href="http://research.microsoft.com/users/lamport/pubs/paxos-simple.pdf">Paxos Made Simple</a> - Leslie Lamport

* <a href="http://static.googleusercontent.com/media/research.google.com/en/us/archive/paxos_made_live.pdf">Paxos Made Live - An Engineering Perspective</a> - Chandra et al

* <a href="http://groups.csail.mit.edu/tds/paxos.html">Revisiting the Paxos Algorithm</a> - Lynch et al

* <a href="http://research.microsoft.com/lampson/58-Consensus/Acrobat.pdf">How to build a highly available system with consensus</a> - Butler Lampson

* <a href="http://research.microsoft.com/en-us/um/people/lamport/pubs/reconfiguration-tutorial.pdf">Reconfiguring a State Machine</a> - Lamport et al - changing cluster membership

* <a href="http://citeseer.ist.psu.edu/viewdoc/summary?doi=10.1.1.20.4762">Implementing Fault-Tolerant Services Using the State Machine Approach: a Tutorial</a> - Fred Schneider


Other Consensus Papers


* <a href="http://www.usenix.org/event/osdi08/tech/full_papers/mao/mao_html/">Mencius: Building Efficient Replicated State Machines for WANs</a> - consensus algorithm for wide-area network


##Gossip Protocols (Epidemic Behaviours)


* <a href="http://roland.grc.nasa.gov/~weddy/biblio/epidemic/">Epidemic Routing Bibliography</a>

* <a href="http://infoscience.epfl.ch/record/109302?ln=en">How robust are gossip-based communication protocols?</a>

* <a href="http://www.cs.cornell.edu/home/rvr/papers/astrolabe.pdf">Astrolabe: A Robust and Scalable Technology For Distributed Systems Monitoring, Management, and Data Mining</a>

* <a href="http://www.allthingsdistributed.com/historical/archives/000456.html">Epidemic Computing at Cornell</a>

* <a href="http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.5.4000">Fighting Fire With Fire: Using Randomized Gossip To Combat Stochastic Scalability Limits</a>

* <a href="http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.17.7959">Bi-Modal Multicast</a>

* <a href="http://dl.acm.org/citation.cfm?id=1317379">ACM SIGOPS Operating Systems Review - Gossip-based computer networking</a>

* <a href="http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.18.9737">SWIM: Scalable Weakly-consistent Infection-style Process Group Membership Protocol</a>


##P2P


* <a href="http://pdos.csail.mit.edu/chord/papers/paper-ton.pdf">Chord</a>: A Scalable Peer-to-peer Lookup Protocol for Internet Applications

* <a href="http://www.cs.rice.edu/Conferences/IPTPS02/109.pdf">Kademlia</a>: A Peer-to-peer Information System Based on the XOR Metric

* <a href="http://research.microsoft.com/en-us/um/people/antr/PAST/pastry.pdf">Pastry</a>: Scalable, decentralized object location and routing for large-scale peer-to-peer systems

* <a href="http://research.microsoft.com/en-us/um/people/antr/PAST/hotos.pdf">PAST</a>: A large-scale, persistent peer-to-peer storage utility - storage system atop Pastry

* <a href="http://research.microsoft.com/en-us/um/people/antr/PAST/jsac.pdf">SCRIBE</a>: A large-scale and decentralised application-level multicast infrastructure - wide area messaging atop Pastry




