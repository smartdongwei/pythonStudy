�½�Ŀ¼
mkdir /opt/sanhui/watchdog

�ļ�ȫ�������� 
cp * /opt/sanhui/watchdog
cd /opt/sanhui/watchdog

ת���ű����з�
./dos2unix installservice.sh
./dos2unix uninstallservice.sh

��װ����
./installservice.sh

��������
service watchdog start
service watchdog status

