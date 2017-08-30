# face_tracking-Python-
使用現成的人臉辨識函式庫，同時使用撰寫人臉追蹤的程式(Python)  

個人開發環境為(OSX10.12.6 Anaconda Python3.5)  

程式使用的Library:
 1. ageitgey/face_recognition (安裝請參考開發者Adam Geitgey
的 [face_recognition][]，實際上這個Library也是依據dlib開發)
 2. cv2 (版本3.0，使用conda安裝 conda install -c jlaura opencv3 --override-channels)
 3. numpy (版本 1.13.1 Anaconda自帶)
 4. Pillow（版本4.1.1 使用pip安裝 pip install Pillow）
 5. dlib (版本19.4 使用conda安裝即可，實際上face_recognition這個庫本身也會用到dlib)
 6. tk(版本8.5.18)
# Reference
1. [Detecting and tracking a face with Python and OpenCV](https://l.facebook.com/l.php?u=https%3A%2F%2Fwww.google.com.tw%2Famp%2Fs%2Fwww.guidodiepen.nl%2F2017%2F02%2Fdetecting-and-tracking-a-face-with-python-and-opencv%2Famp%2F&h=ATMqHc6rY5UoVLOEtjo9CLv9UvcEhZ46Op5W_iIJadvnuE2HhhhOprzDs24QPHy7AueIb4QPiZFxjVJueVLgHe_-XwCTKz4SlR9KTOQfqolNkMoza7AifSatuxBMxNwRnNe2W0JiUUsXZXwfx7c)
2. [ageitgey/Face Recognition](https://github.com/ageitgey/face_recognition)

# <h1 id='experiment'>實驗目錄<h1>
 1. [用臉玩遊戲](#ex1)
 2. [人臉辨識+追蹤](#ex2)
 3. [用臉玩遊戲(人臉辨識+追蹤)](#ex3)
# <h1 id="ex1">實驗一：用臉玩遊戲(人臉辨識)</h1>  

### [Code連結](https://github.com/kabuto412rock/face_tracking-Python-/blob/master/%E7%94%A8%E8%87%89%E7%8E%A9%E9%81%8A%E6%88%B2(%E4%BD%BF%E7%94%A8face_recognition%E5%92%8Ctkinter%E9%96%8B%E7%99%BC%E4%B8%AD...).ipynb "用臉玩遊戲的Code連結")  
### 程式功能:

畫面為電腦攝影機所拍攝。  
辨識出的臉撞到bad.png圖片會扣分，撞到apple.jpeg會加分  
同時辨識出的人臉會比對是否為Obama.jpg或是zonejia_image.jpg，匡起並標示出名字。  
如果是未知的臉則標出'Unknown'  

### Demo影片(避免離開此頁，請右鍵點選圖片，在新分頁開啟連結)：
[![Demo影片](https://img.youtube.com/vi/RMP7lcNI4Ig/0.jpg)](https://www.youtube.com/watch?v=RMP7lcNI4Ig)  
[返回目錄](#experiment)

# <h1 id="ex2">實驗二：人臉辨識+追蹤</h1>  

### [Code連結](https://github.com/kabuto412rock/face_tracking-Python-/blob/master/faceTracking01.ipynb)

### 程式功能:
同時提供多個人臉辨識，但目前只會追蹤一名特定的使用者  

### Demo影片(避免離開此頁，請右鍵點選圖片，在新分頁開啟連結)：
[![Demo影片](https://img.youtube.com/vi/rYczpeB7o2Q/0.jpg)](https://www.youtube.com/watch?v=rYczpeB7o2Q)  
[返回目錄](#experiment)

 # <h1 id="ex3">實驗三：用臉玩遊戲(人臉辨識+追蹤)</h1>  

### [Code連結](https://github.com/kabuto412rock/face_tracking-Python-/blob/master/%E7%94%A8%E8%87%89%E7%8E%A9%E9%81%8A%E6%88%B2v2(%E4%BA%BA%E8%87%89%E8%BE%A8%E8%AD%98plus%E8%BF%BD%E8%B9%A4).ipynb)

### 程式功能:
把實驗一的遊戲跟實驗二的追蹤結合起來。
畫面上方變成兩個分數，  
左邊分數為我的得分，右邊分數為其他人臉的分數合計。  
### Demo影片(暫無...)

[返回目錄](#experiment)


 [face_recognition]: https://github.com/ageitgey/face_recognition/ "face_recognition的Github"
