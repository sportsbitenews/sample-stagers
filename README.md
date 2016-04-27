# sample-stagers

Staging is the process of ingesting your application source code into Apcera and making sure that all its dependencies are met. A stager is a job in Apcera that's responsible for some part of the staging process, such as running the source code through a test suite, or checking for a virus. A staging pipeline is a collection of stagers that run in a specified order.

The end result of the staging process is a package, a collection of binary data (your application source code, for instance) and metadata. A package could represent a specific version of Ubuntu, a Java runtime, a capsule snapshot, a Ruby on Rails application, or a Bash script, to name a few.

These sample stagers show how to create stagers for different purposes in the Apcera Plaform.

Each sample is licensed under the MIT license unless otherwise specified.
