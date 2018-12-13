## Context

This started as a back-on-forth discussion in a private channel where I suggested that we are slowly and surely implementing infrastructure & software, in the "Google" way. This led to a bit more research to actually write down the list of Google's contributions and influences.  Before we go here, here are some guidelines followed to write this down.

 - Direct contributions - The definition of "direct", in this context, is software that is now available and used in the public domain.

 - Influences - The definition of "influences", in this context, is ideas that have led to creation of software that is available and used in the public domain. 

 - The software must exist in the public domain under an open source license that has been approved by [OSI](https://opensource.org/).

 - Projects originating from events like Google's [Summer of Code](https://summerofcode.withgoogle.com/archive/) have been excluded as they are hard to measure and strictly speaking, cannot be classified as software that originated from within Google. 
 
 - In the same vein, other community support or contributions by Google developers to Open Source project were not assessed. 

 - Services like Youtube, Maps have had a big impact on the world but are exlcuded from this list.


## Direct Contributions

 - Android - Arguably the most popular contribution. Android is a mobile operating system, initially developed by Android Inc., acquired by Google in 2005. Android source code is available under the [Android Open Source Project (AOSP)](https://source.android.com/), and is primarily licensed under the Apache License. Android has been the best-selling OS worldwide on smartphones ([ref](https://www.statista.com/statistics/266210/number-of-available-applications-in-the-google-play-store/)).

 - Chromium OS - The developer version of Google's Chrome OS that implements the web/cloud based operating system. [Chromium OS](https://www.chromium.org/chromium-os) has formed the basis for other projects and some of the technology within the OS like [crossvm](https://chromium.googlesource.com/chromiumos/platform/crosvm/) has been used in container technology.

 - Control groups (cgroups) - Not as popular as Android but [cgroups](https://en.wikipedia.org/wiki/Cgroups) addition to the Linux kernel was an important building block in being able to run container engines like Docker.

 - AngularJS - A JavaScript-based open-source front-end web application [framework](https://github.com/angular/angular) which is maintained by Google and the community. The use of Angular has grown increasingly with lots of projects using it [ref](https://www.madewithangular.com/).

- Kubernetes - [Kubernetes](https://kubernetes.io/)(K8s) is an open-source container-orchestration platform open sourced by Google has its roots in Google's [Borg](https://ai.google/research/pubs/pub43438) and Google's learnings on Container management ([ref](https://queue.acm.org/detail.cfm?id=2898444)). 

- GoLang - Golang is a programming language, compiled, and syntactically similar to C but has some of the dynamic features of Python ([ref](https://techcrunch.com/2009/11/10/google-go-language/)). It has seen increased popularity since 2009 and is used by software such as Docker([ref](https://www.slideshare.net/jpetazzo/docker-and-go-why-did-we-decide-to-write-docker-in-go)).

- Tensorflow - TensorFlow is a programming library used for machine learning applications which Google open sourced in 2015 ([ref](https://www.wired.com/2015/11/google-open-sources-its-artificial-intelligence-engine/)).

## Influences

 - MapReduce - Google created MapReduce to manage search on a large-scale and published a [white paper](http://static.googleusercontent.com/media/research.google.com/en/us/archive/mapreduce-osdi04.pdf) describing the MapReduce programming model which then laid the foundation for Apache Hadoop ([ref] (https://books.google.co.uk/books?id=axruBQAAQBAJ&pg=PA300&redir_esc=y#v=onepage&q&f=false)). MapReduce applications has has wide applications and is incorporated into some database technologies. 

- Hbase - Similar to Mapreduce, Google's Bigtable [whitepaper](http://static.googleusercontent.com/media/research.google.com/en/us/archive/bigtable-osdi06.pdf) laid the foundation for Apache Hbase.

- Chubby - A [distributed lock service](http://static.googleusercontent.com/media/research.google.com/en/us/archive/chubby-osdi06.pdf) that was used within Google’s distributed systems led to [Apache ZooKeeper](https://zookeeper.apache.org/), the open source implementation. It is worth mentioning that ZooKeeper has evolved into other areas like metadata storage and divered from Chubby.

- Dremel - Dremel is a distributed system developed at Google for querying large datasets. It is used in Google Cloud's BigQuery service. Apache Drill was inspired by this and is a top level Apache project ([ref](https://drill.apache.org/docs/architecture-introduction/)).


## Want to change something?

There is probably more we can dig up or update. Please send a [PR](https://github.com/srirajan/google-contributions/pulls).
