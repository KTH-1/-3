## sw 오픈소스 과제3

# ps
* 현재 실행중인 프로세스를 출력한다.
* 프로세스의 상태를 나타낸다.

`$ ps [옵션]`

![image](https://github.com/KTH-1/-3/assets/77090149/24de844c-5c19-4829-be6c-d5f5a3ee2ae6)

|옵션|설명|
|---|---|
|a  |터미널과 연관된 프로세스만 출력|
|x  |터미널과 연관되지 않는 프로세스만 출력|
|-A |모든 프로세스 출력 (-e와 동일)|
|-e | 모든 프로세스 출력|
|-a | 세션 리더와 커미널과 연관되지 않은 프로세스를 제외하고 모든 프로세스를 출력|
|p  | 지정한 PID 목록의 정보만 출력|
|-C | 지정한 프로세스의 실행 파일 이름의 정보만 출력|
|-u | 특정 사용자의 프로세스 정보를 출력|
|u  | 프로세스의 소유자 정보를 함께 출력|
|l  | BSD 형식의 긴 형식으로 출력|
|e  | 프로세스 정보와 함께 프로세스의 환경변수 정보도 출력|
|-l | 긴 포맷으로 출력|
|-o | 사용자 정의 형식 지정 가능|
|f  | 프로세스 계층을 텍스트 형식의 트리구조를 보여줌.|
|-f | 전체 포맷으로 출력|

# top
* top 프로그램은 활동 순으로 나열된 프로세스들을 지속적으로 갱신하면서 보여준다.
* 위쪽은 시스템에 대한 전반적인 요약을 보여준다.
* 아래에 테이블로써 CPU 를 사용하는 순으로 프로세스들을 정렬해서 보여준다.

`$ top [옵션]`

![image](https://github.com/KTH-1/-3/assets/77090149/ba45ddcc-bc04-4f27-a7f5-8f0c7ca996de)


|옵션|설명|
|---|---|
|-n |지정한 숫자만큼 화면 출력을 갱신한후 명령|
|-u |지정한 사용자의 프로세스를 모니터링|
|-b |출력결과를 파일이나 다른 프로그램으로 전달|
|-d |화면갱신주기를 초 단위로 설정|
|-p |지정한 PID 프로세스를 모니터링|

# jobs
* 현재 돌아가고 있는 백그라운드 프로세스 리스트를 모두 출력한다.
* +는 스택의 가장 위에 있다는 뜻이다.
* -는 바로 그다음 밑에 있다는 뜻이다.

`$ jobs [options] [job name or number]`

![image](https://github.com/KTH-1/-3/assets/77090149/5828c3aa-ab33-4d5e-9fcf-4736d1cc7dc0)


|옵션|설명|
|---|---|
|-l | 프로세스 ID와 함께 잡 목록을 출력|
|-n | 마지막로 알림 이후 변경된 잡만 출력|
|-p | 잡의 프로세스 ID만 출력|
|-r | 실행 중인 잡만 출력|
|-s | 중지된 잡만 출력|

# kill
* 프로세스에 종료 시그널은 보낸다.
* 명령어를 실행함으로써 프로세스가 시작되고 그 프로세를 제어하기 위하여 사전에 정의된 시그널이 존재한다.

`$ kill [options] [pid]`

![image](https://github.com/KTH-1/-3/assets/77090149/5de51d64-8c0e-491b-8078-51c7f0a033cc)

|옵션|설명|
|---|---|
|-signal, -s signal | 지정한 시그널을 보냄|
|-l                 | 사용 가능한 시그널의 목록을 출력|

# 자료 출처
https://inpa.tistory.com/entry/LINUX-%F0%9F%93%9A-%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4-%EA%B4%80%EB%A6%AC-%EB%AA%85%EB%A0%B9%EC%96%B4-%F0%9F%92%AF-%EC%A0%95%EB%A6%AC-Foreground-Background
