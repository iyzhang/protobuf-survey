# Protobuf survey
We are currently working to optimize serialization and deserialization for faster, kernel-bypass I/O stacks.  To better motivate our work, we'd like to get a better idea of how people use protobufs (and variants like Cap'n Proto and FlatBuffers) in their applications and some statistics about them (e.g., how many fields?, what is the most popular type of field?).

Thus, we are collecting here a repository of .proto files for studying protobuf usage. We are especially interested in protobufs that are used in the critical path (e.g., for serving requests, not for recovery, logging). Eventually, we hope to release some statistics about this collection to help other researchers in the area.

### How to add your .proto file
Create a pull request with the following:
1. A folder with the name of your application
2. Your .proto file(s) in that folder
3. A README.md to the folder with the following info:
  * What application is the protobuf(s) used for?
  * Do you use protobufs, Cap'n Proto, Flat Buffers or some other serialization library?
  * Is the application a research prototype, production system, or other?
  * Is your protobuf for network or storage serialization?
  * If possible, add a link to your code that uses the protobuf file.
  * Trademark and licensing for your protobuf code.

### Disclaimer
This is a public github repo that we will leave available to other researchers working on protobufs. By uploading your protobuf, you agree for it to be used in a research study. We will not use the code for any purpose other than data collection. PLEASE DO NOT upload non-open-source code here!!
