> Legend: [xyz] = Optional; `xyz`= comments; <> = target; ~~x~~=variable; {}=set/options
## **cURL**

1. Get main page from web-server: curl https://www.example.com:[port]/
2. Get README file from FTP server: curl ftp://ftp.example.com/README
3. get directory listing of FTP: curl ftp://ftp.example.com/
4. get a webpageee and store in a local file: curl -O https://example.com [-O https://example2/download.html `to download 2 or more files from diff pages`]
5. show headers only: curl -I https://example.com
6. get a file from FTP server: ftps://files.are.example.com/secrets.txt
7. get a file from SSH server using SFTP: curl -u username sftp://example.com/etc/issue
8. Get a file from an SSH server using SCP using a private key: curl -u username: --key ~/.ssh/id_rsa [--pass private_key_password] scp://example.com/~/file.txt
9. 
	I. verbose debug, use when curl fails when it isnt supposed to: curl -v https://example.com
	II. uTo get more details on what curl does with a given filename to log to: curl --trace my-trace.txt www.haxx.se
10. store the HTTP headers in a separate file: curl


## **find**
1. Important flags:
	1. -type: *f* for file, *d* for directory
	2. -name <>
	3. -user <>
	4. -group <>
	5. -size <>~~x~~:{b for 512-byte blocks (default),c for bytes, w for two-byte words, k for kilobytes, M for MiB, G for GiB}
	6. 2>/dev/null to silence permission errors
	7. -iname \*<>\* find a file by approximation
2.


## grep
