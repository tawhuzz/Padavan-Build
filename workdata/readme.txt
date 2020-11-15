/trunk/user/www/Makefile
/trunk/user/www/dict/CN.dict
/trunk/configs/templates/xiaomi/mi-3.config

#################################################################
trunk        
├── configs
│   ├── boards
│   │   └── XIAOMI
│   │   │   └── MI-3     ---MI-3适配文件
│   │   │       ├── board.h
│   │   │       ├── board.mk
│   │   │       ├── kernel-3.4.x.config
│   │   │       └── libc.config -> ../uclibc-mipsel.config
│   └── templates
│       └── xiaomi
│           ├── mi-3.config      ---mi-3标准版配置
│           └── mi-3_spi.config  ---mi-3改SPI闪存配置
└── user
    └── www
        ├── dict
        │   └── CN.dict  ---简体中文语言文件
        └── Makefile
        
