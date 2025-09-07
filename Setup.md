# 導入方法

- **Unity バージョン**：2022.3.22f1  
- **必須パッケージ**  
  以下のパッケージを **[VRChat Creator Companion (公式ページ)](https://vcc.docs.vrchat.com/)** 経由で導入してください。  

  - [lilToon](https://lilxyzw.github.io/lilToon/)  
  - [FaceEmo](https://suzuryg.github.io/face-emo/)  
  - [Modular Avatar](https://modular-avatar.nadena.dev/)  
- **インポート手順**
  1. **事前準備**  
     - Unity プロジェクトの作成、および VCC (VRChat Creator Companion) の導入方法については本マニュアルでは解説しません。  
       各自で公式ドキュメントや解説記事を参考にセットアップを完了させてください。
  2. **必須パッケージの追加**  
     - VCC の **Manage Project** から以下を追加：  
       - lilToon  
       - FaceEmo  
       - Modular Avatar  
  3. **Poyomina本体のインポート**  
     - Unity のメニューから **Assets → Import Package → Custom Package** を選択。  
     - 配布ファイル **`PoyominaVerxxx.unitypackage`** を指定してインポートしてください。（xxxにはバージョン名が入ります）  
     - インポートが完了すると `00_Murixir/06_Poyomina` フォルダがアセットに追加されます。
  4. **シーンに配置**  
     - 以下のいずれかの **`Poyomina.prefab`**（または Blank 版を使用する場合は **`Poyomina_Blank.prefab`**）を **Hierarchy** にドラッグ＆ドロップしてください。  
       - `Assets/00_Murixir/06_Poyomina/` → **Poyomina.prefab（虎のポヨミナ）**  
       - `Assets/00_Murixir/06_Poyomina/10_Presets/Preset2/` → **Poyomina.prefab（豹のポヨミナ）**  
       - `Assets/00_Murixir/06_Poyomina/10_Presets/Preset3/` → **Poyomina.prefab（猫のポヨミナ）**
  5. **アップロード**  
     - VRChat SDK の Control Panel → Builder から **Build & Publish for Windows** を実行。  
     - 必要情報を入力してアップロードを完了させます。