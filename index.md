# アプリケーション プライバシーポリシー一覧

KawaNova / KawaDev が開発・提供しているアプリおよび Chrome 拡張機能のプライバシーポリシーは以下の通りです。

## 命名規則（Android）

新規・更新する Android アプリのポリシーは次の名前に統一します。

| 種類 | パターン | 例 |
|------|----------|-----|
| Markdown | `android-{slug}.md` | `android-rakuphotoai.md` |
| HTML（公開） | `android-{slug}.html` | `android-rakuphotoai.html` |

- `{slug}` はパッケージ末尾やアプリ識別子を **小文字・ハイフン可**（例: `lazyfitnessai`, `sql-query-drill`）
- Play Console には `https://kawanova.github.io/privacy-policy/android-{slug}.html` を登録する
- 旧来の `RakuPhotoAI.html` のような CamelCase 単独名は使わず、互換リダイレクトのみ残す

## Android アプリ

* [オフモジ（OffMoji）](./privacy.html) — com.kawanova.talktext
* [Python 3 エンジニア：データ分析実技 対策アプリ](./Python3-DataAnalysis.html)
* [Python 3 エンジニア：基礎知識 対策アプリ](./Python3-Basic.html)
* [Python 3 エンジニア：実務・応用 対策アプリ](./Python3-Practical.html)
* [ITパスポート 過去問](./IT-Passport.html)
* [FP3 Trainer Android App](./FP3-Trainer.html)
* [NovusArcade: つぶやきミニゲーム集 - 概要](NovusArcade.html)
* [Android — らくフォトAI](./android-rakuphotoai.html) — com.kawanova.rakuphotoai
* [わんぽアラート（Wanpo Alert）](./WanpoAlert.html) — com.kawanova.wanpo_alert
* [Android — データ分析SQL基礎ドリル](./android-sql-query-drill.html) — com.kawanova.sql_query_drill
* [Android — 簿記3級 仕訳ミニドリル](./android-boki-journal-drill.html) — com.kawanova.bokijournal
* [Android — たてながスクショ](./android-tatenaga.html) — com.kawanova.tatenaga
* [Android — AuraPitch / OtoTore（mimitore）](./android-aurapitch.html) — com.kawanova.aurapitch
* [Android — ズボラFit AI](./android-lazyfitnessai.html) — com.kawanova.lazyfitnessai

## Chrome 拡張機能

* [TabMarkList](./tabmarklist.html)
* [DeepWork Vault](./deepwork-vault.html)

## GitHub Pages

このリポジトリは **GitHub Pages** で公開しています。

| 項目 | 値 |
|------|-----|
| 公開 URL（トップ） | https://kawanova.github.io/privacy-policy/ |
| らくフォトAI | https://kawanova.github.io/privacy-policy/android-rakuphotoai.html |

### 初回セットアップ（参考）

1. リポジトリを GitHub に作成（プライバシー文のみなら **Public 推奨**）。
2. **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)**
3. HTML をルートに配置し、main に push する。
4. 数分後、https://&lt;user&gt;.github.io/&lt;repo&gt;/ で公開される。

**Private リポジトリ** の Pages は GitHub Pro / Team / Enterprise が必要です。無料プランでは **Public** にするか、別ホスティングを使ってください。

現在このリポジトリは **Public** のため、上記 URL で誰でも閲覧できます（アプリのソースコードは含みません）。
