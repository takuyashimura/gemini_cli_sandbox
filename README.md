# gemini_cli_sandbox

## セットアップ方法

Gemini CLIをサポートするために、以下の手順でGoogle Cloud SDKをセットアップしてください。

1.  **Google Cloud SDKのインストールスクリプトを実行**:
    ```bash
    /workspaces/gemini_cli_sandbox/google-cloud-sdk/install.sh --quiet
    ```

2.  **Google CloudプロジェクトIDの設定**:
    ```bash
    /workspaces/gemini_cli_sandbox/google-cloud-sdk/bin/gcloud config set project 860314883451
    ```

3.  **Google Cloudアカウントの設定**:
    ```bash
    /workspaces/gemini_cli_sandbox/google-cloud-sdk/bin/gcloud config set account 1shi9mu9ra6.0ta9ku1ya3@gmail.com
    ```

**注意**: 必要に応じて、`gcloud auth login` コマンドで認証を行ってください。
