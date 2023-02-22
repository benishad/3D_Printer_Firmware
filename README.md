# 3D_프린터_펌웨어_MKS_robin_e3d_V1.1
3D프린터 펌웨어 업데이트

기존 Makerbase mks robin e3d v1.1 보드는 marlin펌웨어 2.0.6이 기본 세팅이다.
위 파일은 marlin 펌웨어를 자작 3D프린터 환경의 맞춰서 수정하여 빌드된 펌웨어로 사용시 문제가 생길수 있다. ^^

수정된 Configuration.h파일은 본인의 프린터 환경을 고려하여 수정해야 한다.

##프린터 환경

엔더3 pro 개조 프린터

###보드
ender3보드 --> makerbase mks robin e3d v1.1
tmc2209 4개 장비

###익스트루더
보우덴 방식 --> direct drive변경

###z축
싱글 z축 --> 듀얼 z축 변경

###추가
mks servo 42c 드라이버를 추가
