# Simple File Transfer in Socket Programming
## Description
* Files are stored in *./remote_storage*.
* Files are downloaded into *./download*.
* The file transfer process is:
  1. Server sends file list in *./remote_storage* to client.
  2. Client sends a filename to server.
  3. Server transfers the requested file to client.
  4. Get back to step 2 and loop until ".exit" is entered.
* Note that minimun error proof is provided in **most** of the time.


