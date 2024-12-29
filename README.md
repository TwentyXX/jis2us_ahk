# JIS2US.ahk
JIS配列をマッピングしてUS配列にするAHKスクリプトです。\
This is an AHK script that maps JIS arrays to US arrays.

## What is this ?
AHKv2.0ではほとんどのキーの自然なマッピングが可能になったので、
それを利用して、`Send`を全く使わずに実現できました。\
Since AHKv2.0 allows natural mapping of most keys,
I was able to use it to achieve this without using `Send` at all.

## Requirement
AutoHotKey v2.0+

## Usage
使用元.ahkと同じフォルダに入れて、使用元.ahkに以下を追加 \
Put it in the same folder as the source.ahk and add the following to the source.ahk
```ahk
#Include "JIS2US.ahk"
```
もしくは`Libs`フォルダに入れて、使用元.ahkに以下を追加 \
Or put it in the `Libs` folder and add the following to the source.ahk

```ahk
#Include <JIS2US>
```

## Special Thanks
このコードは元々[@snytng](https://qiita.com/snytng)さんが公開していたものです。  
元のコードはこちらからご覧いただけます。\
[Qiita - AutoHotKey v2で日本語配列(106/109)→英語配列(101/102)](https://qiita.com/snytng/items/ec72d5dd892d3a520d6e)  
ありがとうございました。