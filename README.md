<div align="center"><h1>Reverse Engineered PHP Shell Backdoor Collection</h1></div> 

All PHP shells are deobfuscated manually (using my hand and my brain) from many diffrent types of obfuscation like goto, Yak-Pro, eval(, halt_compiler, fopo and some others, i've spend like a year maybe to finish this project, so why don't you star and follow me :D
There are so many PHP shell backdoors that are obfuscated just to cover up that in their code there is an email logger that will automatically send the full backdoor shell url, server ip and others to the creator email, so that the creator can get a shell backdoored website for free, but some are just to protect their code from a skid :p.
and also some shells are not 100% deofuscated if there some error, blank, fix it by your self.
where did i got all the PHP shells? only god and me know it.

***tips to fix php shell that uses login function errors or goes blank:***
* try to fix the "**magic_quotes_gpc**" function
* fix the "**if(!isset($_SESSION[md5($_SERVER['HTTP_HOST'])]))**" function
* remove the "**set_magic_quotes_runtime()**"

Missing original shell? or any request to deobfuscate? let me help you, just mail me at *bapakgwheker[at]duck.com* (free)

## Disclaimer

This repository is for educational & cyber security research purposes only.
Malicious usage of this repository will not be the author responsible.
