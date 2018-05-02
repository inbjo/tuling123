# 申明
    本项目基于https://github.com/gdali/tuling123-sdk的修改
# tuling123
    图灵机器人API SDK for PHP，支持图灵机器人接口v1.0和v2.0，官方文档：https://www.kancloud.cn/turing/web_api/522992
# 要求
    PHP >= 5.3.0 || PHP >= 7.0.0
# 安装
    composer require "faker/tuling123"
# 使用
    有五个主要参数：
*  appID：机器人的APIkey，必填
*  appKey：机器人的secret，必填
*  userID：用户唯一标识符，选填，默认为1
*  selfInfo：客户端属性参数，数组，选填，默认为空，详见demo
*  Text：输入字符串，必填
# 输出
    当->tuling带true参数时，返回Tuling123的原生数组，否则返回文字信息。

