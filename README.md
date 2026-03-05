# キャリアコーチング for Claude Code

Claude Codeでキャリアコーチングを体験できるスキルセットです。

---

## 事前準備：Claude Codeのインストール

まだClaude Codeを入れていない場合は先にインストールしてください。

**Node.js（v18以上）が必要です。**
Node.jsがない場合は https://nodejs.org からインストールしてください。

Node.jsが入ったら、以下を実行：

```
npm install -g @anthropic-ai/claude-code
```

---

## ファイルの入手方法（3パターン）

### パターンA：ZIPでダウンロード（Gitなし・一番簡単）

ターミナルやGitを使わずに入手できます。

1. このページ右上の緑色の「**Code**」ボタンをクリック
2. 「**Download ZIP**」を選択
3. ダウンロードされたZIPを解凍する
4. 解凍してできたフォルダを覚えておく

---

### パターンB：GitHub Desktop（GUIアプリ）

ターミナルを使わずにGitを操作できます。

1. https://desktop.github.com からGitHub Desktopをインストール
2. 画面左上「**File**」→「**Clone Repository**」
3. 「URL」タブを選択し、以下を入力：
   ```
   https://github.com/ymiyashiro-cell/career-coaching-claude
   ```
4. 保存先フォルダを選んで「**Clone**」

---

### パターンC：ターミナル・コマンドラインで clone

**Mac / Linux の場合（ターミナル）:**
```bash
git clone https://github.com/ymiyashiro-cell/career-coaching-claude.git
```

**Windows の場合（コマンドプロンプト / PowerShell / Git Bash）:**
```
git clone https://github.com/ymiyashiro-cell/career-coaching-claude.git
```

---

## Claude Codeの起動方法

ファイルを入手したら、そのフォルダでClaude Codeを起動します。

### Mac の場合

ターミナルを開いて：

```bash
cd ダウンロードしたフォルダのパス
claude
```

**Finderから開く場合：** フォルダを右クリック →「フォルダに新しいターミナルを開く」（macOS 10.15以降）

---

### Windows の場合

**コマンドプロンプトで開く場合：**

1. Windowsキー + R を押して `cmd` と入力してEnter
2. 以下を入力（フォルダのパスは自分の環境に合わせて変更）：

```
cd C:\Users\あなたのユーザー名\Downloads\career-coaching-claude
claude
```

**エクスプローラーから開く場合：**

1. ダウンロードしたフォルダを開く
2. フォルダのアドレスバーに `cmd` と入力してEnter
3. コマンドプロンプトが開いたら `claude` と入力してEnter

**PowerShellで開く場合：**

1. フォルダを右クリック →「PowerShellウィンドウをここで開く」
2. `claude` と入力してEnter

---

## 使い方

Claude Codeが起動したら、こう話しかけてください：

```
キャリアコーチングしてほしい
```

または

```
転職について相談したい
```

---

## このスキルでできること

- キャリアの方向性を整理する
- 「やりたいこと」を明確にする
- 転職・副業・フリーランスへの移行を検討する
- 自分の強みと市場価値を言語化する
- 行動を変えるための内省を深める

---

## コーチングの特徴

- **アドバイスを押し付けない** — 質問を通じてあなた自身の答えを引き出す
- **行動を管理しない** — 「何をいつまでに」を宣言させることが目的ではない。認識が変われば行動は自然に変わる
- **仕事とお金を別軸で考える** — やりがいと収入は必ずしもセットにしなくていい

---

## 注意

このリポジトリのファイルはコーチングセッション中に変更されません。
読み取り専用のコーチングスキルとして機能します。
