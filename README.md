# nextjs-vitest-biome-template
## 環境構築

前提：node、pnpmのインストール

`lefthook`（pre-commit, pre-push時にlintやtestを行うツール）のインストール
- 例：`brew install lefthook`
- リポジトリ作成時に`lefthook install`で`.husky`ディレクトリが作られる

依存ライブラリのインストール：`pnpm i`

実行：`pnpm dev`
- [http://localhost:3000](http://localhost:3000)でアプリケーションが立ち上がる
