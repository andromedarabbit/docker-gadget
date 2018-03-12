[![Docker Automated build](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg)](https://hub.docker.com/r/andromedarabbit/gadget/)

# docker-gadget

k8s 환경에서 문제를 진단하거나 데이터를 추출할 때 유용한 유틸리티 도커 이미지

- `s3cmd`
- `aws`
- `vim`
- `csvkit`
- 기타

``` bash
kubectl run -it --rm test --image andromedarabbit/gadget -- bash
```

