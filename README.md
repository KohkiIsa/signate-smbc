# signate-smbc
## Overview
SIGNATE　SMBC Group GREEN*DATA Challengeにて、Pythonで前処理・学習・推論・提出ファイル作成まで実装したポートフォリオです。

## Notebooks
- [`notebooks/01_train_main.ipynb`](notebooks/01_train_main.ipynb)：trainデータによるLightGBM/ブートスラップ/k-Fold交差検証/Grid Search/Cat Boostなどについての検証コードです。
- [`notebooks/02_inference_main.ipynb`](notebooks/02_inference_main.ipynb)：testデータによるCatBoostや対数変換など精度測定

## Approach
- **Features**：経度・緯度、waste、TRI/GHG関連（※ノート内で作成）
- **Models**：LightGBM / CatBoost（比較・検証）
- **Validation**：K-Fold（必要に応じてGrid Search等）

## Notes
- データはコンペ規約により本リポジトリには含めていません。
- 実行には各自の環境（Colab等）でデータを配置してください。
