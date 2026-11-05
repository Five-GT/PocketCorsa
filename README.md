<div align="center">

<img src="Docs/Images/pocket_corsa_logo_transparent.png" alt="POCKET CORSA Logo" width="480"/>

<br/>

[日本語](#japanese) | [English](#english)

</div>

---

<a name="japanese"></a>
# POCKET CORSA クイックスタートガイド (日本語)

Assetto Corsa（アセットコルサ）のMODをスマホ（Android）で走らせるための基本操作ガイドです。

> **⚠️ 注意事項（MOD非同梱）**
> 本アプリに車両やコースのデータは含まれていません。ご自身でお持ちのAssetto Corsa用MODデータを端末に配置してプレイしてください。

---

## 1. 初回セットアップ（権限許可・フォルダ作成・パス指定）

### ステップ①：ストレージアクセスの許可
1. アプリを初回起動すると、自動的にAndroidの権限設定画面（または許可ダイアログ）が表示されます。
2. 画面の案内に従って **「すべてのファイルへのアクセス」** を許可してください。
   *(※MODを端末のストレージから読み込むために必要な権限です)*

### ステップ②：フォルダの作成 ＆ MODの配置
お使いのスマホのファイル管理アプリ（Files等）やPCとのUSB接続を使い、端末内の好きな場所（Downloadフォルダ等）に3つのフォルダを作成します。

- **車両用フォルダ**（例: `cars`）
- **コース用フォルダ**（例: `tracks`）
- **リプレイ用フォルダ**（例: `replays`）※走行ログが自動保存される空フォルダ

> **💡 重要：MODは必ず「解凍（展開）」して配置してください**
> ダウンロードしたMODファイル（`.zip`、`.rar`、`.7z` など）は**圧縮されたままでは読み込めません**。
> 必ず事前に解凍し、中身のフォルダ（`.kn5` や `ui/`、`data.acd` 等が入っているフォルダ）をそのまま各フォルダへ配置してください。

### ステップ③：アプリ側でのパス指定
1. アプリ内の **「SETTINGS（設定）」** を開きます。
2. 作成した **車両（Cars）・コース（Tracks）・リプレイ（Replays）** の各フォルダをそれぞれ選択して指定します。
3. 指定が完了すると、MODがアプリに読み込まれます。

---

## 2. オプション設定項目（SETTINGS）

トップメニューの **「SETTINGS」** では、パス指定のほか、端末に合わせた快適なプレイ環境を設定できます。

- **MODフォルダ指定**:
  - `CAR / TRACK / REPLAY PATH`: 車両・コース・リプレイ各フォルダの変更
  - `RE-SCAN MODS`: MODを追加・削除した際の再読み込み
- **リプレイ設定**:
  - `ENABLE REPLAY RECORDING`: 走行自動録画の ON / OFF
  - `OTHER CARS (ONLINE)`: オンライン走行時の他車の記録頻度
- **グラフィック・負荷軽減設定（動作が重い場合）**:
  - `SMALL OBJECT DRAW DISTANCE`: 小物部品（ポール・看板・フェンス等）の描画距離
  - `MOD TEXTURE QUALITY`: テクスチャの解像度・品質切り替え
  - `STREET LIGHTS`: 夜間街灯の光源数（OFFにすると動作が軽くなります）
- **システム設定**:
  - `VIBRATION`: 衝突時や縁石に乗ったときのスマホ振動（ハプティクス）の ON / OFF

---

## 3. 車両選択・スキン・走行チューニング

1. メニュー画面の **「CAR」** をタップして走りたい車を選択します。
2. **スキン変更**: カラーリングやバイナルの切り替えが可能です。
3. **TUNING（走行チューニング）**:
   お好みの乗り味に合わせて車両の物理挙動を細かく調整できます。
   - **ACCEL MODEL**: 実車に忠実な物理計算「REAL」と、扱いやすい「ARCADE」を切り替え
   - **POWER**: 加速力・エンジン出力の倍率（30%〜400%）
   - **AIR DRAG**: 最高速や伸びに影響する空気抵抗の強さ（25%〜200%）
   - **LATERAL GRIP**: ドリフトの滑りやすさを変える横グリップ倍率（50%〜150%）
   - **BRAKE CURVE**: ペダル操作に応じたブレーキの効き方
   - **プリセット**: 「RESET TO DEFAULT（標準実車値）」や「RESET TO ARCADE（乗りやすい設定）」にワンタップで変更可能
   *(※オンライン走行時はイコールコンディション維持のため自動的にREAL基準となります)*

---

## 4. コース・レイアウトの選択
1. メニュー画面の **「TRACK」** をタップします。
2. 配置したコースMODの一覧から走りたいコースを選択します。
3. 複数レイアウト（ドリフト用、逆走、ショートカット等）が存在するコースは、レイアウトの選択も行えます。

---

## 5. 車の走らせ方・共通操作

シングル・オンライン共通の操作方法です。

- **ステアリング（ハンドル）**:
  画面左側のハンドルをスワイプして操舵（最大900度連動 / スムーズなカウンターアシスト付き）。
- **マルチスライダーペダル（アクセル・ブレーキ・サイド）**:
  - **上へスライド**: アクセル（スロットル）
  - **左へスワイプ**: フットブレーキ（減速・停止）
  - **右へスワイプ**: サイドブレーキ（ハンドブレーキ / ドリフトのきっかけ作り）
  - **下へスライド**: バック（リバースギア）
- **シフト操作**:
  - **AT（オートマ）** / **MT（マニュアル）** の切り替えに対応。
- **灯火類・ホーン（画面上部のアイコン）**:
  - **LIGHTS**: ヘッドライト・テールランプの点灯
  - **< TURN / TURN >**: 左右ウインカー
  - **HAZARD**: ハザードランプ点滅
  - **HORN**: ハンドル中央をタップ（または長押し）でクラクション吹鳴
- **カメラ視点切り替え**:
  - 後方視点（チェイス）、ドライバー視点（頭部Gフォース連動のNeckFX風コックピット）、車外自由視点などを切り替え可能。

---

## 6. シングルプレイ（フリー走行）
- 車両とコースを選んで **「DRIVE」** を押すと、即座にコースインします。
- 単独走行で思う存分ドリフトの練習やグリップ走行、コースの習熟を楽しめます。

---

## 7. オンラインプレイ（マルチプレイ）
Assetto Corsaのマルチサーバー（acServer / AssettoServer）に参加して他プレイヤーと一緒に走行できます。

1. **事前準備**: サーバーで指定されているコース・車両と同じフォルダ名のMODを導入しておきます。
2. メニューの **「ONLINE」** をタップし、サーバーのアドレスとポート番号を入力して **「GET INFO」** を押します。
3. 空いている車両スロット（スキン枠）を選択して **「JOIN」** で接続します。

> **🔗 URLクリックでのワンタップ参加に対応**  
> DiscordやWebサイト等に貼り付けられたAssetto Corsaサーバーの参加URL（`acmanager://...` や `https://acstuff.ru/s/...` 等）をスマホでタップするだけで、ポケコルが起動してサーバー情報が自動入力されます。

4. **オンライン中の専用機能**:
   - **CHAT**: テキストチャットの送受信（`/` から始まるサーバーコマンド対応）
   - **VIEW**: 他プレイヤーの走行をリアルタイム観戦
   - **TIMES**: 順位表・リアルタイムラップタイムの確認

---

## 8. リプレイ機能（Replay）
走行したセッションの記録・鑑賞・保存ができる専用機能です。

- **リプレイの再生**:
  走行終了後やメニューの **「REPLAY」** から、保存された走行ログを選択して再生できます。
- **多彩なカメラワーク**:
  自車視点だけでなく、迫力ある **コースサイドTVカメラ** や **フリーカメラ** でドリフトフォームや走りをチェックできます。
- **スロー・早送り再生**:
  再生速度の変更やシークバーでの巻き戻し・スキップが可能です。

---

## 9. 注意事項 / 免責事項

- ※本アプリ本体には著作権を有する車両・コース等の商用ゲームデータは一切含まれておりません。
- ※本アプリは、ユーザーが用意したMODファイルを端末内から読み込んで動作します。
- ※本アプリの物理挙動はアセットコルサ公式の挙動とは異なり、モバイル向けに最適化された独自挙動となります。
- ※本プロジェクトは Kunos Simulazioni、Digital Bros、505 Games とは一切関係のない個人による非公式プロジェクトです。
- ※各MODはAssetto Corsa向けに制作されたものであり、本アプリおよび各MOD製作者様は相互に無関係です。MODに関するお問い合わせはご遠慮ください。

---

### クレジット
- **企画 / 開発**: ファイヴ
- **技術協力**: Noel “Excël” Minamino

Copyright 2026 ファイヴ

---

<a name="english"></a>
# POCKET CORSA Quick Start Guide (English)

This is a basic user guide for running Assetto Corsa MODs natively on Android mobile devices with **POCKET CORSA**.

> **⚠️ Notice (Zero Bundled MOD Content)**  
> This application does not include any car or track data. Please supply and place your legally acquired Assetto Corsa MODs on your device storage before playing.

---

## 1. Initial Setup (Permissions, Folder Creation, Path Config)

### Step 1: Grant Storage Permission
1. When you launch the app for the first time, Android's permission dialog/settings screen will automatically appear.
2. Follow the on-screen prompt and allow **"All files access"** (Manage External Storage).  
   *(※This permission is strictly required to scan and load MOD files from your device storage)*

### Step 2: Create Folders & Place MODs
Using a file manager app on your phone (such as Files) or via USB connection to a PC, create three folders in any preferred location (e.g., inside the `Download` folder):

- **Cars Folder** (e.g., `cars`)
- **Tracks Folder** (e.g., `tracks`)
- **Replays Folder** (e.g., `replays`) *(Empty folder where driving logs are automatically saved)*

> **💡 Important: Always Extract/Unzip MODs Before Copying**  
> Compressed archive files (`.zip`, `.rar`, `.7z`, etc.) **cannot be loaded directly**.  
> Always extract them first, and place the extracted folder (the directory containing `.kn5`, `ui/`, `data.acd`, etc.) into each respective folder.

### Step 3: Configure Paths in App Settings
1. Open **"SETTINGS"** from the top menu.
2. Select and browse to your created **Cars**, **Tracks**, and **Replays** folders respectively.
3. Once paths are set, the app will scan and load your MODs.

---

## 2. Options & Settings (SETTINGS)

In **"SETTINGS"** on the main menu, you can configure paths as well as performance and visual options:

- **MOD Path Settings**:
  - `CAR / TRACK / REPLAY PATH`: Change paths for cars, tracks, and replays
  - `RE-SCAN MODS`: Refresh and reload MOD lists after adding or removing files
- **Replay Settings**:
  - `ENABLE REPLAY RECORDING`: Toggle automatic driving log recording ON / OFF
  - `OTHER CARS (ONLINE)`: Set recording frequency of other players during online sessions
- **Graphics & Performance (For Smoother Gameplay)**:
  - `SMALL OBJECT DRAW DISTANCE`: Adjust rendering distance of small props (poles, signs, fences)
  - `MOD TEXTURE QUALITY`: Switch texture resolution and quality
  - `STREET LIGHTS`: Number of active real-time street lights (set to OFF for better performance)
- **System Settings**:
  - `VIBRATION`: Toggle haptic feedback on collisions and curb strikes ON / OFF

---

## 3. Car Selection, Skins & Driving Tuning

1. Tap **"CAR"** on the main menu to choose your vehicle.
2. **Skin Selection**: Switch liveries, colors, and visual variants.
3. **TUNING (Physics & Handling Adjustments)**:  
   Fine-tune your vehicle's physics to match your driving style:
   - **ACCEL MODEL**: Toggle between true-to-life physics **"REAL"** and accessible **"ARCADE"**
   - **POWER**: Scale acceleration and engine output (30% to 400%)
   - **AIR DRAG**: Adjust aerodynamic drag affecting top speed and acceleration (25% to 200%)
   - **LATERAL GRIP**: Tune tyre side-grip and drift slide characteristics (50% to 150%)
   - **BRAKE CURVE**: Adjust pedal curve and braking sensitivity
   - **Presets**: Reset instantly with **"RESET TO DEFAULT"** (standard real values) or **"RESET TO ARCADE"** (easy handling)  
   *(※Online multiplayer automatically enforces REAL baseline settings for fair competition)*

---

## 4. Track & Layout Selection
1. Tap **"TRACK"** on the main menu.
2. Choose a track from your installed MOD collection.
3. If a track contains multiple layouts (drift layout, reverse, short circuit, etc.), you can select your preferred layout.

---

## 5. Driving Controls & Universal Operations

These controls apply to both Single Player and Online Multiplayer:

- **Steering Wheel**:  
  Swipe the steering wheel on the left side of the screen (up to 900° rotation with smooth counter-steer assist).
- **Multi-Slider Pedal (Throttle, Brake, Handbrake)**:
  - **Slide Up**: Throttle (Acceleration)
  - **Swipe Left**: Foot Brake (Deceleration / Stop)
  - **Swipe Right**: Handbrake (E-brake / Drift initiation)
  - **Slide Down**: Reverse gear
- **Transmission**:  
  Toggle between **AT (Automatic)** and **MT (Manual)**.
- **Lights & Horn (Top Screen Icons)**:
  - **LIGHTS**: Turn headlights and taillights ON / OFF
  - **< TURN / TURN >**: Left / Right turn indicators
  - **HAZARD**: Hazard warning flashers
  - **HORN**: Tap or hold the center of the steering wheel to honk
- **Camera View**:  
  Switch between Chase Cam, Driver Cockpit View (NeckFX-style dynamic G-force head movement), and Free Orbit Camera.

---

## 6. Single Player (Free Drive)
- Select your car and track, then tap **"DRIVE"** to enter the track immediately.
- Practice drifting, test grip lines, or learn tracks freely in solo mode.

---

## 7. Online Multiplayer
Connect to unofficial Assetto Corsa servers (**acServer / AssettoServer**) and drive with other players.

1. **Preparation**: Install the exact car and track MODs specified by the server with identical folder names.
2. Tap **"ONLINE"** in the menu, enter the server IP and HTTP port, and tap **"GET INFO"**.
3. Choose an available slot/skin and tap **"JOIN"** to connect.

> **🔗 One-Tap Join via Deep Link URLs**  
> Simply tapping an Assetto Corsa server join link (e.g. `acmanager://...` or `https://acstuff.ru/s/...`) shared in Discord or websites will launch POCKET CORSA and fill in the server details automatically.

4. **Online Features**:
   - **CHAT**: Send and receive text messages (supports `/` server commands)
   - **VIEW**: Spectate other players in real-time
   - **TIMES**: Live leaderboard and lap timing

---

## 8. Replay System
Record, review, and preserve your driving sessions.

- **Playback**:  
  Watch replays right after a run or access saved replays anytime from the **"REPLAY"** menu.
- **Dynamic Camera Angles**:  
  Inspect your drift angles and lines from onboard views, dramatic **Trackside TV Cameras**, or **Free Orbit Cam**.
- **Playback Controls**:  
  Adjust playback speed (slow motion / fast forward) and scrub through the timeline.

---

## 9. Notice & Disclaimer

- ※ This application does not contain any copyrighted car models, track meshes, textures, sounds, or commercial game data.
- ※ This application dynamically loads and runs user-provided MOD files located on device storage.
- ※ Vehicle physics in this application are customized and optimized for mobile devices, and differ from official Assetto Corsa physics.
- ※ This is an unofficial, non-profit community project created by individuals and is not affiliated with, endorsed by, or associated with Kunos Simulazioni, Digital Bros, or 505 Games.
- ※ All MODs are created for Assetto Corsa by third-party creators. The authors of this app and individual MOD creators have no affiliation with each other. Please do not contact MOD authors regarding this application.

---

### Credits
- **Planning & Development**: ファイヴ
- **Technical Assistance**: Noel “Excël” Minamino

Copyright 2026 ファイヴ
