groovy-http-server
==================

Groovy で書かれた単純な HTTP サーバーです。

Simple HTTP Server by Groovy.

##使い方（Usage）

`http.groovy` をローカルにダウンロードします。

Download `http.groovy` file to your pc.

以下のコマンドで起動します。

Run with following commad.

```
> groovy http.groovy

port=80
base-dir=D:\tmp\httpgroovy\.
```

ブラウザを開いて、 `http://localhost/` にアクセスします。

Open web browser and access to `http://localhost/`.

その他の使い方については、 `--help` オプションで確認できます。

If you want to check other usage. Run with `--help` option.

```
> groovy http.groovy --help

usage: http <option>
 -b,--base-dir <path>   base directory path. default : current directory.
    --debug             run with debug mode.
 -h,--help              show this help.
 -p,--port <port>       port number. default : 80.
    --print-request     display request infomation.
```

##動作環境（System Requirements）
###OS
Windows

※Linux では未検証。  I don't test on Linux and Unix.

###Java
1.7 or more
