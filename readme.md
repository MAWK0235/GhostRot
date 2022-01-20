FOR FUCKS SAKE STOP SUBMITTING PULL REQUESTS AND READ THE MANUAL 

## What is GhostRot ?
GhostRot is an anonymization script. GhostRot redirects all internet traffic through SOCKS5 tor proxy. DNS requests are also redirected via tor, thus preventing DNSLeak. The scripts also disables unsafe packets exiting the system. Some packets like ping request can compromise your identity.

## Build and install from source
`git clone https://github.com/TheMakeAWishKid/GhostRot.git`

`cd GhostRot`

`chmod +x build.sh`

`./build.sh`





#### Alternate method (support for previous install script)
The *install.sh* script also does the same. Its for users following old tutorials.

`git clone https://github.com/TheMakeAWishKid/GhostRot.git`

`cd GhostRot`

`chmod +x install.sh`

`./install.sh`


## Usage
GhostRot v3.0 usage:

`  -s      --start        Start GhostRot`

`  -r      --switch       Request new tor exit node`

`  -x      --stop         Stop GhostRot`

`  -h      --help         Print this help and exit`

`  -u      --update       Checks for updates`





