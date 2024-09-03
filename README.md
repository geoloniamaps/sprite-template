# Geolonia アイコンセットのテンプレート

Geolonia Maps または Maplibre でアイコンを表示させるためにスプライトシートを作るテンプレート

Geolonia Maps の標準アイコンセットはこちらのテンプレートを利用しているので、使い方にご参照にしてください。 [GitHub](https://github.com/geoloniamaps/sprite-gstd) [プレビュー](https://geoloniamaps.github.io/sprite-gstd/)

## 使い方

こちらのレポジトリをテンプレートとして、新しいレポジトリを作成してください。その後、

1. スプライトシートに追加したいアイコンを `icons` ディレクトリに追加
1. GitHub Pages を GitHub Actions からデプロイするように設定する（ Settings → Pages → Source を GitHub Actions に変更）
1. この README を編集
1. `_site/index.html` の `<title>` `h1` タグ等を適切に編集します。

ローカルで編集する場合は、 `npm install` 後に `npm run start` をすると、ローカルのサーバーが起動され、GitHubにプッシュする前に確認できます。

うまく行けば、スプライトシートが `https://<GitHub username>.github.io/<repository name>/sprite.png` でホスティングされます。MapLibre対応の `.png / .json / @2x.png / @2x.json` の合計4ファイルが作成されます。MapLibreに複数スプライトシートを読み込ませる方法は、 [公式ドキュメンテーション](https://maplibre.org/maplibre-style-spec/sprite/#multiple-sprite-sources) を参照にしてください。
