# Ubuntu Frame on YOUR hands 워크숍 예제 코드

electron 시작 튜토리얼 코드입니다.

### 앱 테스트
```
npm install
WAYLAND_DISPLAY=wayland-99 ubuntu-frame   # Wayland 스크린 시뮬레이터 실행 (wayland-99 소켓을 생성)

export WAYLAND_DISPLAY=wayland-99
npm start -- --enable-features=UseOzonePlatform --ozone-platform=wayland
```
