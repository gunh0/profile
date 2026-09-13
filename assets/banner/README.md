# LinkedIn banner

- `banner.html` : 소스 (1584×396, 시스템 폰트 Helvetica Neue / SF Mono 사용)
- `banner.png` : 2배 해상도 렌더링 결과 (3168×792)

렌더링:

```sh
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless --disable-gpu \
  --hide-scrollbars --window-size=1584,396 --force-device-scale-factor=2 \
  --virtual-time-budget=2000 --screenshot=banner.png "file://$PWD/banner.html"
```

프로필 사진이 좌측 하단에 겹치므로 모든 요소는 우측 정렬, 좌측 하단은 비워 둔다.
