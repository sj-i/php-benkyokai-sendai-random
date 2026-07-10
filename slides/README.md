# slides

勉強会用スライド置き場。トーク 1 本につき 1 ディレクトリ、
[Marp](https://marp.app/) 形式の Markdown で書く。

## レンダリング

```bash
# HTML
npx @marp-team/marp-cli slides/dumping-php-memory/slides.md -o dumping-php-memory.html

# PDF
npx @marp-team/marp-cli slides/dumping-php-memory/slides.md --pdf

# プレビューしながら編集
npx @marp-team/marp-cli -p -w slides/dumping-php-memory/slides.md
```

VS Code なら [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode) 拡張でプレビュー可。

各ディレクトリには生成済みの `slides.html` / `slides.pdf` もコミットしてある
（ソースは `slides.md`）。手直ししたら上のコマンドで再生成してコミットする。

## 一覧

- [dumping-php-memory](dumping-php-memory/slides.md) — 外から、中から、素の PHP で: PHP プロセスのメモリダンプが 3 通りに増殖した話 (reli / ext-rdump / php-memory-dump)
  （[HTML](dumping-php-memory/slides.html) / [PDF](dumping-php-memory/slides.pdf)）
