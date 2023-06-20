# M5Unified_StackChan_ChatGPT_Google_CoreS3_FaceDetectExample

[robo8080さんの完全体AIｽﾀｯｸﾁｬﾝ](https://github.com/robo8080/M5Unified_StackChan_ChatGPT_Google)に、顔検出を組み込んだプログラムを参考例として公開します。  
※VoiceBoxバージョン（完全体AIｽﾀｯｸﾁｬﾝ2）ではありません。  
※顔検出単体のプログラム例はこちらです→　https://github.com/ronron-gh/M5CoreS3_FaceDetect

### 主な仕様
- 顔検出するとｽﾀｯｸﾁｬﾝが話しかけてくれます。
- ｽﾀｯｸﾁｬﾝの顔の隅にカメラ画像が表示されます。画像部分をタッチすると表示ON/OFFできます。
- 額部分をタッチするとｽﾀｯｸﾁｬﾝが聞き取りを開始します（AIｽﾀｯｸﾁｬﾝの既存機能）。


### 補足
- ｽﾀｯｸﾁｬﾝとお話するためにはChatGPTとGoogle Cloud TTSのAPIキーが必要です。取得方法は[robo8080さんの完全体AIｽﾀｯｸﾁｬﾝ](https://github.com/robo8080/M5Unified_StackChan_ChatGPT_Google)のページに記載があります。
- フォルダ名が長いため、ワークスペースの場所によってはライブラリのインクルードパスが通らない場合があります。
なるべくCドライブ直下に近い場所をワークスペースにしてください。(例 C:\Git)
- カメラ画像を表示するためにAvatarライブラリに変更を加えています（libフォルダ参照）。
