# TILog-OG-Image-Service

- 해당 레포지토리는 ![og-image](https://github.com/vercel/og-image)를 Fork하였습니다.

## 개요

TILog의 Post는 이미지가 없을시 PostID에 따라 기본 이미지를 제공합니다.

metadata의 OpenGraph Image를 사용하여 Post의 기본이미지를 제공하고, 다른 페이지의 OG Image또한 지원하기위해 사용합니다.

## 사용방법

```
https://og.tilog.link/텍스트 내용(markdown 사용가능).png?md=1&fontSize={폰트 사이즈(px)}&seed={postID값}&images={이미지 URL}

OR

https://og.tilog.link/ 접속

```

