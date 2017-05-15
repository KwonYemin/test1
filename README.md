# include<opencv2/opencv.hpp>
int main()
{
     IplImage *img=cvLoadImage("c://lena.bmp");
     cvShowImage('test1',img);
     cvWaitKey();
 
 return 0;
 }
