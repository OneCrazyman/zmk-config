# Wireless-Corne-Xiao-ble-Zmk-Config-CHIPPY
원본 https://github.com/JonMuller/gerbers/tree/main/corne-choc-xiao

<img src="https://github.com/OneCrazyman/zmk-config-corne-xiao-ble/assets/98089603/57fc906f-5b65-4bd2-b4d8-0308c08b06be" width="70%" />
<img src="https://github.com/OneCrazyman/zmk-config-corne-xiao-ble/assets/98089603/d1bb61b5-abd4-4766-9269-59c22fa4c7e6" width="70%" />

### 주요 디렉토리
```
zmk-config/
├── config/
│   ├── boards/
│   │   ├── shields/
│   │   │   ├── chippy/
│   │   │   │   ├── ...
```

### build.yaml에서 경로 설정
```yaml
---
include:
  - board: seeeduino_xiao_ble
    shield: chippy_left
  - board: seeeduino_xiao_ble
    shield: chippy_right
  - board: seeeduino_xiao_ble
    shield: settings_reset    
```

### 키맵 레이어 (apply. Miryoku)
```
#define U_DEFAULT 0
#define U_LOWER   1
#define U_MEDIA   2
#define U_NAV     3
#define U_MOUSE   4
#define U_SYM     5
#define U_NUM     6
#define U_FUN     7
```
![image](https://github.com/OneCrazyman/zmk-config-corne-xiao-ble/assets/98089603/4d20a873-2447-4040-b881-b0e12f8e58d3)
