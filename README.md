# Squid Proxy Server
Use this image for running a Squid Proxy server
## Usage
To run the container, do the following,

```` 
     docker run -d -p <host port>:8888 -v <config file>:/etc/squid/squid.conf srpillai/squid 
````
## Example
Following is an example,

```` 
     docker run -d -p 8888:8888 -v /tmp/squid.conf:/etc/squid/squid.conf srpillai/squid 
````
