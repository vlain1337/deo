<div align="center"><h1>Reverse Engineered PHP Shell Backdoor Collection</h1></div> 

All PHP shells are deobfuscated manually (using my hand and my brain) from many diffrent types of obfuscation like goto, Yak-Pro, eval(, halt_compiler, fopo and some others.

some shells are not 100% deofuscated if there some error, blank, fix it by your self

***tips to fix php shell that uses login function errors or goes blank:***
* try to fix the "**magic_quotes_gpc**" function
* fix the "**if(!isset($_SESSION[md5($_SERVER['HTTP_HOST'])]))**" function
* remove the "**set_magic_quotes_runtime()**"

missing original shell or any request to deobfuscate? mail me at *bapakgwheker[at]duck.com*

## Disclaimer

This repository is for educational & cyber security research purposes only.
Malicious usage of this repository will not be the author responsible.
