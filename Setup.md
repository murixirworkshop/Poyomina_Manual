# 導入方法(VRChatへのアップロード)

## **1. 事前準備**  

Unityプロジェクトに[ポヨミナ](https://mesukemoshop.booth.pm/items/7420279)をダウンロード・導入してください。

## 2. **PoyominaExのインポート**  

- Unity のメニューから **Assets → Import Package → Custom Package** を選択。  

- 配布ファイル **`PoyominaExVerxxx.unitypackage`** を指定してインポートしてください。（xxxにはバージョン名が入ります）。

  Importを選択し、インポートします。

- インポートが完了すると `00_Murixir/06Ex_PoyoEx` フォルダがアセットに追加されます。



## 3. **シーンに配置**  

Hierarchy上のポヨミナに、PoyominaEx.prefabをドラッグ&ドロップしてください。

> ⚠️ <span style="color:red; font-weight:bold;">注意</span>  
> Preset2, Preset3用は個別に/06Ex_PoyoExPoyoEx/10_Presets/PresetX/内に.prefabが用意されています。
> これはポヨミナのBodyテクスチャに色味を合わせるために必要です。
>
> 改変済みのポヨミナにPoyominaExを導入する手順は次のステップで解説します。

![image-20250914153538635](Images/PoyoEx1.png)

##　4. 色味合わせ

ポヨミナExの見た目をより自然にするために以下の設定を行ってください。

このステップは、ポヨミナのpresetを改変せずに使う場合は不要です。
改変してテクスチャを変更している場合はこれを参考に設定してください。

1. まず使用した.prefabのマテリアルを選択します。

​	06Ex_PoyoEx直下のPoyominaEx.prefabを使用した場合 --> /06Ex_PoyoEx/02_Materials/Preset1/<BR>
​	06Ex_PoyoEx/10_Presets/Preset2/のPoyominaEx.prefabを使用した場合 --> /06Ex_PoyoEx/02_Materials/Preset2/<BR>
​	06Ex_PoyoEx/10_Presets/Preset3/のPoyominaEx.prefabを使用した場合 --> /06Ex_PoyoEx/02_Materials/Preset3/<BR>

![image-20250914154200383](Images/PoyoEx2.png)

2. 06_Poyomina_ExBody.mat および 06_Poyomina_ExBody_Dark.mat をInspectorから編集します。
   メインカラー2ndのテクスチャをポヨミナ(Poyomina)のBody2に使用しているテクスチャ(通常は06_Poyomina_Body_Base_color.png)に変更してください。06_Poyomina_ExBody.mat および 06_Poyomina_ExBody_Dark.mat 共に設定をしてください。

![image-20250914154858483](Images/PoyoEx3.png)

## 5. **アップロード**  

- Unity のメニューからVRChat SDK -> Show Control Panel で VRChat SDK の Control Panel を開き、VRChatのIDでログインしてください。

- ログインするとBuilderタブからAvatarの情報を入力できるようになります。Name, Visibility, サムネイルを設定してアップロードします。

> ⚠️ <span style="color:red; font-weight:bold;">注意</span>  
> Visibility の項目は <span style="color:red; font-weight:bold;">必ず Private</span> に設定してください。  
> Public に設定するのは <span style="color:red; font-weight:bold;">規約違反</span> です！

- → Builder から **Build & Publish for Windows** を実行。  

- アップロードを完了させます。お疲れ様でした！

