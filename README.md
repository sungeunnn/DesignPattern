# DesignPattern[2020.04.22-2020.06.17]
## 디자인패턴을 적용하여 뮤직 플레이어 시스템구축

- 개발환경
  - IDE : NetBeans IDB(maven)
  - OS : Window 10
  - 테스팅도구 : 테스트 주도 개발
  - 설계도구 : Bouml
  - 데이터관리 : 파일입출력(IOException)
  - 자바개발환경 : JDK Zulu 11

- 시스템 분석
  - QA 작성 
  - 기능 별 유스케이스 작성 및 패턴 별 다이어그램 산출
  
    - 다이어그램

      - 로그인 : State패턴
    
        ![Login](https://user-images.githubusercontent.com/109890241/222882310-0993ea5b-2ee9-4974-9d99-129dde9bd6b9.PNG)

      - 사용자관리 : Observer패턴
    
        ![management](https://user-images.githubusercontent.com/109890241/222882334-3b575eb6-6710-4155-a10f-560293d9b659.PNG)

      - 음악 재생, 정지 : Bridge패턴
    
        ![브릿지 -재생정지](https://user-images.githubusercontent.com/109890241/222882363-4707375e-946b-480e-a54b-aa12534d0e1a.PNG)

      - 음악 검색기능 : Iterator패턴
    
        ![이터레이터 - 검색](https://user-images.githubusercontent.com/109890241/222882346-bf9f621a-524d-429d-b970-2fbed4ce16a1.PNG)

      - 플레이리스트 : Command패턴
    
        ![playlistUML](https://user-images.githubusercontent.com/109890241/222882400-e79f340a-349f-4adf-bfa6-6fa7bd97e2c0.png)

      - 음악추가 : Builder패턴
    
        ![Information](https://user-images.githubusercontent.com/109890241/222882342-7e96deea-88a6-4d80-a972-cd0904d82fac.png)

      - 음악 이용권 및 음악 구매 : Strategy패턴
    
        ![BuyTicket](https://user-images.githubusercontent.com/109890241/222882366-9a246b51-7acb-481d-9ae4-388f1f61818d.png)

