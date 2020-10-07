# protobuf-survey
We are currently working to optimize protobufs for faster, kernel-bypass I/O stacks.  To bettaer motivate our work, we'd like to get a better idea of how people use protobufs in their applications and some statistics about them (e.g., how many fields?, what is the most popular type of field?).

Thus, we are collecting here a repository of .proto files for studying protobuf usage. We are especially interested in protobufs that are used in the critical path (e.g., for serving requests, not for recovery, logging). Eventually, we hope to release some statistics about this collection to help other researchers in the area.

### How to add your .proto file
1. Create a new folder
2. Add .proto file(s)
3. Add a README.md to the folder with the following info:
  * What application is the protobuf(s) used for?
  * Is the application a research prototype, production system, or other?
  * Is your protobuf for network or storage?
  * If possible, add a link to your code that uses the protobuf file
4. Submit a pull request

### Disclaimer
This is a public github repo that we will leave available to other researchers working on protobufs. PLEASE DO NOT upload non-open-source code here!!
