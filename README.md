# 図を描くためのツール比較用Dev Container環境

## 比較対象

1. [diagrams.net(draw.io)](https://diagrams.net/)
    - 皆さんご存じ図描きツール
    - 図を描くためのUIが優れており、直感的に描くことが可能
    - vscode用の拡張機能（hediet.vscode-drawio）によってvscodeでWeb版と同様なUIが使用できる模様
2. [Diagrams (Diagram as Code)](https://diagrams.mingrammer.com/)
    - Pythonのライブラリdiagramsによって、図をコーディングするため「Diagram as Code」
        - Graphvizを使用するためOS側でもインストールが必要
    - GitHubで差分確認に使用するには便利そうに思えるが、差分が図ではどのような違いになるかがわかるには修行が必要だろう

## 用意したもの

- 開発コンテナでは、拡張機能（hediet.vscode-drawio）のみインストール済み
- コンテナはGraphvizとPythonライブラリ（diagrams）インストール済み

### サンプル
- sample.drawio
    - 普通にダウンロードで保存したもの（SVG）
- sample-png.py
    - デフォルトはPNG出力の模様
- sample-svg.py
    - SVGで周力するよう変更

同じ図ではないところはご愛敬
