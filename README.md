# apriltag-visual-servo-with-gimbal
Visual servoing system with a gimbal-mounted camera using Apriltags. Optional image trimming for faster detection.

## 目次 (Table of Contents)
1. [導入 (Introduction)](#導入-introduction)
2. [依存関係 (Dependencies)](#依存関係-dependencies)
3. [インストール (Installation)](#インストール-installation)
4. [使い方 (Usage)](#使い方-usage)
5. [オプション (Options)](#オプション-options)
6. [ライセンス (License)](#ライセンス-license)

## 導入 (Introduction)

このプロジェクトは、Apriltagsを用いたビジュアルサーボ（視覚に基づく制御）を、ジンバル付きのカメラで行うためのシステムです。画像のトリミングを行うことで、Apriltagsの検出速度を高速化するオプションも備えています。

## 依存関係 (Dependencies)

- Python 3.x
- OpenCV
- Apriltag Library
- Your gimbal's SDK or control software

## インストール (Installation)

### Apriltagのインストール
詳細は[こちら](https://github.com/AprilRobotics/apriltag)を参照してください。

```bash
git clone https://github.com/AprilRobotics/apriltag.git
cd apriltag
make
sudo make install
