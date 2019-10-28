# Project1_cannyStill

goto: https://github.com/MicrocontrollersAndMore/OpenCV_3_Windows_10_Installation_Tutorial
I'm using visual studio 2019
opencv4.1.1.

changes:

line 25:  cv::cvtColor(imgOriginal, imgGrayscale, cv::COLOR_BGR2GRAY);       // convert to grayscale     it was CV_COLOR_BGR2GRAY
line 38:  cv::namedWindow("imgOriginal", cv::WINDOW_AUTOSIZE);     // note: you can use CV_WINDOW_NORMAL which allows resizing the window		//changed CV_WiNDOW_AUTOSIZE
line 39:  cv::namedWindow("imgCanny", cv::WINDOW_AUTOSIZE);        // or CV_WINDOW_AUTOSIZE for a fixed size window matching the resolution of the image
