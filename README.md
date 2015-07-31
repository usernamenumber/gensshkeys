# Automated SSH key generator
## Overview
This is an [https://en.wikipedia.org/wiki/Expect](expect) script that automates the creation of a set of SSH keypairs.

## Requirements
The script assumes you have expect installed, which is pre-installed on OSX and many *nixes. On Debian-like Linux systems, just run `apt-get install expect` to get it if you don't already have it.

## Running the script
`./gensshkeys`

...or if that doesn't work:

`expect -f gensshkeys`
