# プロ野球監督＆GMシミュレーター 公式サイト

静的HTMLとCSSのサイトです。GitHub Pagesの公開元はこのリポジトリの `main` / `/ (root)` です。

| 用途 | URL |
| --- | --- |
| アプリ紹介・App Store ConnectのマーケティングURL | https://ebi-oishii.github.io/baseball-game-site/ |
| サポートURL | https://ebi-oishii.github.io/baseball-game-site/support/ |
| プライバシーポリシーURL | https://ebi-oishii.github.io/baseball-game-site/privacy/ |
| 利用規約 | https://ebi-oishii.github.io/baseball-game-site/terms/ |
| 特定商取引法に基づく表記 | https://ebi-oishii.github.io/baseball-game-site/commerce/ |
| 免責事項 | https://ebi-oishii.github.io/baseball-game-site/disclaimer/ |

問い合わせには既存のアプリ共通窓口 `ebi.apps.support@gmail.com` を使います。販売事業者の氏名・住所・電話番号の請求にも、この窓口で遅滞なく対応します。

AdMobは同じホストのルートにある [共通の app-ads.txt](https://ebi-oishii.github.io/app-ads.txt) を使います。野球版の本番Publisher IDは `pub-9837264864279123` です。[AdMobの設置手順](https://support.google.com/admob/answer/9363762)

## サブスクリプションの販売開始前

- 確定したプラン名、対象機能、税込価格、更新周期、無料体験がある場合の終了後の料金と最初の請求時期を、特商法表記と購入画面に反映します。購入確定前に期間・価格・自動更新・解約条件が読めるようにします。[消費者庁の最終確認画面の案内](https://www.no-trouble.caa.go.jp/what/mailorder/rule.html)
- App Store Connectで有料アプリ契約・税務・銀行情報を確認し、サブスクリプショングループと商品を作成します。商品の価格、配信地域、日本語の表示名・説明、審査用画像を設定します。初回のサブスクリプションは新しいアプリバージョンと一緒に提出します。[Appleのサブスクリプション設定](https://developer.apple.com/app-store/subscriptions/) · [初回の審査提出](https://developer.apple.com/help/app-store-connect/manage-submissions-to-app-review/submit-an-in-app-purchase/)
- アプリの購入画面から利用規約、プライバシーポリシー、購入の復元を開けるようにします。アプリ説明やライセンス契約の設定には採用するEULAを反映します。このサイトはAppleの標準EULAを案内しています。[App Reviewガイドライン](https://developer.apple.com/app-store/review/guidelines/#subscriptions)
- 購入SDKを追加したら、実際に外部送信する購入情報と提供先をプライバシーポリシーおよびApp Storeのプライバシー申告に反映します。現行サイトのプライバシーポリシーは、野球版の現在の端末内保存・AdMob・問い合わせの構成を対象にしています。[RevenueCatを利用する場合の申告資料](https://www.revenuecat.com/docs/platform-resources/apple-platform-resources/apple-app-privacy)
- SandboxまたはTestFlightで、購入、別端末での復元、期限切れ、解約後の利用可能期間を確認します。[AppleのSandbox検証](https://developer.apple.com/documentation/storekit/testing-in-app-purchases-in-the-sandbox)

## ローカル確認

リポジトリのルートで `python3 -m http.server 8000` を起動し、`http://localhost:8000/` を開きます。
