# jj-social-assets

JJcompany 소셜 게시용 이미지 호스팅.

Instagram Graph API 는 로컬 파일을 받지 않고 공개 `image_url` 만 받는다
(Meta 서버가 그 주소로 이미지를 가지러 온다). 그래서 게시할 이미지를 여기에
두고 raw 주소로 공개한다.

공개 주소 형식:
```
https://raw.githubusercontent.com/copssu1124/jj-social-assets/main/images/<파일명>
```

- 공개 저장소인 이유: 어차피 인스타에 공개 게시할 홍보 이미지이고,
  Meta 서버가 로그인 없이 가져갈 수 있어야 한다.
- GitHub Pages 를 켤 필요는 없다. raw 주소가 `image/jpeg` 로 리다이렉트 없이 응답한다.
- 게시가 끝난 이미지는 지워도 된다. Meta 가 이미 자기 CDN 에 복사해 간다.
