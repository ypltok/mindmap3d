# 3D Mind Map

考えを立体で広げる3Dマインドマップ。スマホとPCにインストールして使えます（オフラインでも動きます）。

- 公開ページ: https://ypltok.github.io/mindmap3d/
- マップは各端末のブラウザに保存されます（このリポジトリには入りません）。
- クラウド同期とAI作成は Claude 版で使えます: https://claude.ai/artifact/VUaZK6bFgfV2KXsMH9dF9F

## 中身

| ファイル | 役割 |
|---|---|
| `index.html` | アプリ本体 |
| `three.min.js`, `OrbitControls.js` | 3D表示ライブラリ（three.js r147、MITライセンス） |
| `manifest.webmanifest` | インストール用の設定（名前・アイコン） |
| `sw.js` | オフラインで開くための仕組み |
| `icon-*.png`, `apple-touch-icon.png` | アイコン |
