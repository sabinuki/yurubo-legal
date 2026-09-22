# yurubo-legal

アプリ「ゆるぼ」の法務文書を GitHub Pages で公開するためのリポジトリ。

- プライバシーポリシー: https://sabinuki.github.io/yurubo-legal/

**文面の正は本リポジトリの `index.html`**。アプリ本体リポジトリ（`sabinuki/yurubo`）には文面を置かず、`docs/product/privacy-policy.md` に「公開ページの各項目が実装のどこに対応するか」の一覧と記載方針だけを持つ。

実装（データベーススキーマ・通知・クラッシュ収集の設定）を変更したら、本体側の対応表で該当項目を確認し、本リポジトリの PR で `index.html` を更新する。
