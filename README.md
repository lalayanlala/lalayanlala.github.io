# lalayanlala Dalamud Plugin Repository

Dalamudのカスタムプラグイン一覧です。

カスタムプラグインリポジトリURL:

```text
https://lalayanlala.github.io/pluginmaster.json
```

## 公開ルール

今後 `lalayanlala` のGitHubで公開するDalamudプラグインは、すべてこのリポジトリの
`pluginmaster.json` に登録します。

1. 各プラグインのGitHub Releaseへ `latest.zip` を添付する
2. ZIP内のマニフェストと `pluginmaster.json` で `InternalName`、`AssemblyVersion`、
   `DalamudApiLevel` を一致させる
3. `DownloadLinkInstall`、`DownloadLinkUpdate`、`DownloadLinkTesting` はReleaseの
   `latest.zip` を指すようにする
4. 更新時は必ず `AssemblyVersion` と `LastUpdate` を更新する
5. `pluginmaster.json` が有効なJSONであることと、配布URLが取得できることを確認する

新規登録時は `plugin-template.json` をコピーして必要な値を設定してください。
