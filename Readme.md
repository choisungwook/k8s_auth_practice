# 개요
* k8s pod 토큰 인증 연습

# pod안에서 api 요청
```sh
curl -k https://kubernetes --header "Authorization: Bearer {token}"
```