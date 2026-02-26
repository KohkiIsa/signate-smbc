# signate-smbc
## Overview
SIGNATE　SMBC Group GREEN DATA Challengeにて、Pythonで前処理・学習・推論・提出ファイル作成まで実装したポートフォリオです。

## Notebooks
- [`notebooks/01_train_main.ipynb`](notebooks/01_train_main.ipynb)：trainデータによるLightGBM/ブートストラップ/k-Fold交差検証/Grid Search/Cat Boostなどについての検証コードです。
- [`notebooks/02_inference_main.ipynb`](notebooks/02_inference_main.ipynb)：testデータによるCatBoostや対数変換など精度測定しました。

## Approach
- **Features**：FacilityName,Latitude,Longitude,LocationAddress,City,State,ZIP,County,FIPScode,PrimaryNAICS,SecondPrimaryNAICS,IndustryType,TRI_Air_Emissions_10_in_lbs,TRI_Air_Emissions_11_in_lbs,TRI_Air_Emissions_12_in_lbs,TRI_Air_Emissions_13_in_lbs,GHG_Direct_Emissions_10_in_metric_tons,GHG_Direct_Emissions_11_in_metric_tons,GHG_Direct_Emissions_12_in_metric_tons,GHG_Direct_Emissions_13_in_metric_tons,GHG_Direct_Emissions_14_in_metric_tons
- **Models**：LightGBM/CatBoost
- **Validation**：K-Fold/Grid Search/ブートストラップ

## Notes
- データそのものは本リポジトリには含めていません。
- 実行には各自の環境（Colab等）でデータを配置してください。
