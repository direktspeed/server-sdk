# graaljs-server-sdk
A Polyglot Server SDK with a High Focus on JavaScript / ES2020 / ECMAScript based on graalvm
We use some Java Implamentations as they can be easy extended and build directly into the Application
and they produce more performant code most time. We Use JavaScript where it really shines in our application logic

## Features
- The Fastes JavaScript Server Runtime in the world Paired with the Fastes Distributed Key Value Store in the World
- Used as the Fundamental building block of direktspeed-serverless-platform
- Apache Ignite in Memory Key Value Store **optional** on disk storage written in JAVA
- Apache Ignite JavaScript Bridge to manage the Ignite Cluster in your Javascript application
- Can use any Language that graalvm supports in addition
- can be deployed as Single Binary or JIT Version
- vertx IO Framework for Java IO

### Apache Ignite
Ignite can be accessed with simple key-value APIs and, thus, act as a distributed key-value store (aka. data grid). In this scenario, you can think of Ignite as of a distributed partitioned hash map with every cluster node owning a portion of the overall data set. It's worth mentioning, that even if you see or use Ignite as a key-value store, you're not limited to the key-value operations and can always leverage from other available APIs such as SQL, collocated computations, machine learning, streaming.

### GraalVM
A Polyglot Compiler written in Java that can produce JIT and AOT Versions of your server Application it can run 95% of all existing NPM Packages out of the box.
