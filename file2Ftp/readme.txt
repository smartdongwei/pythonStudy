��Ҫ�Լ���װthreadpool ģ��

file2ftp.py     �ѱ����ļ��ϴ���ftp��
DailyStatisticsLog.py   ͳ��ģ���Լ�ɾ������ ��־ģ��
config.ini      ������Ϣ


�������ļ���
[ftpMessage]
host = 192.168.63.101
port = 21
username = test
passwd = test    
ftpRootPath =  /CD/DEMO/     #ftp�洢�ĸ�Ŀ¼

[fileMessage]
fileRoot = E:\\ceshi            #�����ļ��洢�ĸ�Ŀ¼
needUploadFileHouZhui = txt     #��Ҫ�ϴ����ļ���׺��   ���Ϊ�գ����ϴ����е��ļ�
LinShiHouZhui = .img            #��ʱ��׺����
isBackUp = 1                    #  1  ��Ҫ����    0 ����Ҫ����
backUpPath = E:\\temp           #��Ҫ���ݵ�·��
threadPoolNumber = 3            # �̳߳ص��߳���  һ�㲻����Ϊ����Ŀ¼��Ŀ¼��


[statistics]
logSaveDays= 10                  #��Ҫ����ȷ����־��Ҫ���������
backUpSaveDays = 10              #��Ҫ����ȷ������Ŀ¼��Ҫ���������    �������Ҫɾ��������Ҫд


����־Ŀ¼������������־
statistics_20180516.log              #����ÿ���ϴ�������־
upload_20180516.log                  #ÿ�νű�����ʱ���ɵ���־


�ڽű�����ʱ�ᴴ��һ��  ��ʱ�ļ� needRemove.md  ����ű����н�������ļ�û�б�ɾ����˵���������⣬�ֶ�ɾ�����ļ�
�ڽű����й����в��ù�����ļ�
