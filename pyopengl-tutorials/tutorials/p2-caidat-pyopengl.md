# Cài đặt PyOpenGL trên Ubuntu 16.04

Thực hiện: Thi Minh Nhựt - Email: thiminhnhut@gmail.com

Thời gian: Ngày 22 tháng 11 năm 2016

## Cách cài đặt

* Cài đặt PyOpenGL trên Ubuntu 16.04: 

	+ Mở cửa sổ Terminal (nhấn `Ctrl + Alt + T`), gõ lệnh sau:		

			$ sudo apt-get install python-opengl
			
		![](https://raw.githubusercontent.com/h3int2um/pyopengl/master/pyopengl-tutorials/images/caidat-pyopengl-ubuntu.png)
		
	+ Kiểm tra cài đặt: gõ các lệnh sau, nếu không báo lỗi nghĩa là cài đặt thành công.
	
			$ python
			
			>>> from OpenGL.GL import *
			
			>>> from OpenGL.GLU import *
		
		![](https://raw.githubusercontent.com/h3int2um/pyopengl/master/pyopengl-tutorials/images/kiemtra-caidat-pyopengl.png)
