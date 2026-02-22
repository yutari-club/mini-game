# makecode

https://minecraft.makecode.com/?lang=ja#
https://makecode.com/_LFt1Em1urdoE


# チュートリアルの設定方法
codebuilder navigate @p false https://minecraft.makecode.com/?ipc=1&inGame=1#tutorial:github:yutari-club/mini-game/BreaktheTerracotta

---

# チュートリアルmdファイルの制御オプション

### @explicitHints true
明示的なヒント
各ステップでヒントをデフォルトで表示したい場合は、チュートリアルページの上部にあるメタデータで @explicitHints を指定してください。
デフォルトはfalseで、ヒントは非表示になりますが、各ステップで利用できるようになります。

### @flyoutOnly false
フライアウトブロック
利用可能なすべてのブロックを、ツールボックスの代わりに常時表示されるフライアウトにするには、@flyoutOnly を使用します。
デフォルトの設定はfalseです。

### @hideIteration false
反復を隠す
これは、ステップコントロールを非表示にします。
これには、前、次、終了のチュートリアルボタンとメニューバーのステップカウンターが含まれます。
デフォルトはfalseです。

### @activities 1
### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### カスタムブロックの参照
```package
rubyblock=github:Mming-Lab/rubyblock1#master
```

### 作業エリアをブロックなしにする
```template
{}
```
## ポップアップ @showdialog
タイトルの横に「@unplugged」を付けるとポップアップになる

## 画像表示
![代理テキスト](https://yutari.link/wp-content/uploads/2022/02/yutari.logo3_-e1644819005624.png "タイトル")

```ghost
ブロックの表示はない

```template
最初に表示されるブロック
下記表示で、初期ブロックなし
{}

## エージェントをNCPのボタンでテレポートさせる方法
execute as @initiator at @s  run tp @c 2 2 5