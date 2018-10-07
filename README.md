# opencv341-mingw
 OpenCV for windows Complied by mingw-w64.
 
 OpenCV version : 3.4.1
 
 You can use this with Cmake + mingw in windows.
 
 Set "mingw-build\x86\mingw\bin" to your system PATH before use it.
 
 And then add 2 cmake commands in your CMakeList.txt. Example:

 #Change those path if you modify opencv-mingw's path or directory.
 
 include_directories(C://opencv-mingw//mingw-build//include)
 
 link_libraries(C://opencv-mingw//mingw-build//x86//mingw//bin//libopencv_world341.dll)
 

 The java and python directories are come form offical Win pack. 
 
 Offical web:https://opencv.org/opencv-3-4-1.html
