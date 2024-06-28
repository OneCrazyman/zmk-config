# Wireless-Corne-Xiao-ble-Zmk-Cofig-CHIPPY
원본 https://github.com/JonMuller/gerbers/tree/main/corne-choc-xiao

![image](https://github.com/OneCrazyman/zmk-config-corne-xiao-ble/assets/98089603/57fc906f-5b65-4bd2-b4d8-0308c08b06be)
![image](https://github.com/OneCrazyman/zmk-config-corne-xiao-ble/assets/98089603/d1bb61b5-abd4-4766-9269-59c22fa4c7e6)

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
