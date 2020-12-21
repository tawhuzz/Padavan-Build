###编译配置文件MI-3
/trunk/configs/templates/xiaomi/mi-3.config
###汉化界面
/trunk/user/www/Makefile
/trunk/user/www/dict/CN.dict
###中文无线SSID
trunk/user/www/n56u_ribbon_fixed/general.js
trunk/user/httpd/aspbw.c
trunk/user/httpd/httpd.h
#################################################################
trunk        
├── configs
│   ├── boards
│   │   └── XIAOMI
│   │       └── MI-3     ---MI-3适配文件
│   │           ├── board.h
│   │           ├── board.mk
│   │           ├── kernel-3.4.x.config
│   │           └── libc.config -> ../uclibc-mipsel.config
│   └── templates
│       └── xiaomi
│           ├── mi-3.config      ---mi-3标准版配置
│           ├── mi-3_spi.config  ---mi-3改SPI闪存配置
│           └── mi-3_4M.config   ---mi-3编译小于4M的固件方便从官方刷入
└── user
    └── www
    │   ├── dict
    │   │   └── CN.dict  ---简体中文语言文件
    │   ├── Makefile     ---简体中文语言配置
    │   │
    │   └───n56u_ribbon_fixed 
    │       └── general.js ────┐
    └── httpd                  │
        ├── aspbw.c        ────┼---中文无线SSID支持
        └───httpd.h        ────┘
        
        
        
