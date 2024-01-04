# gRPC 

여기에서 띄울 파드내의 애플리케이션 컨테이너의 이미지는 

https://github.com/kimsehwan96/gRPC-python-example

위에서 빌드해서 사용했다.

## gRPC json transcoder

`envoy filter` 이용하는데, 자세한 내용은 추후에 작성

## TODO

`proto_descriptor_bin` 에 `proto descriptor` 를 base64 인코딩한걸 넣는게 아니라, 파일 마운트를 해서 넣는다던지, 뭐 좀 더 괜찮은 방법이 없을지 확인하기
