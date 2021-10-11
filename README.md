# qi
非侵入式App性能采集

# 下载
[下载](https://github.com/oneym/qi/releases/latest)地址

# 使用方法
```shell
./qi -p <pid>
```

命令帮助
```shell
  -h, --help                 show this help
  -p, --pid int              target pid
      --qi-server-port int   qi server port (default 54168)
  -v, --version              qi version

```

# 功能一览
## 指标信息
|   /  | cpu | mem | cpu time | call tree |
|  :-: | :-: | :-: | :-: | :-: |
| Java | ✅  | ✅  | ✅ | ✅ |
|Golang| ✅  | ✅  | ❎ | ❎ |

## 支持的系统
目前仅支持x86_64操作系统
|   /  | MacOS | Linux | Windows |
|  :-: | :-: | :-: | :-: |
| Java | ✅  | ✅  | ✅ |
|Golang| ✅  | ❎  | ❎ |

## 测试情况
|   /  | MacOS | Linux | Windows |
|  :-: | :-: | :-: | :-: |
| Java | ✅  | ❎  | ❎ |
|Golang| ✅  | ❎  | ❎ |
