# 琥珀虛顏 ADB 驗證碼計算器 (Hupo Xuyan ADB Auth Calculator)

[繁體中文](#繁體中文) | [简体中文](#简体中文) | [English](#english) | [日本語](#日本語)

---

## 繁體中文

這是一個專為狗尾草（Gowild）人工智能藍牙音箱「HE琥珀虛顏」設計的 ADB 連線驗證碼網頁工具。只需透過瀏覽器，即可計算出 Auth Key，幫助您透過 ADB 連入音箱並取得 root 權限。

由於官方伺服器已停止服務（服務商跑路），原本的琥珀虛顏 APP 已無法使用。但透過本工具解鎖並取得 root 權限後，這台設備將充滿可玩性！您可以自由進行軟硬體改裝，例如：**開發專屬 APP 替換成自己喜歡的 3D 模型，或是將其改造成接入大語言模型 (LLM) 的智能語音助理**。

👉 **[點我直接使用線上計算器](https://nekodakohaku.github.io/hupo-xuyan-speaker-adb-auth/)**

### 📖 使用方法

1. 將音箱開機，並使用 USB 線連接至電腦。
2. 嘗試透過電腦終端機（CMD/Terminal）執行任意 ADB 指令（例如：`adb shell` 或 `adb root`）。
3. 音箱終端機會拒絕連線，並顯示一串挑戰訊息，例如：`Who are you ? (O_O)??? (數字)`。
4. 將括號內的 **數字** 複製並輸入到本網頁計算器中。
5. 獲取對應的 Key 後，在終端機執行指令：`adb shell "auth:您的Key"` 即可成功連線。
6. 若驗證成功，終端機會顯示 `Welcome home . O(^_^)O~~`。
7. 接著輸入 `adb root` 以獲取 root 權限。
   *(注意：執行此指令後 adb 會以 root 權限重新啟動，請**重複上述 1~5 的步驟**再次進行驗證)*

> **💡 提示：** 每次音箱重開機，都需要重新計算驗證碼並解鎖 ADB，或是重新獲取 root 權限。

---

## 简体中文

这是一个专为狗尾草（Gowild）人工智能蓝牙音箱“HE琥珀虚颜”设计的 ADB 连接验证码网页工具。只需通过浏览器，即可计算出 Auth Key，帮助您通过 ADB 连入音箱并取得 root 权限。

由于官方服务器已停止服务（服务商跑路），原本的琥珀虚颜 APP 已无法使用。但通过本工具解锁并取得 root 权限后，这台设备将充满可玩性！您可以自由进行软硬件改装，例如：**开发专属 APP 替换成自己喜欢的 3D 模型，或是将其改造成接入大语言模型 (LLM) 的智能语音助手**。

👉 **[点我直接使用线上计算器](https://nekodakohaku.github.io/hupo-xuyan-speaker-adb-auth/)**

### 📖 使用方法

1. 将音箱开机，并使用 USB 线连接至电脑。
2. 尝试通过电脑终端（CMD/Terminal）执行任意 ADB 指令（例如：`adb shell` 或 `adb root`）。
3. 音箱终端会拒绝连接，并显示一串挑战信息，例如：`Who are you ? (O_O)??? (数字)`。
4. 将括号内的 **数字** 复制并输入到本网页计算器中。
5. 获取对应的 Key 后，在终端执行指令：`adb shell "auth:您的Key"` 即可成功连接。
6. 若验证成功，终端会显示 `Welcome home . O(^_^)O~~`。
7. 接着输入 `adb root` 以获取 root 权限。
   *(注意：执行此指令后 adb 会以 root 权限重新启动，请**重复上述 1~5 的步骤**再次进行验证)*

> **💡 提示：** 每次音箱重启，都需要重新计算验证码并解锁或是重新获取 root 权限。

---

## English

This is a web-based ADB authentication key calculator designed for the "HE Hupo Xuyan" (HE琥珀虚颜) AI Bluetooth speaker by Gowild. This tool allows you to calculate the Auth Key via your browser to bypass the ADB lock and gain root access.

Since the official servers have been shut down, the original companion app is no longer functional. However, by unlocking the device and gaining root access with this tool, you can unlock its full modding potential! You can repurpose the hardware by **developing custom apps to replace the built-in 3D avatar with your own models, or integrate Large Language Models (LLMs) to create a custom smart voice assistant**.

👉 **[Click here to use the online calculator](https://nekodakohaku.github.io/hupo-xuyan-speaker-adb-auth/)**

### 📖 How to Use

1. Turn on the speaker and connect it to your computer via a USB cable.
2. Try executing any ADB command in your terminal (e.g., `adb shell` or `adb root`).
3. The terminal will reject the connection and display a challenge message like: `Who are you ? (O_O)??? (Number)`.
4. Copy the **Number** in the parentheses and enter it into the web calculator.
5. Get the corresponding Auth Key and execute the following command in your terminal: `adb shell "auth:YourKey"`.
6. If the authentication is successful, the terminal will display: `Welcome home . O(^_^)O~~`.
7. Next, enter `adb root` to gain root privileges.
   *(Note: After executing this command, the adb daemon will restart with root privileges. You must **repeat steps 1-5** to authenticate again.)*

> **💡 Tip:** You will need to re-enter a new auth key every time the speaker reboots or when switching to root mode.

---

## 日本語

これは、GowildのAIスマートスピーカー「HE琥珀虚顔」向けのADB接続認証コードを計算するWebツールです。ブラウザ上でAuth Keyを計算し、ADB経由でスピーカーに接続してroot権限を取得することができます。

公式サーバーがサービスを終了したため、純正のコンパニオンアプリは現在使用できません。しかし、このツールでロックを解除しroot権限を取得することで、端末を自由にカスタマイズできるようになります！例えば、**自作アプリを導入してお気に入りの3Dモデルに置き換えたり、LLM（大規模言語モデル）を組み込んで独自のAI音声アシスタントに改造したりすることが可能**です。

👉 **[オンライン計算機を使用する](https://nekodakohaku.github.io/hupo-xuyan-speaker-adb-auth/)**

### 📖 使用方法

1. スピーカーの電源を入れ、USBケーブルでPCに接続します。
2. ターミナルで任意のADBコマンド（例：`adb shell` や `adb root`）を実行します。
3. 接続が拒否され、ターミナルに `Who are you ? (O_O)??? (数字)` のようなチャレンジメッセージが表示されます。
4. カッコ内の **数字** をコピーし、このWeb計算機に入力します。
5. 対応するKeyを取得したら、ターミナルで `adb shell "auth:取得したKey"` を実行します。
6. 認証に成功すると、`Welcome home . O(^_^)O~~` と表示されます。
7. 続いて `adb root` を入力し、root権限を取得します。
   *(注意：このコマンドを実行すると、adbはroot権限で再起動します。**再度手順 1～5 を繰り返し**、再認証を行ってください)*

> **💡 ヒント:** スピーカーを再起動するたび、またはrootモードに切り替えるたびに、認証コードを再計算して入力する必要があります。
