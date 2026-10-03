# Tint for X プライバシーポリシー

最終更新日：2026年10月3日

Tint for X（以下「本拡張機能」）は、X（旧Twitter）の背景を、単色・グラデーション・画像から選んで着せ替えられる Chrome 拡張機能です。本拡張機能は、利用者の個人情報を収集・送信・販売しません。

## 収集する情報

本拡張機能は、利用者に関する情報を一切収集しません。アクセス解析、広告、外部サービスへのデータ送信も行いません。

## ページの内容の扱い

本拡張機能は、次のサイトでのみ動作します。

- https://x.com/ ・ https://twitter.com/

これらのページでは、背景の色を置き換えるために、ページのスタイルシート（どの部分がどの色で表示されているか）をブラウザの中で読み取ります。投稿の内容や閲覧履歴を読み取ったり、保存したり、外部に送信したりすることはありません。

## 端末に保存する情報

本拡張機能は、Chrome の拡張機能用ストレージに次の情報を保存します。開発者や第三者のサーバーに送信されることはありません。

- 設定値（オン・オフ、選んだ色、グラデーション、画像の濃さなど）：chrome.storage.sync に保存します。Chrome の同期機能が有効な場合は、利用者自身の Google アカウントの Chrome 間で同期されます。
- アップロードした背景画像：chrome.storage.local に保存します。この端末の中だけに保存され、同期されません。

これらの情報は、本拡張機能をアンインストールすると削除されます。背景画像は、拡張機能のポップアップの「削除」からいつでも削除できます。

## 権限について

- `storage`：上記の設定値と背景画像を保存するために使います。
- 対象サイトへのアクセス（x.com・twitter.com）：そのページの背景の色を変えるために使います。これ以外のサイトにはアクセスしません。

## 本ポリシーの変更

本ポリシーを変更する場合は、このページで更新内容と最終更新日をお知らせします。

## お問い合わせ

本ポリシーに関するお問い合わせは、このリポジトリの Issues（https://github.com/ninolog/tint-for-x-privacy/issues）からお願いします。

本拡張機能は X Corp. とは関係のない非公式のツールです。

---

# Tint for X Privacy Policy

Last updated: October 3, 2026

Tint for X ("the extension") is a Chrome extension that lets you restyle the background of X (formerly Twitter) with a solid color, a gradient or an image. The extension does not collect, transmit or sell any personal information.

## Information we collect

None. The extension collects no information about you. It has no analytics, no ads, and sends no data to any outside service.

## How page content is used

The extension runs only on these sites:

- https://x.com/ and https://twitter.com/

On those pages it reads the page's stylesheets (which parts are drawn in which color), inside your browser, to replace the background colors. It does not read, store or send your posts or browsing history.

## Information stored on your device

The extension keeps the following in Chrome's extension storage. None of it is ever sent to the developer or any third party.

- Your settings (on/off, chosen color, gradient, image strength and so on), in chrome.storage.sync. If Chrome Sync is on, they sync across your own Chrome browsers signed in to your Google account.
- An uploaded background image, in chrome.storage.local. It stays on this device only and is not synced.

They are removed when you uninstall the extension. The background image can also be removed at any time with "削除" (Remove) in the extension's popup.

## Permissions

- `storage`: to keep the settings and background image above.
- Access to x.com and twitter.com: to change the background colors on those pages. The extension does not access any other site.

## Changes to this policy

If this policy changes, the update and its date will be posted on this page.

## Contact

For questions about this policy, please open an issue on this repository: https://github.com/ninolog/tint-for-x-privacy/issues

This extension is not affiliated with or endorsed by X Corp.
