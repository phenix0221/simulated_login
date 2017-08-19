### simulated_login程序简介

- 作者：phenix0221
- QQ：381904496
- Python版本：3.5.3
- 程序版本：v1
- 功能：简单实现了用户注册、登录、查询、修改密码、删除、解锁等功能

### 程序结构

- 用户注册
- 用户登录
  - 普通用户登录成功后，进入子菜单
    - 修改密码
    - 返回主菜单
    - 退出程序
  - 管理员登录成功后，进入子菜单：
    - 修改密码
    - 用户删除
    - 用户解锁
    - 查看用户信息（用户名，状态，注册时间）
    - 返回主菜单
    - 退出程序
- 退出

### 使用说明

- 程序在linux平台上测试通过，windows平台上无法显示不同字体颜色，其它平台暂未测试


- 程序使用了getpass模块，由于pycharm不支持getpass模块，因此需要在命令行中使用python解释器来执行程序，例如：`python3 analog_login.py`
- 第一次执行程序时，会自动创建管理员账户，用户名和密码都是administrator
- 除管理员账户外，程序没有内置任何用户信息，需要先进行注册
