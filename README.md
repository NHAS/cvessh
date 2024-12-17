# Golang SSH

This repo is a slightly modified version of the golang stdlib SSH library. 
The modifications allow you to exploit the recently discovered `CVE-2024-45337` by changing how the client ssh code negotiates keys.

Please visit https://github.com/NHAS/CVE-2024-45337-POC for an example of how to use this 