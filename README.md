# YOU&MORE G.K. 公式サイト

合同会社YOU&MORE（障害福祉サービス事業所）の公式サイトです。

## 理念

障がいと共に。あなたともっと楽しくユウモアに。

## 構成

- `index.html` ... トップページ
- `css/style.css` ... スタイルシート
- `images/` ... 画像素材

## 事業内容

- 共同生活援助（グループホーム）
- 就労継続支援B型（開設予定）
- 訪問看護ステーション（開設予定）

## 更新方法

1. ファイルを編集する
2. 変更をGitHubにプッシュする
3. Cloudflare Pagesが自動で公開する

## 技術情報

- 静的サイト（HTML / CSS / 軽量JavaScript）
- ホスティング: Cloudflare Pages

## 連絡先

- 〒300-0815 茨城県土浦市中高津2丁目4-11
- 090-3128-2267
- youmoamore@gmail.com

---

# サイト管理ガイド（次回の更新用）

このファイルを読めば、サイトの全体像と更新手順が把握できます。

## 公開情報

| 項目 | 内容 |
|---|---|
| 公開URL | https://cocolo-youmore.com |
| 一時URL | https://youmore-site.pages.dev |
| ドメイン | cocolo-youmore.com（Cloudflareで購入） |
| ホスティング | Cloudflare Pages |
| GitHub | https://github.com/youmore-JP/youmore-site（mainブランチ） |

## サイト構成

- `index.html` ... トップページ（ヒーロー・私たちの想い・事業内容・下部ナビ・会社概要・アクセス・フッター）
- `css/style.css` ... デザイン全般（配色・レイアウト・レスポンシブ）
- `images/` ... 画像素材（2.jpeg=トップ背景、共同生活援助/・就労継続支援/・訪問看護/）

## デザインの特徴

- JINSホールディングス風のコーポレートデザイン
- アクセントカラー: ブルー（#1a73e8）
- ヒーロー: 猫の写真（images/2.jpeg）+ フェードイン + 左下にキャッチコピー
- 事業内容: 3つの縦長カード（10:16比）で写真+テキスト

## 更新フロー（重要）

1. `index.html` / `css/style.css` を編集
2. GitHubにコミット → mainブランチへプッシュ
3. Cloudflare Pagesが自動で再デプロイ（数分）

※ 編集後に「index.htmlをダミー編集→コミット」すると、Cloudflareの再デプロイを確実にトリガーできます。

## 更新の際の指示プロンプト（AIへ）

```
/home/cocololo/youmore-site にある YOU&MORE 事業所のホームページを更新したい。
まずフォルダの中身と index.html を読んで、サイトの全体像を把握して。
変更したい内容は【ここに書く】。
変更後は変更箇所を教えて。GitHubへの反映は自分で行うので、編集のみでOK。
```

## 注意事項

- 画像を差し替える場合は `images/` にファイルを追加してから、index.htmlの参照を変更
- プライバシーに注意（利用者の顔写真は使わない）
- 画像素材はフリー素材サイト（SAIYO DESIGN 等）から商用利用可のものを使用

