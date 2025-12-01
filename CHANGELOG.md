# SDK更新日志

## Version 1.0.3

Release on 2025.09.16

* 升级iOS sdk version: 2.8.1.12
* 支持错误上报时附带上报Bugly日志


## Version 1.0.2
Release on 2025.08.15
* 升级Android sdk version: 4.4.6.2, 支持Android 16KB Page size.
* Android 接口configCrashReportParams添加AppChannel参数，用于业务自定义渠道信息
* 升级iOS sdk version: 2.8.1.7
* iOS 新增logBuffer接口和flushLog接口，用于记录和上报自定义log
* iOS 新增setBuglyPluginArray接口用于启用log能力(次log能力非诊断系统能力)
* 升级BuglyAgent到"BuglyPro 1.2.9"

* 修复iOS下调用setAppChannel接口无效的bug


## Version 1.0.1

Release on 2025.08.01

* 发布cocos2dx plugin
* Android sdk version: 4.4.3.7
* iOS sdk version: 2.8.0.6
