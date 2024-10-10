# githubPages用のビルド
githubPagesはGzipの回答に対応していないので、
非圧縮の状態でビルドする必要がある

1. ProjectSettingタブ → 左窓"Player" → PublishingSettings → CompressionFormatをDisabledに変更
2. BuildSettingにてWebGLでビルド
3. このリポジトリにコミット