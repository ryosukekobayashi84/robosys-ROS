# ロボットシステム学　課題２  
***20c1044　小林凌介***
## 概要 
ROSプログラミング
## 動画  
実際に動作している動画  
<https://youtu.be/ClbIgq_lgf8>
## 使用するもの
  -Raspberry Pi 4  
  -PC   
  ## 環境  
  -Ubuntu 20.04 LTS 
  -ROS: robot operating system
  ## 使い方  
リポジトリをクローンしてローカルリポジトリの作成  
`$ git clone https://github.com/ryosukekobayashi84/robosys-ROS.git`  
`$ cd robosys-ROS`  
ubuntuは同時に起動して使うので準備しておくとよい、起動すための準備を順に記載する。  
端末１  
`$ roscore` //rosの起動   
端末2  
`$ cd scripts`  
`$ chmod +x count.py` //パーミッションの設定  
`$ rosrun mypkg count.py`　//確認したら＾C  
`$ chmod +x twice.py` //パーミッションの設定  
`$ rosrun mypkg count.py`   

端末3  
 `$ rosnode list`        
 `$ rostopic list `　　  
 `$ rostopic echo /count_up` //確認したら＾C 
 `$ rostopic echo /twice`  
 ## LICENSE  
  BSD 2-Clause "Simplified" License 
 ## Author
 Ryuichi Ueda 
