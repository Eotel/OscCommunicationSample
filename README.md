# OscCommunicationSample

OSC通信を利用して値を受信するサンプルプロジェクト

## 初期設定

1. レジストリを追加する

  <img src="https://github.com/Eotel/OscCommunicationSample/blob/images/imgs/second_registry.png" width="720">

2. PackageManagerからOSCJackVSをインストールする

  <img src="https://github.com/Eotel/OscCommunicationSample/blob/images/imgs/packagemanager.png" width="720">

3. ZIG SIMを設定する

  - Sensor > Quaternion を送信する設定にする
  - Setting > IP Address をUnityを実行するPCのIPアドレスに設定する
  - Setting > Port Number を`9000`にする
  - Setting > Device UUID を`iPhone`にする

4. ZIG SIMとUnityを実行する
  - Unityを起動するとコンソールにエラーが出るので，指示に従いVisualScript Nodeを再構成する（Player Settings内の指定のボタン押すだけ）


## 追記

- VisualScript はgitに上げてないので，自分で書かないと動かない！
- 忘れていました
