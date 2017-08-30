# face_tracking-Python-
使用現成的人臉辨識函式庫，撰寫人臉追蹤的程式(Python)

個人開發環境為(OSX10.12.6 Anaconda Python3.5)
程式使用的Library:
 1. ageitgey/face_recognition (安裝請參考開發者ageitgey的 [face_recognition的Github][])
 2. cv2 (版本3.0，使用conda安裝 conda install -c jlaura opencv3 --override-channels)
 3. numpy (版本 1.13.1 Anaconda自帶)
 4. Pillow（版本4.1.1 使用pip安裝 pip install Pillow）
 5. dlib (版本19.4 使用conda安裝即可，實際上face_recognition這個庫本身也會用到dlib)
 6. tk(版本8.5.18)

# 實驗一：用臉玩遊戲(使用face_recognition和tkinter開發中...).ipynb
### [Code連結](https://github.com/kabuto412rock/face_tracking-Python-/blob/master/%E7%94%A8%E8%87%89%E7%8E%A9%E9%81%8A%E6%88%B2(%E4%BD%BF%E7%94%A8face_recognition%E5%92%8Ctkinter%E9%96%8B%E7%99%BC%E4%B8%AD...).ipynb "用臉玩遊戲的Code連結")

### 程式功能:
畫面為電腦攝影機所拍攝。  
辨識出的臉撞到bad.png圖片會扣分，撞到apple.jpeg會加分  
同時辨識出的人臉會比對是否為Obama.jpg或是zonejia_image.jpg，匡起並標示出名字。  
如果是未知的臉則標出'Unknown'  

### Demo影片(避免離開此頁，請右鍵點選圖片，在新分頁開啟連結)：
[![Demo影片](https://img.youtube.com/vi/RMP7lcNI4Ig/0.jpg)](https://www.youtube.com/watch?v=RMP7lcNI4Ig)


# 實驗二：faceTracking01.ipynb
### [Code連結](https://github.com/kabuto412rock/face_tracking-Python-/blob/master/faceTracking01.ipynb "faceTracking01的Code連結")

### 程式功能:
同時提供多個人臉辨識，但目前只會追蹤一名特定的使用者

### Demo影片(避免離開此頁，請右鍵點選圖片，在新分頁開啟連結)：
[![Demo影片](https://img.youtube.com/vi/rYczpeB7o2Q/0.jpg)](https://www.youtube.com/watch?v=rYczpeB7o2Q)

 [face_recognition的Github]: https://github.com/ageitgey/face_recognition/ "face_recognition的Github"
