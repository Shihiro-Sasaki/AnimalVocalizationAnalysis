# AnimalVocalizationAnalysis
Script for analyzing animal vocalizations using spectrograms and spectral centroids.

## Description
このリポジトリは、動物の音声データ（.wav）からスペクトログラムおよびスペクトルセントロイドを抽出するためのPythonスクリプトを公開しています。
Google Colaboratory環境で動作し、特定の周波数帯域の可視化や平滑化処理を含みます。

## Features
- Spectrogram Visualization: 1000Hz, 1500Hz, 8000Hzの3段階での可視化
- Spectral Centroid Analysis: 音声の音色特性を示すセントロイドの算出と平滑化
- Batch Processing: 複数ファイルの自動一括処理

## Requirement
実行には以下のライブラリが必要です。
- Python 3.10+
- librosa
- NumPy
- Matplotlib

## Usage
1. Animal_Vocalization_Analysis.ipynb をGoogle Colabで開きます。
2. pathlist に解析したい音声ファイルのパスを入力します。
3. その他ディレクトリ設定などをコメントアウトに従って入力します。
4. すべてのセルを実行すると、spectrogram/ および centroid/ フォルダに解析結果が保存されます。

## Project Info
- **作成者**: 佐々木志洋
- **所属**: 横浜市立横浜サイエンスフロンティア高等学校 16期生 物性科学分野 熱・音・運動コース
- **作成日**: 2026年1月
- **概要**: ヒョウ属(*Panthera*)の研究プロジェクトの一環として開発した音声解析用スクリプト。

## Repository Purpose
本リポジトリは、最終レポート「ヒョウ属(*Panthera*)の鳴き声の共通性と相違性」における解析の透明性と再現性を確保するために公開しています。
