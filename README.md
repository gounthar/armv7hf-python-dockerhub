# armv7hf-python-dockerhub
ARM docker image that builds python from source on dockerhub

Just trying to understand why my other repo keeps getting

```
Step 2/6 : RUN [ “cross-build-start” ] ---> Running in 1263be0b5ab4 [91mstandard_init_linux.go:187: exec user process caused "exec format error" [0m Removing intermediate container 1263be0b5ab4
```

on DockerHub.
This is a fork of [armv7hf-python-dockerhub](https://github.com/petrosagg/armv7hf-python-dockerhub) that has built on DockerHub previously.
