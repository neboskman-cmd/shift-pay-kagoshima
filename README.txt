シフト給与メーター V7（PWA版）

【iPhoneでアプリとして使う方法】
1. このフォルダ一式を HTTPS のWebサーバーへアップロードします。
   例: GitHub Pages / Netlify / Vercel
2. iPhoneのSafariで公開URLを開きます。
3. 共有ボタン →「ホーム画面に追加」→「追加」。
4. ホーム画面の「シフト給与」アイコンから起動できます。

【重要】
- Service Workerは file:// では動きません。HTTPSで公開してください。
- データはブラウザのlocalStorageに保存されます。SafariのWebサイトデータを消すと消えるため、重要な実績は別途バックアップしてください。
- standalone.html は単体確認用です。PWAとして使うときは index.html を公開してください。
