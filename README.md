sv4s3fs
=======

Signature version 4 for s3fs
<<<<<<< HEAD

This first push is a read-only(GET/HEAD) version, I am working on POST/PUT/DELETE.

shunwang@ 2014-08-15

The second update is a read-write verion (GET/HEAD/PUT/DELETE), not sure the POST/Multi-upload part now.

shunwang@ 2014-08-20


Install Guide:
1. (replace all the .cpp and .h files in original s3fs-fuse branch)
   git clone https://github.com/s3fs-fuse/s3fs-fuse.git

2. git clone https://github.com/shunataws/sv4s3fs.git

   (pre-step: sudo apt-get install libfuse-dev libxml2-dev)
   ./autogen.sh
   ./configure
   make

   cp src/s3fs to your bin dir and test if it works.

=======
>>>>>>> parent of 9b1202d... read-only version


