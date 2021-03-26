# test-container-volumes

Just a simple container that runs the ls command so you can test your volume maps. Does exactly as it says.

Usage: 
```
docker run -v /tmp/my-host-vol:/tmp/my-container-vol leviharrison/test-volumes /tmp/my-container-vol -l
```
