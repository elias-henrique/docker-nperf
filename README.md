# nPerf-Server-Docker-Version
A docker version for nPerf servers network
you can try on :  https://www.nperf.com/pt/?sp=6219

# english
if your need join to nperf speedtest
this image will be useful

when done you can try the test on : 
https://server-check.nperf.com/


# build 
docker  build  -t  sirio_nperf_img  .

# run
docker run --name=sirionperf_run -d -p 8080:8080 -p 8443:8443 -p 80:8080 -p 443:8443  sirio_nperf_img 

