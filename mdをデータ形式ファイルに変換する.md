# md をデータ形式ファイルに変換する

- json 形式
- yaml 形式
- cue 形式

json を cue に変換する場合は、以下のコマンドを実行する。

```bash
# 個別のファイルを変換する場合
cue import data/social-media/twitter/twitter.json -o data/cue/social-media/twitter/twitter.cue

# 一括で変換する場合
cue import data/social-media/*/*.json -o data/cue/social-media/*.cue
```
