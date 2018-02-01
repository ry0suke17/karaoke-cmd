# karaoke-cmd

カラオケのコマンド送信

## オプション

```shell
$ go run karaoke-dam-cmd.go -h
Usage of /tmp/go-build008078685/command-line-arguments/_obj/exe/karaoke-dam-cmd:
  -config int
        config number. (default 1)
  -debug int
        Debug level for libusb (default 3)
  -device string
        select device. default "22ea:0039"  (default "22ea:0039")
  -ep int
        endpoint number. (default 4)
  -interface int
        interface number. (default 3)
  -key string
        select key. (default "none")
  -number int
        select number. (default 999999)
  -setup int
        setup number.
exit status 2
```

## 依存しているパッケージ

- https://github.com/kylelemons/gousb

（こちら廃止予定となっており、[こちら](https://github.com/google/gousb)を使用するようにしないといけない）
