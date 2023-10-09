# Yagom-Projects
🐻🏛️ 야곰 아카데미 프로젝트 모음집 🐻🏛️

기간: 2023.04~2023.10 

## 1️⃣ 프로젝트 매니저

[깃헙 저장소](https://github.com/agilestarskim/Yagom-ProjectManager)

### 사용 기술

`SwiftUI` `Realm` `Firebase` `Async/Await` `클린 아키텍처 + MVVM`

### 프로젝트 소개

칸반보드를 이용한 프로젝트 관리 어플리케이션입니다.  
할 일 목록을 만들고 삭제하고 수정할 수 있습니다.  
모든 활동 내역은 로컬 데이터베이스와 리모트 데이터베이스에 저장됩니다.  
간단한 로그인을 통해 계정별로 데이터를 관리할 수 있습니다.  

### Pull Requests & Code Reviews

* [step2-1](https://github.com/yagom-academy/ios-project-manager/pull/304)
* [step2-2](https://github.com/yagom-academy/ios-project-manager/pull/309)
* [step3](https://github.com/yagom-academy/ios-project-manager/pull/315)

## 2️⃣ 일기장

[깃헙 저장소](https://github.com/agilestarskim/Yagom-Diary)

### 사용 기술

`UIKit` `CoreData` `OpenWeather API` `CLLocation`

### 프로젝트 소개

일기장을 만들고 삭제하고 수정할 수 있습니다.  
CoreData를 통해 모든 내용을 영구적으로 저장합니다.  
일기를 작성했던 날짜를 기반으로 날씨 아이콘을 자동으로 추가됩니다.  


### Pull Requests & Code Reviews

* [step1](https://github.com/yagom-academy/ios-diary/pull/119)
* [step2](https://github.com/yagom-academy/ios-diary/pull/133)
* [step3](https://github.com/yagom-academy/ios-diary/pull/141)

## 3️⃣ 박스오피스

[깃헙 저장소](https://github.com/agilestarskim/Yagom-BoxOffice)

### 사용 기술

`UIKit` `URLSession` `Async/Await` `Compositional Layout` `Dynaminc Type` `Device Orientation`

### 프로젝트 소개

박스오피스 open API를 이용해 영화정보 데이터를 가져와 사용자에게 보여줍니다.  
Daum Image API를 통해 영화 포스터도 함께 보여줍니다.  
캘린더를 이용해 특정 날짜의 박스오피스를 확인할 수 있습니다.  
박스오피스 정보를 리스트 형태로 보여줄지 아이콘 형태로 보여줄지 선택할 수 있습니다.  
글자크기와 화면 방향에 따라 영화정보를 효과적으로 보여주기 위해 레이아웃이 자동으로 조절됩니다.  

### Pull Requests & Code Reviews

* [step1](https://github.com/yagom-academy/ios-box-office/pull/68)
* [step2](https://github.com/yagom-academy/ios-box-office/pull/76)
* [step3](https://github.com/yagom-academy/ios-box-office/pull/87)
* [step4](https://github.com/yagom-academy/ios-box-office/pull/99)
* [step5](https://github.com/yagom-academy/ios-box-office/pull/112)

## 4️⃣ 은행 창구 매니저

[깃헙 저장소](https://github.com/agilestarskim/Yagom-BankManager)

### 주요 개념

`GCD` `Operation` `Queue` `Linked List` `Unit Test` `Timer`

### 프로젝트 소개

업무를 수행하는 은행원의 수를 정하여 각 은행원이 고객의 업무를 수행합니다.   
고객 추가 버튼을 누르면 10명의 고객이 생성되어 `대기중` 스택에 쌓이고 해당 고객의 업무를 스레드가 처리하기 시작하면 `업무중` 스택으로 이동합니다. 스레드가 업무를 마치면 `업무중` 스택에서 제거됩니다.  
총 업무시간을 기록하여 상단에 위치한 레이블에 표시합니다. 초기화 버튼을 누르면 업무 중이던 작업, 고객, 총 업무시간이 초기화 됩니다.  

### Pull Requests & Code Reviews

* [step1](https://github.com/yagom-academy/ios-bank-manager/pull/297)
* [step2](https://github.com/yagom-academy/ios-bank-manager/pull/307)
* [step3](https://github.com/yagom-academy/ios-bank-manager/pull/314)

## 5️⃣ 계산기

[깃헙 저장소](https://github.com/agilestarskim/Yagom-Calculator)

### 주요 개념

`UIKit` `Double Stack` `Unit Test` `Error Handling` `문자열 처리` `고차함수`

### 프로젝트 소개

사용자에게 숫자와 연산자를 입력 받으면 모든 내역을 큐에 저장합니다.  
`=` 버튼을 누르면 큐에서 요소들을 꺼내 계산한 후 결과를 보여줍니다.  
이전 계산 결과들을 볼 수 있도록 히스토리에 저장합니다.  

### Pull Requests & Code Reviews

* [step1](https://github.com/yagom-academy/ios-calculator-app/pull/488)
* [step2](https://github.com/yagom-academy/ios-calculator-app/pull/500)
* [step3](https://github.com/yagom-academy/ios-calculator-app/pull/520)

