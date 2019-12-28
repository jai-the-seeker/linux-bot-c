# Simple Uploader 
### This program utilises **_curl_** library to upload the data from linux desktop to a **_php_** based server `

### Prerequisites
First update the apt and then install _curl_

```
$ sudo apt update
$ sudo apt install libcurl4-openssl-dev
```

Verify the installation and version of _curl_
```
$ curl-config --version
```

If _gcc_ toolset is not installed
```
$ sudo apt install build-essential
```

In order to compile the code link _curl library_
```
$ gcc -Wall -o https https.c -lcurl
$ ./https
```

Change settings of php.ini for uploading the files. In order to check the location of the php.ini file type following code

```
<?php echo php_ini_loaded_file(); ?>
```
