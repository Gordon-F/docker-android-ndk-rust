Android NDK Docker image with Rust specific additions. Based on [bitriseio/android-ndk](https://github.com/bitrise-io/android-ndk).

## Build image
```bash
docker build -t rust_android_ndk.image -f Dockerfile --build-arg API=21 .
```

## Run container

```bash
docker run -it --rm -v "$PWD:/home/rust/application" rust_android_ndk.image /bin/bash
```
