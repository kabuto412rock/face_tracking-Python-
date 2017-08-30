# face_tracking-Python-
使用現成的人臉辨識函式庫，撰寫人臉追蹤的程式(Python)

個人開發環境為(OSX10.12.6 Anaconda Python3.5)
程式使用的Library:
 1. face_recognition (最新安裝參考 [face_recognition的Github][])

 2. cv2 (版本3.0，使用conda安裝 conda install -c jlaura opencv3 --override-channels)
 3. numpy (版本 1.13.1 Anaconda自帶)
 4. Pillow（版本4.1.1 使用pip安裝 pip install Pillow）
 5. dlib (版本19.4 使用conda安裝即可，實際上face_recognition這個庫本身也會用到dlib)
 6. tk(版本8.5.18)

## face_tracking-Python-/用臉玩遊戲(使用face_recognition和tkinter開發中...).ipynb
### 程式功能:
畫面為電腦攝影機所拍攝。  
辨識出的臉撞到bad.png圖片會扣分，撞到apple.jpeg會加分  
同時辨識出的人臉會比對是否為Obama.jpg或是zonejia_image.jpg，匡起並標示出名字。  
如果是未知的臉則標出'Unknown'  
### Demo影片：
[![Demo影片](https://img.youtube.com/vi/RMP7lcNI4Ig/0.jpg)](https://www.youtube.com/watch?v=RMP7lcNI4Ig)

<a href="https://www.youtube.com/watch?v=RMP7lcNI4Ig" target="_blank"><img src="https://img.youtube.com/vi/RMP7lcNI4Ig/0.jpg"></img></a>



 [face_recognition的Github]: https://github.com/ageitgey/face_recognition/ "face_recognition的Github"
