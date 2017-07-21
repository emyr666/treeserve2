# treeserve2
version 2 of treeserve. Uses memory mapped file for storage an python api for http server.

To Do
-----
* start with program to generate tree in the mapped file
* use the boost mapped file STL containers
* only need access to the root node at the first memory location
* Tree node should hold size, gid, uid, mtime, ctime and atime
* also tree node should have a map of string -> pointer to tree node for child nodes
* read in gzipped data file line by line
* for each line, create an object to represent the lstat info
* will need to decode the b64 encoded path
* store the objects in the mapped file
* write another program that can traverse the tree held in the mammped file
