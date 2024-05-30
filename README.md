# sw 오픈소스 과제3
top, ps, jobs, kill 리눅스 명령어

ps

$ ps [옵션]

현재 실행중인 프로세스를 출력한다

a : 터미널과 연관된 프로세스만 출력
x : 터미널과 연관되지 않는 프로세스만 출력
-A : 모든 프로세스 출력 (-e와 동일)
-e : 모든 프로세스 출력
-a : 세션 리더와 커미널과 연관되지 않은 프로세스를 제외하고 모든 프로세스를 출력
p : 지정한 PID 목록의 정보만 출력
-C : 지정한 프로세스의 실행 파일 이름의 정보만 출력
-u : 특정 사용자의 프로세스 정보를 출력
u : 프로세스의 소유자 정보를 함께 출력
l : BSD 형식의 긴 형식으로 출력
e : 프로세스 정보와 함께 프로세스의 환경변수 정보도 출력
-l : 긴 포맷으로 출력
-o : 사용자 정의 형식 지정 가능
f : 프로세스 계층을 텍스트 형식의 트리구조를 보여줌.
-f : 전체 포맷으로 출력

top

$ top [옵션]

시스템 프로세스/메모리 사용 현황을 실시간으로 출력한다

-n 지정한 숫자만큼 화면 출력을 갱신한후 명령
-u 지정한 사용자의 프로세스를 모니터링
-b 출력결과를 파일이나 다른 프로그램으로 전달
-d 화면갱신주기를 초 단위로 설정
-p지정한 PID 프로세스를 모니터링

jobs
$ jobs [options] [job name or number]
현재 돌아가고 있는 백그라운드 프로세스 리스트를 모두 출력한다

kill

$ kill [options] [pid]

프로세스에 종료 시그널은 보낸다
