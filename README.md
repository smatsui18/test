サードパーティライブラリについて、Windows10用インストーラを使用する方法を説明する。


# RealSense SDK

下記から"Intel.RealSense.SDK-WIN10-2.39.0.2337.exe"をダウンロードする。
https://github.com/IntelRealSense/librealsense/releases/tag/v2.39.0

ダウンロードしたファイルを実行する。


# OpenCV

下記から"opencv-4.5.1-vc14_vc15.exe"をダウンロードする。
https://sourceforge.net/projects/opencvlibrary/files/4.5.1/

ダウンロードしたファイルを実行し、インストールしたいディレクトリを指定し展開する。


# Point Cloud Library

下記から"PCL-1.9.1-AllInOne-msvc2017-win##.exe"をダウンロードする。
https://github.com/PointCloudLibrary/pcl/releases/tag/pcl-1.9.1

下記点に注意し、他はインストーラーに従って進めていく。

* [Install Options]において、"Add PCL to the system PATH for all users"にチェックを入れる

* [コンポーネントを選んでください]において、PCLと3rd Party Librariesにチェックを入れる。

途中でOpenNIのインストーラが起動するため、指示に従いインストールすること。