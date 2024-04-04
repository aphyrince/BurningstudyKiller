# 사용법
1. 본 실행 프로그램을 관리자 권한으로 실행
# 소스 코드
1. #include<windows.h> int main(){system("taskkill /fi \"imagename eq vm*\" /F");return 0;}
# 주의점
1. 본 프로그램은 윈도우즈에서만 작동
2. 재부팅 시 열공백배가 다시 살아남
3. 프로세스 이미지이름이 vm으로 시작하는 프로세스가 무고하게 죽을 수 있음.