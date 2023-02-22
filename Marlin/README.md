# 3D_프린터_펌웨어_MKS_robin_e3d_V1.1
3D프린터 펌웨어 업데이트

---

기존 Makerbase mks robin e3d v1.1 보드는 marlin펌웨어 2.0.6이 기본 세팅이다.
위 파일은 marlin 펌웨어를 자작 3D프린터 환경의 맞춰서 수정하여 빌드된 펌웨어로 사용시 문제가 생길수 있다. ^^

수정된 Configuration.h파일은 본인의 프린터 환경을 고려하여 수정해야 한다.

* __프린터 환경__

  엔더3 pro 개조 프린터

* __보드__

  ender3보드 --> makerbase mks robin e3d v1.1
  tmc2209 4개 장비

* __익스트루더__

  보우덴 방식 --> direct drive변경

* __z축__

  싱글 z축 --> 듀얼 z축 변경

---

* __추가__

  mks servo 42c 드라이버를 추가
  
 ---

* MKS V1.1 Board

To compile Marlin for this board set `MOTHERBOARD` to `BOARD_MKS_ROBIN_E3_V1_1` (not `BOARD_MKS_ROBIN_E3`).

Changes in MKS Version 1.1:
  - `Z_STEP_PIN` is now `PC14`
  - `Z_DIR_PIN` is now `PC15`
  - The EEPROM on the board is the AT24C32D (32KB)

Full specs and documentation for MKS E3 hardware can be found at https://github.com/makerbase-mks/MKS-Robin-E3-E3D/tree/master/hardware
