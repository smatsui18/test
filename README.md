## Windows用インストーラをダウンロードし使用する方法を説明する。


# RealSense SDK

下記から"Intel.RealSense.SDK-WIN10-2.39.0.2337.exe"をダウンロードする。
https://github.com/IntelRealSense/librealsense/releases/tag/v2.39.0

ダウンロードしたファイルを実行する。


# OpenCV

下記から"opencv-4.5.1-vc14_vc15.exe"をダウンロードする。
https://sourceforge.net/projects/opencvlibrary/files/4.5.1/

ダウンロードしたファイルを実行するとopencvフォルダが解凍されるので、例えばC:\opencv 等のディレクトリを指定し解凍する。

システム環境変数 Path に以下を追加する
* C:\opencv\build\bin
* C:\opencv\build\x64\vc15\bin

システム環境変数 OpenCV_DIR に下記を設定する
* C:\opencv\build


# Point Cloud Library

下記から"PCL-1.9.1-AllInOne-msvc2017-win##.exe"をダウンロードする。
https://github.com/PointCloudLibrary/pcl/releases/tag/pcl-1.9.1

下記点に注意し、他はインストーラーに従って進めていく。

* [Install Options]において、"Add PCL to the system PATH for all users"にチェックを入れる

* [コンポーネントを選んでください]において、"PCL"と"3rd Party Libraries"にチェックを入れる。

途中でOpenNIのインストーラが起動するため、指示に従いインストールすること。