Computer Networks : Assignment 2
---------------------------------
Socket Programming :
	Compiling code : gcc server_client.c -lcrypto -lssl
	To run code : ./a.out

After running, it asks for the host port and then next server port. These should be vice versa while running the server and client
There is a FileUploadAllow or FileUploadDeny input to be given for the permissions for uploading files


And then :
	To run commands through TCP protocol, select 0
	To run commads through UDP protocol, select 1


Commands:
	IndexGet longlist
	IndexGet shortlist {timestamp} {Example: IndexGet shortlist WedJul0909:02:262014 FriFeb0618:23:442015
	IndexGet regex <regular expression>
	FileDownload <filename>
	FileUpload <filename>
	FileHash verify <filename>
	FileHash checkall
