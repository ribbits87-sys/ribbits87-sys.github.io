# ribbits87-sys.github.io

Haven Atelier のルートサイト。GitHub Pages のユーザーサイトとして
`https://ribbits87-sys.github.io/` で公開される。

| ファイル | 役割 |
|---|---|
| `index.html` | 入口のページ。アプリとサポート・プライバシーへのリンク |
| `app-ads.txt` | AdMob の認定販売者ファイル |

## app-ads.txt について

AdMob のクローラは**ホスト名のルート直下**（`https://ribbits87-sys.github.io/app-ads.txt`）
しか見ない。アプリのサポートサイトは `/kaigo-drill-site/` 配下にあるので、
そちらに置いても読まれない。だからこのリポジトリが要る。

中身は AdMob の [app-ads.txt] タブ →「app-ads.txt の設定方法」に出るスニペットそのまま。
パブリッシャー ID を変えたときは、この1行を差し替える。

反映には AdMob のクロールが要る（公式の案内で**24時間以上**）。状態は
AdMob → すべてのアプリ → app-ads.txt で確認する。

**前提**：ストアの掲載情報に、このサイトのドメインを含むウェブサイトが登録されていること。
Google Play は「ストアの設定 → 連絡先の詳細 → ウェブサイト」に入れてある。
