# M65 PCB Design

根據Mtto3所提供的外殼圖紙設計出PCB。

## PCB Features Requested

1. RGB underglow
2. STM32 based MCU
3. Support Via/QMK
4. ESD protection
5. Perkey RGB
6. Power Lighting Indicator

## Development Roadmap
0.  確認Feature Request, 提供PCB dimension(2週) 
1. 測試RGB Matrix功能(預估時程2個月)

    - 開發RGB breakout board(一週)
        - RGB Matrix使用IS31FL3731-QF作為RGB的i2c控制介面

    - 利用STM32測試板測試QMK功能(兩週) 

    預期測試可能遇到的問題
    - STM32F042 Flash大小不足(需要額外買EEPROM)(Debug 抓一個月)
2. 功能皆測試完成，移植原本電路圖，以及初步打樣(預估1個月, 不確定性較小)
3. Alpha版本Release.

## Current Work on
目前正在開發RGB breakoutboard
    -正在畫電路圖。   
