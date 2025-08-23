# Workfinder_v1
Workfinder_v1は、HTML,CSS,JavaScriptを使用して書かれた作品の閲覧・検索ができるHTMLファイルです。

# プレビュー
https://atserver186.jp/Service/workfinder/v1/workfinder_v1/

# 使い方
<ins>ロゴ・作品等の編集</ins><br>
作品を追加する場合は、work/archive/workfinder_v1/work2/index.htmlをコピーしてください。<br>
ユーザーページを追加する場合は、work/archive/workfinder_v1/index.htmlをコピーし、プロフィール画像・名前・作品名・サムネイル・作品ファイルなど、必要な情報を入力することで簡単に作成できます。<br>
この際、ユーザー名のフォルダは workfinder_v1 の直下ではなく、archive フォルダの直下に配置してください。<br>

Workfinder_v1ではヘッダー・フッターを共通化しているため、HTMLファイルをChromeなどのブラウザで直接開くと、これらが表示されません。<br>
そのため、簡易環境では Windows の IIS や XAMPP などのローカルサーバーを、本番環境では Apache・nginx・IIS などのWebサーバーソフトをご利用ください。<br>
※XAMPPは開発用のため、セキュリティ設定が甘く、外部公開には適していません。<br>

検索システムを利用する際は、search.html を VSCode などのエディターで開き、<br>
コメントアウトに従って、作品ファイルのパス・サムネイル・タイトル・見出し・検索用キーワードなどを入力してください。<br>

その他の編集可能な箇所については、各HTMLファイル内のコメントアウトをご参照ください。<br>

編集可能なCSSファイルは以下の通りです：<br>

<ul>
  <li>
    style.css - ヘッダー・フッターなど共通部品のスタイル
  </li>
  <li>
    profile.css - 投稿者ページ用のスタイル
  </li>
  <li>
    work.css - 作品一覧ページ用のスタイル（このページ）
  </li>
</ul>

詳しくはこちら https://atserver186.jp/Service/workfinder/v1/work/archive/workfinder_v1/work1/index.html を見てください

ご不明な点がございましたら、ATSERVER総合お問い合わせよりご連絡ください。
※ATSERVERは、Workfinder_v1の開発元ですので、安心してご利用いただけます。

<ins>公開</ins>
Windowsのローカル環境で動作させてい場合は、XAMPPまたは、IISを使用するのが最も簡単です。
IISやXAMPPの使用方法はご自身で調べてください。
簡単です。
Linux環境の場合はApache2を使用するのが楽です
