## 斗地主 &nbsp;&nbsp;

[![Build Status](https://travis-ci.org/mailgyc/doudizhu.svg?branch=master)](https://travis-ci.org/mailgyc) &nbsp;&nbsp;
[![Coverage Status](https://coveralls.io/repos/github/mailgyc/doudizhu/badge.svg?branch=master)](https://coveralls.io/github/mailgyc/doudizhu?branch=master) &nbsp;&nbsp;
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)

斗地主游戏，后端基于 Python+Tornado+MySQL 开发，前端 Phaser 引擎

## Dependencies

- Python3.6+
- Mysql5.7+

## Quick Start

1. Localhost

```sh
    git clone https://github.com/mailgyc/doudizhu
    cd doudizhu
    mysql --user=root -p < schema.sql
    pip3 install -r requirements.txt
    cd doudizhu
    python3 app.py --password=your_database_password
    # Now visit http://127.0.0.1:8080
```

1. Docker

```sh
    docker-compose up -d --build
```

Online Demo
<http://m.ihouser.com/>

运行截图
![menu](https://raw.githubusercontent.com/mailgyc/doudizhu/master/screenshot/a.png)
![battle1](https://raw.githubusercontent.com/mailgyc/doudizhu/master/screenshot/c.png)
![battle2](https://raw.githubusercontent.com/mailgyc/doudizhu/master/screenshot/d.png)
