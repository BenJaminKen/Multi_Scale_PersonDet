# Multi_Scale_PersonDet
CPU Real-time Multi-scale Person Detection

# Test steps
## step1
Download model and put it to "model/"  [BaiDu CLoad](https://pan.baidu.com/s/1PNc83cAMWpOQj5pjpQgrUw)
## step2
Download opencv_dll and put it to current directory [BaiDu Cload](https://pan.baidu.com/s/143Ia9lH9BXNiv-hSPSu4Bw)
## step3
Set parameters:
`PersonDet.exe test_type path thresh(0-1)`
like:  PersonDet.exe image test.jpg 0.3  (for image)
or:    PersonDet.exe imgdir D:/test_images/ 0.3  (for imgdir)
or:    PersonDet.exe video test.avi 0.3  (for video)
or:    PersonDet.exe video 0 0.3   (for usbcam)
# Example result
![image](https://github.com/samylee/Multi_Scale_PersonDet/blob/master/image/result.jpg)
# Reference
https://blog.csdn.net/samylee
