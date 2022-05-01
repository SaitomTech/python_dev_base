# python_dev_base

## 使い方
### 初期設定
1. `.env`ファイルを作成
2. `xxxx`に作成予定のサービス名を入力
  - 作業ディレクトリ（Docker内）
    - `.devcontainer/Dockerfile/`: `WORKDIR`
    - `docker-compose.yml`: `WORKDIR`, `volumes`
    - `.devcontainer/devcontainer.json`: `workspaceFolder`
  - サービス名
    - `docker-compose.yml`: `services`直下
    - `.devcontainer/devcontainer.json`: `service`
  - イメージ名、コンテナ名
    - `docker-compose.yml`: `image`, `container_name`
3. `.devcontainer.json`の`name`に任意のプロジェクト名を入力（VScodeの左下に表示される）
4. 左下のアイコンから`reopen in container`

### 追加設定
#### VScodeのExtensionsの追加方法



## 参考
- [python_repository_simple](https://github.com/yamap55/python_repository_simple)
