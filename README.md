# Agenda
* 사전준비
* 과제

## 사전준비

* Java SE Development Kit 8 Downloads : http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
* STS 다운로드 : https://spring.io/tools/sts/all
(intelliJ 쓰시는 분들은 쓰셔도 되요)
* github 가입
* sourceTree 설치

## 과제
* 아래 주어진 요구사항을 만족하는 Java 프로그램을 개발해서 본인의 git repository에 올리고 저한테 링크알려주시면 됩니다!

### 요구사항
Java로 학생부 프로그램을 만듭니다.

1. 프로그램을 실행하면 `1. 학생`, `2. 교수`, `3. 과목`, `4. 성적`, `5. 종료` 5가지 선택지가 나오고 종료를 선택하면 프로그램이 종료된다.

2. `학생`을 선택하게 되면 1. 조회, 2. 입력, 3. 삭제 4. 이전 화면을 선택할 수 있다.

  - 조회를 누르면 전체학생들의 번호, 이름, 생년월일(YYMMDD)을 출력
  - 입력을 누르면 번호, 이름, 생년월일을 입력받는다
  - 삭제 버튼을 누르면 학생의 번호를 입력받고 입력받은 학생을 삭제한다
  - 이전화면을 누르면 첫번째 화면으로 돌아간다.

3. `교수`를 선택하게 되면 1. 조회, 2. 입력, 3. 삭제, 4. 이전 화면을 선택할 수 있다.

  - 조회를 누르면 전체교수들의 번호, 이름, 생년월일(YYMMDD, 과목을 출력
  - 입력을 누르면 번호, 이름, 생년월일, 과목명(ex. 컴퓨터공학) 을 입력받는다
  - 삭제를 선택하면 교수의 번호를 입력받고 입력받은 교수를 삭제한다.
  - 이전 화면을 누르면 첫번째 화면으로 돌아간다.

4. `과목`을 선택하게 되면 1. 조회, 2. 입력, 3. 삭제, 이전화면을 선택할 수 있다.

  - 조회를 누르면 전체 과목의 번호, 과목명을 출력
  - 입력을 누르면 과목번호, 과목명을 출력한다
  - 삭제를 선택하면 과목번호를 입력받고 입력받은 과목을 삭제한다
  - 이전 화면을 선택하면 첫번째 화면으로 돌아간다

5. `성적`을 선택하게 되면 1. 학생별 성적조회, 2. 과목별 성적 조회, 3. 성적 입력, 4. 성적 삭제, 5. 이전화면 선택가능하다.

  - 학생별 성적조회를 선택하면 다시 학생의 번호를 입력받고 해당하는 학생의 성적을 성적번호, 학생의번호, 과목번호, 성적순으로 출력한다
  - 과목별 성적조회를 선택하면 다시 과목의 번호를 입력받고 해당하는 과목의 성적을 성적번호, 학생의번호, 과목번호, 성적순으로 출력한다
  - 성적 입력을 선택하면 성적번호, 학생의번호, 과목번호, 성적순으로 입력한다
  - 성적 삭제를 선택하면 다시 성적번호를 입력받고 해당하는 성적을 삭제한다.

* 종료를 선택하기 전까지는 프로그램이 종료되지 않음
* 변수의 type은 자유

다하고 본인의 git repository에 업로드 해주세요!
모르는건 아무때나 물어보셔도 됩니다!