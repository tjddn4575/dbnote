
# 데이터베이스 환경구축 하기

●데이터베이스 다운
-database
-Database 11g Enterprise/Standard Editions 
-Oracle Database Express Edition
-Oracle Database 11g Release 2 Express Edition for Windows 64
-Oracle Database 11gR2 Express Edition for Windows x64 Download
{Note: Unzip the download and run the DISK1/setup.exe}

●디벨로퍼 툴 다운
-Developer Tools
-SQL Developer
-Windows 64-bit with JDK 8 included 다운 (JDK없을 때 이거 다운)

다운로드 폴더에 들어간 후 
OracleXE112_Win64 우클릭 후 OracleXE112_Win64에 풀기 (압축)
sqldeveloper-19.1.0.094.2042-x64 우클릭 후 sqldeveloper-19.1.0.094.2042-x64에 풀기(압축)

OracleXE112_Win64 폴더 클릭
-DISK1 안에 setup 실행
DB 리스너 포트 : 1521
HTTP 리스너 포트 : 8080
설치 완료 후 OracleXE112_Win64폴더, 압축된 것 까지 삭제(안해도 됨)

sqldeveloper-19.1.0.094.2042-x64 폴더 클릭
c드라이브에 sqldeveloper 이동 (D드라이브에 sqldeveloper ->컨트롤+X)
sqldeveloper 보내기로 바탕화면에 생성

## 설치 확인

cmd에서 확인
cls - 화면 지우기
cmd - sqlplus 입력 - 버전확인
user-name : system
password : 1234
-exit
sqlplus system/1234 - 접속확인
-exit
sqlplus / as sysdba

sqldeveloper 접속
좌측상단 초록색 + 클릭
Name : 관리자
사용자 이름 : system
비밀번호 : 1234
입력 후 테스트 클릭 -> 상태 : 성공 ->접속

다른사용자->HR유저(교육용으로 만들어진 계정)
계정 락 풀어주기
워크시트
alter user hr IDENTIFIED by hr ACCOUNT unlock;