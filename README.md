# librust

Rust の学習用ライブラリcrate。はじめての Rust プロジェクトとして、ライブラリの作り方・テスト・examples の動かし方を練習する。

## 構成

```
librust/
├── Cargo.toml      # プロジェクト設定（名前・依存クレート）
├── src/
│   └── lib.rs      # ライブラリ本体
└── examples/       # ライブラリを実際に使うサンプル（cargo run で実行できる）
```

## よく使うコマンド

```sh
cargo build                    # コンパイルできるか確認
cargo test                     # テストを実行
cargo run --example basics     # examples/basics.rs を実行
cargo doc --open               # ドキュメントを生成してブラウザで開く
```

## 学習リソース

はじめて Rust を学ぶのにおすすめの教材:

- [The Rust Programming Language（通称: The Book）](https://doc.rust-lang.org/book/) — 公式の入門書。最初に読むならこれらしい。
- [Tour of Rust](https://tourofrust.com/) — ブラウザ上でコードを動かしながら文法を学べるチュートリアル。
- [実践 Rust 入門（Zenn）](https://zenn.dev/mebiusbox/books/22d4c1ed9b0003/viewer/6d5875) — 日本語で読める解説記事。
