# Medical Notes

内科（循環器中心）の臨床メモを MkDocs Material で公開するためのリポジトリです。**医療従事者向け** の参考資料であり、一般向け医療アドバイスではありません。

## ローカルでのプレビュー

```powershell
# 仮想環境を作る（任意）
python -m venv .venv
.\.venv\Scripts\Activate.ps1

pip install -r requirements.txt
mkdocs serve
```

ブラウザで http://127.0.0.1:8000 を開く。

## ビルド

```powershell
mkdocs build --strict
```

## デプロイ

`main` に push すると GitHub Actions が `.github/workflows/deploy.yml` で GitHub Pages にデプロイします。
リポジトリの **Settings → Pages → Source: "GitHub Actions"** に設定してください。

## 構成

```
docs/
├── index.md                 # トップ
├── about/disclaimer.md      # 免責事項
└── cardiology/
    ├── antihypertensives.md # 降圧薬
    ├── antiarrhythmics.md   # 抗不整脈薬
    ├── heart-failure.md     # 心不全治療薬
    └── antithrombotics.md   # 抗凝固・抗血小板薬
```

## 免責

[docs/about/disclaimer.md](docs/about/disclaimer.md) を参照。臨床判断は最新のガイドライン・添付文書を確認のうえ自己責任で行ってください。
