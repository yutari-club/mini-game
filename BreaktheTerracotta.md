### @hideIteration false
### @flyoutOnly true

# my-minecraft-skillmap
name: Minecraft Skillmap
description: Learn coding in Minecraft step by step!
infoUrl: https://minecraft.makecode.com/

## basics-path
name: Basics
description: Learn basic coding with Minecraft
completionUrl: /skillmap/certificates/basics.pdf

### basics-activity1
name: Move Player
description: Learn to move the player with code.
type: tutorial
url: /tutorials/move-player
imageUrl: /static/skillmap/move-player.png

### basics-activity2
name: Place Blocks
description: Place blocks using MakeCode
type: tutorial
url: /tutorials/place-blocks
imageUrl: /static/skillmap/place-blocks.png

## build-path
name: Building
description: Learn how to auto-build structures.

### build-activity1
name: Build House
type: tutorial
description: Automatically build a house.
url: /tutorials/build-house
imageUrl: /static/skillmap/build-house.png

# テラコッタ破壊ゲーム

## ゲーム概要 @showdialog

マイクラでゲームプログラミングをはじめよう！

プレイヤーは丸石で囲まれたバトルフィールド内で、ランダムに出現する黄色の彩釉テラコッタを剣で破壊してスコアを競うアクションゲーム。

時間経過とともにゾンビと葉ブロックが増加し、難易度が段階的に上昇する。

![ニワトリの雨(あめ)](https://raw.githubusercontent.com/yutari-club/mctuto/refs/heads/master/block/world00/level04/01_ChickenRain.webp)


## バトルフィールドを作る

| 項目 | 値 |
|------|-----|
| 横幅（X方向） | 30ブロック |
| 奥行（Z方向） | 30ブロック |
| 壁の高さ | 10ブロック |
| 中心座標 | X=0, Z=0 |
| 地面の高さ | Y=-61 |


