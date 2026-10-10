# ch2_3_manage_student

수강생 관리 프로그램 과제를 구현한 Java 콘솔 프로젝트입니다. 수강생·강좌 등록, 요일별 강좌 조회, 수강생 활성 상태와 수강료 변경을 다룹니다.

## 코드 구조

- [Main.java](src/main/java/org/fastcampus/student_management/Main.java): 프로그램 시작과 메뉴 처리
- [application](src/main/java/org/fastcampus/student_management/application/): 수강생·강좌 서비스
- [domain](src/main/java/org/fastcampus/student_management/domain/): 도메인 모델
- [repo](src/main/java/org/fastcampus/student_management/repo/): 저장소 클래스
- [ui](src/main/java/org/fastcampus/student_management/ui/): 입력·출력과 메뉴 처리

Gradle 프로젝트를 IDE에서 열고 `Main.main()`을 진입점으로 코드를 살펴볼 수 있습니다.

## 과제 출처

기존 제목: 수강생 관리 프로그램 과제

https://fastcampus-community-feed.notion.site/ec0c2f76549448f78917774c48db0100
