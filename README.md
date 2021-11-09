# AI 알고리즘 실습 팀 프로젝트
## 팀원 소개
> 김영준(조장, XML Processing 담당), 
> 장동현(XML Processing 담당), 
> 이풍규(GUI 담당), 
> 박시언(GUI 담당), 
> 진민규(Database 담당), 
>
>
> 황수현(Database 담당), 
> 박창대(연산자 담당), 
> 김도현(연산자 담당) 
> 이상 8인 1팀입니다.
## 선정한 주제 와 이유
### 주제
> 계산기
### 선정이유
> 저희팀이 계산기를 AI알고리즘 실습의 팀 프로젝트 과제로 선정하게 된 이유는 이때까지 수업에서 배운것중 여러가지를 이용하여 계산기를 표현할 수 있고 GUI를 통해 기능을 구현하기에도 가장 적합하다고 판단하여서 입니다.
## 기능
> 우선 기본적인 기능으로 사칙연산(+, -, /, x) 등 4개와 clear 기능을 기본으로 하며 추가적으로 공학용 계산기에 있는 다양한 기능을 추가할 예정입니다.
## 역할 및 파트분배, 시스템의 동작원리
### GUI : 계산기의 기본외형 및 입력을 신호로 전해주는 역할으로 이풍규, 박시언 이상 두명이 담당하게 되었습니다. 기본적으로 생각중인 외형은 다음 사진과 같습니다.
![11](https://user-images.githubusercontent.com/89117576/140930346-2469577f-3d35-43da-a9f4-28496dc12fbb.PNG)
### XML Processing : GUI를 통해 받은 데이터를 저장하고, 연산자 파트로 분배 해주는 역할으로 김영준, 장동현 이상 두명이 담당하게 되었습니다.
### Database : 다양한 연산자를 미리 변수로 지정하여 연산자 파트에서 연산자를 길게 입력 해야하는 것을 짧게 만들어 주는 역할으로 진민규, 황수현 이상 두명이 담당하게 되었습니다.
### 연산자 : GUI에서 연산자를 선택하면 데이터베이스에서 연산자 관련 변수를 받아서 연산을 한 후, 결과를 XML Processing에 다시 전달하는 역할으로 박창대, 김도현 이상 두명이 담당하게 되었습니다.
### 시스템 동작 원리
>우선 GUI에서 숫자 또는 연산자를 입력받으면 숫자는 XML Processing 으로 저장하고 연산자 파트에 분배하면 연산자 파트에서 선택한 연산자를 Database에서 연산자 변수를 받은 후 연산이 끝난 데이터를 다시 XML Processing에 전달하면 XML Processing에서 다시 GUI의 결과창에 나타내어 주는 방식입니다.
