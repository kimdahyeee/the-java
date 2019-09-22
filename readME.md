###실습

---
infleran - [더자바, 코드를 조작하는 다양한 방법](https://www.inflearn.com/course/the-java-code-manipulation)

###바이트 조작

1. 바이트 조작 사용 예
    - 프로그램 분석
        - 코드에서 버그 찾는 툴
        - 코드 복잡도 계산
    - 클래스 파일 생성
        - 프록시
        - 특정 API 호출 접근 제한
        - 스칼라 같은 언어의 컴파일러
    - 그밖에도 자바 소스 코드 건리지 않고 코드 변경이 필요한 여러 경우에 사용할 수 있다.
        - 프로파일러 (newrelic)
        - 최적화
        - 로깅
    - ...

2. 바이트 조작 라이브러리
    #####[bytebudy](https://bytebuddy.net)
    - hibernate도 옮기고 있다고 함 
    - mockito