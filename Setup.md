# 導入方法(VRChatへのアップロード)

## **1. 事前準備**  

- [Unity(2022.3.22f1)](https://unity.com/ja/download)をダウンロード・インストールしてください。

- **[VRChat Creator Companion](https://unity.com/ja/download)** **(VCC)** を導入してください。

  ![image-20250907185325640](PoyominaManual_Pict/VCC0.png)

## **2. 必須パッケージの追加**  

- 以下のパッケージをVCC経由で導入します。
  - **必須パッケージ**  
    - [lilToon](https://lilxyzw.github.io/lilToon/)  のウェブページから「VCCに追加」を選択し、画面の案内に従ってAdd Repositoryを行ってください。
    - [FaceEmo](https://suzuryg.github.io/face-emo/ja/)  のウェブページから「ダウンロード(VCC)」を選択し、画面の案内に従ってAdd Repositoryを行ってください。
    - [Modular Avatar](https://modular-avatar.nadena.dev/ja)  のウェブページから「ダウンロード」を選択し、画面の案内に従ってAdd Repositoryを行ってください。

## 3. **VCCで新規プロジェクトの作成**

画面右上のCreate New Projectから新規プロジェクトを作成してください。

![image-20250907190359795](PoyominaManual_Pict/VCC1.png)

続いて表示される画面でUnity2022 Avatar Projectを選択し、プロジェクト名を任意に設定してCreate Projectからプロジェクトを作成してください。

![image-20250907185816115](PoyominaManual_Pict/VCC2.png)

## 4. 必須パッケージのインストール

プロジェクトが作成できたらまずManage Projectを選択し、lilToon, Modular Avatar, FaceEmoをインストールしてください。（Not Installedのプルダウンメニューから最新版を選択します）。

ここで必須パッケージが表示されない場合は、[2. 必須パッケージの追加](###_2-必須パッケージの追加)をやり直してください。

![image-20250907191227241](PoyominaManual_Pict/VCC3.png)

最終的に以下のようにlilToon, Modular Avatar, FaceEmoがインストールされた状態になればOKです。

![image-20250907192752855](PoyominaManual_Pict/VCC7.png)

## 5. **Poyomina本体のインポート**  

- Open Projectを選択し、作成したプロジェクトを開いてください。Unityが起動します。

![image-20250907192931627](PoyominaManual_Pict/OpenProject.png)

- Unity のメニューから **Assets → Import Package → Custom Package** を選択。  

![image-20250907193231728](PoyominaManual_Pict/Unity1.png)

- 配布ファイル **`PoyominaVerxxx.unitypackage`** を指定してインポートしてください。（xxxにはバージョン名が入ります）。

  Importを選択し、インポートします。

![image-20250907193733475](PoyominaManual_Pict/Unity2.png)

- インポートが完了すると `00_Murixir/06_Poyomina` フォルダがアセットに追加されます。

## 6. **シーンに配置**  

- 以下のいずれかの  `Poyomina.prefab` （または Blank 版を使用する場合は `Poyomina_Blank.prefab`）を **Hierarchy** にドラッグ＆ドロップしてください。  
  - `Assets/00_Murixir/06_Poyomina/` → **Poyomina.prefab（虎のポヨミナ）**  
  
  - `Assets/00_Murixir/06_Poyomina/10_Presets/Preset2/` → **Poyomina.prefab（豹のポヨミナ）**  
  
  - `Assets/00_Murixir/06_Poyomina/10_Presets/Preset3/` → **Poyomina.prefab（猫のポヨミナ）**
  
    ![image-20250907193847044](PoyominaManual_Pict/Unity3.png)
  
    成功するとポヨミナがシーンに置かれます。
  
    ![image-20250907193930926](PoyominaManual_Pict/Unity4.png)

## 7. **アップロード**  

- Unity のメニューからVRChat SDK -> Show Control Panel で VRChat SDK の Control Panel を開き、VRChatのIDでログインしてください。

  ![image-20250907195120702](PoyominaManual_Pict/SDK1.png)

- ログインするとBuilderタブからAvatarの情報を入力できるようになります。Name, Visibility, サムネイルを設定してアップロードします。

> ⚠️ <span style="color:red; font-weight:bold;">注意</span>  
> Visibility の項目は <span style="color:red; font-weight:bold;">必ず Private</span> に設定してください。  
> Public に設定するのは <span style="color:red; font-weight:bold;">規約違反</span> です！

![image-20250907200200691](PoyominaManual_Pict/SDK2.png)

- → Builder から **Build & Publish for Windows** を実行。  

- アップロードを完了させます。お疲れ様でした！