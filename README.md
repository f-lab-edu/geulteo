# :black_nib: ​글터 Geulteo 

<br/>

## :ballot_box_with_check: 프로젝트 개요

글터는 다양한 사람들의 자신의 글과 정보를 공유할 수 있는 텍스트 컨텐츠 공유 플랫폼입니다.

Brunch와 Medium 서비스를 모티브로 제작하였습니다.

<br/>

## :ballot_box_with_check: ​전체적인 구조 (예상)

<img src="https://user-images.githubusercontent.com/48677101/114451680-7cad2b00-9c12-11eb-9c5e-fe37139c8c1a.png" width="80%">
* (Firebase는 제외될 수도 있어 우선 점선으로 처리하였습니다.)

<br/>

## :ballot_box_with_check: 사용 기술 및 개발 환경 (예상)

Java, Spring Boot, IntelliJ, Gradle, MySQL, Redis, Nginx, Firebase, Jenkins, Docker

<br/>

## :ballot_box_with_check: 프로젝트 목표 & 주요 관심사

### **_:heavy_exclamation_mark: 추가 내용들은 프로젝트를 진행하며 추가할 예정입니다._**

### :heavy_check_mark: 공통사항

* 프로젝트 진행과 문서화를 병행하여 기술적 문서 작성에 익숙해지는 것을 목표로 합니다.
* 객체 지향 원리와 다양한 이론을 중점으로 하여 양질의 코드를 작성하는 것을 목표로 합니다.
* 가능한 모든 서비스에 대하여 테스트를 진행하며 최대의 테스트 커버리지를 목표로 합니다.  (추후에 테스트 커버리지 기입)
* 단순한 기능 구현을 넘어서 대용량 트래픽 처리까지 고려한 기능을 구현하는 것을 목표로 합니다.

### :heavy_check_mark: ​브랜치 관리 전략

Git Flow 브랜치 전략을 사용하여 작업 및 버전 관리를 학습할 예정입니다.

<img src="https://user-images.githubusercontent.com/48677101/114451748-93538200-9c12-11eb-99cd-26f3c837b342.png" width="70%">

- Master : 이미 배포했거나 곧 배포할 코드를 관리합니다.
- Develop : 배포할 것을 개발하는 코드를 관리합니다. 배포할 준비가 되면 Master로 merge합니다.
- Feature : 기능 개발을 진행할 때 사용합니다. 기능을 완성할 때까지 유지하고 완성되면 Develop 브랜치로 merge 합니다.
- Release : 배포를 준비하는 브랜치로 배포에 필요한 메타데이터를 준비합니다.
- Hotfix : 배포한 버전에서 생긴 문제를 해결하는 브랜치입니다.

#### Git Flow 브랜치 관리 전략 참고 문헌

:link: A successful Git branching model by Vincent Driessen(https://nvie.com/posts/a-successful-git-branching-model/)

:link: 우아한 형제들 기술 블로그(https://woowabros.github.io/experience/2017/10/30/baemin-mobile-git-branch-strategy.html)

### :heavy_check_mark: 테스트

* (Mockito Framework를 활용하여 테스트 코드 작성)
* Jenkins CI를 적용하여 테스트 자동화

### :heavy_check_mark: DB

* Spring JPA를 사용하나 학습 및 이해를 높이기 위해 Native query로 진행
* 데이터베이스 이중화 Master / Slave

### :heavy_check_mark: CI

* Jenkins를 통해 PR시 자동 Build 및 Test 

### :heavy_check_mark: CD

* Docker 이미지를 제작하여 배포

### :heavy_check_mark: 성능 테스트 및 서버 모니터링

<br/>

## :ballot_box_with_check: [프로젝트 WIKI](https://github.com/f-lab-edu/geulteo/wiki)

(Use Case 및 기술적 이슈에 대한 고민과 해결 과정을 포스팅할 예정입니다.)

<br/>

## :ballot_box_with_check: 프로젝트 화면 설계

(추후에 프로토타입 이미지를 올릴 예정입니다.)

<br/>

## :ballot_box_with_check: DB ERD

(추후에 DB ERD 이미지를 올릴 예정입니다.)

