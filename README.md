# apriltag-visual-servo-with-gimbal
Visual servoing system with a gimbal-mounted camera using Apriltags. Optional image trimming for faster detection.

目次 (Table of Contents)
導入 (Introduction)
依存関係 (Dependencies)
インストール (Installation)
使い方 (Usage)
オプション (Options)
ライセンス (License)
導入 (Introduction)
このプロジェクトは、Apriltagsを用いたビジュアルサーボ（視覚に基づく制御）を、ジンバル付きのカメラで行うためのシステムです。画像のトリミングを行うことで、Apriltagsの検出速度を高速化するオプションも備えています。

依存関係 (Dependencies)
Python 3.x
OpenCV
Apriltag Library
Your gimbal's SDK or control software
インストール (Installation)
Apriltagのインストール
詳細はこちらを参照してください。

bash
Copy code
git clone https://github.com/AprilRobotics/apriltag.git
cd apriltag
make
sudo make install
このリポジトリのクローン
bash
Copy code
git clone https://github.com/your-username/apriltag-visual-servo-with-gimbal.git
cd apriltag-visual-servo-with-gimbal
使い方 (Usage)
基本的な使用方法は以下のとおりです。

bash
Copy code
python3 start_visual_servo.py
オプションでトリミングを有効にする
bash
Copy code
python3 start_visual_servo.py --use_trimming=True
オプション (Options)
--use_trimming: 画像トリミングを有効にする（デフォルトはFalse）
ライセンス (License)
このプロジェクトはMITライセンスの下で公開されています。詳細はLICENSEファイルを参照してください。
