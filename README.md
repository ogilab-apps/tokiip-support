# tokiip-support

ToKiip の公開ページ（プライバシーポリシー・利用規約・サポート）。

**このフォルダの中身が、そのまま `ogilab-apps/tokiip-support` リポジトリのルートになる。**
`shikakulog-support` と同じ構成・同じレイアウトに揃えてある。

| ファイル | 公開URL | 用途 |
|---|---|---|
| `index.html` | `https://ogilab-apps.github.io/tokiip-support/` | Support URL（ASC必須） |
| `privacy.html` | `.../privacy.html` | Privacy Policy URL（ASC必須・日本語） |
| `terms.html` | `.../terms.html` | 利用規約（日本語） |
| `privacy-en.html` | `.../privacy-en.html` | Privacy Policy（英語） |
| `terms-en.html` | `.../terms-en.html` | Terms of Use（英語） |

アプリからのリンクは `src/features/public-pages.ts` に定義し、`src/__tests__/public-pages.test.ts` で固定している。
**URLを変えるときは両方を直す。**

## 公開の手順

1. `ogilab-apps` に `tokiip-support` リポジトリを作る（Public）
2. このフォルダの中身をリポジトリのルートへ置いて push
3. Settings → Pages → Source を `main` ブランチのルートにする
4. 上表のURLが表示されることを確認する

## 問い合わせ先

`ogilab.apps@gmail.com`。ピカパラ・shikakuLog と同じ ogilab 共通アドレスを使う。
アプリ専用のアドレスは作らない。

## 更新のたびに確認すること

- 価格（買い切り ¥2,480 / 月額 ¥300）が App Store Connect の設定と一致しているか
- 無料枠の記載（解き直し中10問）が実装と一致しているか
