# Ubuntu Frame on YOUR hands 워크숍 예제 코드

electron 시작 튜토리얼 코드입니다.

## 해 볼 작업

### 앱 테스트
```
npm start   # 빌드 및 실행해서 앱을 확인해봅시다

WAYLAND_DISPLAY=wayland-99 ubuntu-frame   # Wayland 스크린 시뮬레이터 실행 (wayland-99 소켓을 생성)
WAYLAND_DISPLAY=wayland-99 npm start      # 앱을 wayland-99 소켓에 붙입니다.
```

### Ubuntu Frame을 위한 snap 패키징
설명 참고
