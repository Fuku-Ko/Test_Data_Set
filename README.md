# 小さなデータセット

## 1. 概要

*   機械学習のテスト用のデータセット。
*   動作テスト用のつもりで作成した。

## 2. ファイル構成

*   'train_data.csv'...教師データ。
*   'test_data.csv'...正解(Subject_F)を省いたテストデータ。
*   'answer_data.csv'...テストデータ。
*   'README'...説明書きのメモ。
*   'LISENCE'...ライセンスについての説明。

## 3. 作成

*   円周率を参照して作成。
*   Subject_CとSubject_Dが相関するように手で調整。
*   Subject_Fは、およそSubject_A * 0.2 +Subject_B * 0.9 -Subject_C * 0.2 -Subject_D * 0.2 +Subject_E * 0.3 +(乱数)となるように調整。
*   (乱数)も円周率を参照して抽出。

## 4. 変数について

*   説明変数...Subject_A, Subject_B, Subject_C, Subject_D, Subject_E
*   目的変数...Subject_F
*   データ数...(train, test) = (15,5)

以上である。
