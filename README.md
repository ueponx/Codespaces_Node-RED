# GitHub CodeSpacesを使用したNode-RED開発環境

**GitHub CodeSpaces**を使用した`Node-RED`の開発環境を構築します。

# Node-RED学習環境について

## Node-RED起動方法

### 1. このリポジトリでGitHub Codespacesを作成

環境設定が終わるまで5分程度待機します。

### 2. ターミナルで以下を実行

```bash
node-red
```

### 3. 画面右下に表示されるボタンをクリック

---
## Ollamaの起動設定方法

3回目の講義ではローカルLLM（Large Language Model）環境を使用する予定です。

参考リンク : [Ollama](https://ollama.com/)

### 1. インストール

```bash
curl -fsSL https://ollama.com/install.sh | sh
```

### 2. 起動

⚠️`&`の入力を忘れないこと

```bash
ollama serve &
```

### 3. モデルのダウンロード

```bash
ollama pull 【モデル名】
```

[モデルの検索](https://ollama.com/search)
