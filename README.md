
# �����ͺ��̽� ȯ�汸�� �ϱ�

�ܵ����ͺ��̽� �ٿ�
-database
-Database 11g Enterprise/Standard Editions 
-Oracle Database Express Edition
-Oracle Database 11g Release 2 Express Edition for Windows 64
-Oracle Database 11gR2 Express Edition for Windows x64 Download
{Note: Unzip the download and run the DISK1/setup.exe}

�ܵ𺧷��� �� �ٿ�
-Developer Tools
-SQL Developer
-Windows 64-bit with JDK 8 included �ٿ� (JDK���� �� �̰� �ٿ�)

�ٿ�ε� ������ �� �� 
OracleXE112_Win64 ��Ŭ�� �� OracleXE112_Win64�� Ǯ�� (����)
sqldeveloper-19.1.0.094.2042-x64 ��Ŭ�� �� sqldeveloper-19.1.0.094.2042-x64�� Ǯ��(����)

OracleXE112_Win64 ���� Ŭ��
-DISK1 �ȿ� setup ����
DB ������ ��Ʈ : 1521
HTTP ������ ��Ʈ : 8080
��ġ �Ϸ� �� OracleXE112_Win64����, ����� �� ���� ����(���ص� ��)

sqldeveloper-19.1.0.094.2042-x64 ���� Ŭ��
c����̺꿡 sqldeveloper �̵� (D����̺꿡 sqldeveloper ->��Ʈ��+X)
sqldeveloper ������� ����ȭ�鿡 ����

## ��ġ Ȯ��

cmd���� Ȯ��
cls - ȭ�� �����
cmd - sqlplus �Է� - ����Ȯ��
user-name : system
password : 1234
-exit
sqlplus system/1234 - ����Ȯ��
-exit
sqlplus / as sysdba

sqldeveloper ����
������� �ʷϻ� + Ŭ��
Name : ������
����� �̸� : system
��й�ȣ : 1234
�Է� �� �׽�Ʈ Ŭ�� -> ���� : ���� ->����

�ٸ������->HR����(���������� ������� ����)
���� �� Ǯ���ֱ�
��ũ��Ʈ
alter user hr IDENTIFIED by hr ACCOUNT unlock;