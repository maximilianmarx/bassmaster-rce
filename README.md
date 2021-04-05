# bassmaster-rce
Exploiting CVE-2014-7205 by injecting arbitrary JavaScript resulting in Remote Code Execution.

I stumbled across this [Post by LuuPhu](https://luuphu25.github.io/posts/bassmaster_nodejs_cve/) (written in viatnamese). Since I have written some code in NodeJS but never came across exploiting it, I figured why not today?

The Python PoC includes two ways of reverse shells:
1) A simple NC reverse shell
2) A "simple" NodeJS reverse shell taken from [Riyaz Walikar's ibreak.software](https://ibreak.software/2016/08/nodejs-rce-and-a-simple-reverse-shell/)

