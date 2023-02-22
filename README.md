# 3D_프린터_펌웨어_MKS_robin_e3d_V1.1
3D프린터 펌웨어 업데이트

---

기존 Makerbase mks robin e3d v1.1 보드는 marlin펌웨어 2.0.6이 기본 세팅이다.
위 파일은 marlin 펌웨어를 자작 3D프린터 환경의 맞춰서 수정하여 빌드된 펌웨어로 사용시 문제가 생길수 있다. ^^

수정된 Configuration.h파일은 본인의 프린터 환경을 고려하여 수정해야 한다.

* __변경전 프린터 사진__

  <img src="https://user-images.githubusercontent.com/50231941/220642399-d5cc7a98-12ca-487e-a857-fda7f7f94824.jpg" width="500" height="500"/>

* __프린터 환경__

  엔더3 pro 개조 프린터

* __보드__

  ender3보드 --> makerbase mks robin e3d v1.1
  tmc2209 4개 장비
  <img src="https://user-images.githubusercontent.com/50231941/220643423-28742787-64ac-4b8f-a75d-7186a11f1279.jpg" width="500" height="500"/>

* __익스트루더__

  보우덴 방식 --> direct drive변경
  ![direct drive](https://user-images.githubusercontent.com/50231941/220643196-0619b1f1-7cd2-4939-a790-e7e9ce6b8dc4.jpg)

* __z축__

  싱글 z축 --> 듀얼 z축 변경

---

* __추가__

  mks servo 42c 드라이버를 추가
  ![servo42c](https://user-images.githubusercontent.com/50231941/220643606-ca506db8-3418-4b40-8f1c-76894ae722bc.jpg)

  
