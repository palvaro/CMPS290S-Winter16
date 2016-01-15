The project requirements are very open ended, so that (I hope) each of you can undertake a project
that is directly related to your current research.  I do ask that the research contribution be "distributed"
in some way -- we can discuss exceptions to this rule if necessary.

For those of you whose research is far-removed enough from distributed systems that you are at a loss for project ideas,
here are some suggestions:

 * Make an improvement to an existing, openly-available distributed system (such as Ceph, Spark, Hadoop/HDFS, Zookeeper etc).  The improvement could be functional (add a feature) or nonfunctional (improve performance, increase reliability or recoverability, etc).  

 * Prototype a novel distributed system.  For example, create a simple key/value store, or a pub/sub messaging system, or a cluster manager, choosing a point in the design space that you can argue has not been adequately explored.

 * Analyze a distributed system, with the goal of either finding bugs or providing assurances of correctness.  There are a variety of tools available, including lineage-driven fault injection (LDFI), modeling tools such as Alloy (the system that Zave used to find bugs in Chord), model checkers such as Spin and TLA+, and automated theorem provers such as Coq and Agda.  LDFI is my own research project, so if you decide to play around with this I can provide extra support.

 * (your idea here)
