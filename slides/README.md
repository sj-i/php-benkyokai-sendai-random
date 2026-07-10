# slides

勉強会用スライド置き場。[Marp](https://marp.app/) 形式の Markdown で書く。

## レンダリング

```bash
# HTML
npx @marp-team/marp-cli slides/php-memory-dump.md -o php-memory-dump.html

# PDF
npx @marp-team/marp-cli slides/php-memory-dump.md --pdf

# プレビューしながら編集
npx @marp-team/marp-cli -p -w slides/php-memory-dump.md
```

VS Code なら [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode) 拡張でプレビュー可。

## 一覧

- [php-memory-dump.md](php-memory-dump.md) — 外から、中から、素の PHP で: PHP プロセスのメモリダンプ 3 変化 (reli → ext-rdump → php-memory-dump)
