��sdk����������ֱ������bin�е��ļ����в������У������������������ķֱ��ʣ�Ĭ��Ϊ1280��1024�����VideoCapture����ʼ�ɼ���SnapShot�����ͼ����Ŀ¼�е�snap.jpg.
�������������ʱ���ᱣ��¼��Ϊh.264���롣

�������vs2010��д��ʹ����OpenCV���е���ʾ������ͼƬ��������Ƶ�ļ��Ĺ��ܡ�

API������CCTAPI.h�С�

CCT_API int startCap(int height,int width,LPMV_CALLBACK2 CallBackFunc);
��ʼ�ɼ������У�
int height���ɼ�ͼ��ĸ߶�
int width:�ɼ�ͼ��Ŀ��
LPMV_CALLBACK2 CallBackFunc���ص�����������ʹ�÷����ڴ����У�

CCT_API int stopCap();
ֹͣͼ��ɼ���

CCT_API int setMirrorType(DataProcessType mirrortype);
����ͼ��ľ���ʽ������
DataProcessTypeΪ�Զ���ö������
enum DataProcessType
{
	Normal_Proc,Xmirror_Proc,Ymirror_Proc,XYmirror_Proc
};