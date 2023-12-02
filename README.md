# yolact
(주)일성하이스코와 진행한 경북대학교 인공지능혁신융합대학사업단 산학 프로젝트(CCTV 현장 안전 인공지능 시스템)<br/><br/>
ai-hub에 공개되어 있는 모델(https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=realm&dataSetSn=163)<br>
해당 모델은 resnet101 기반의 yolact모델 사용 (https://github.com/dbolya/yolact)

모델을 (주)일성하이스코 현장에 적용해 봄.<br>
사전 공개 모델이 어느 정도 성능을 보여주면 데이터를 추가해 진행하는 방식으로 하려했으나 <br/>
성능이 좋지 못해 직접 데이터셋 구축해 따로 모델을 만들기로 결정[현재 진행 중(cvat.ai, yolov8 사용), 추후 업로드 예정]<br/>

성능이 좋지 못한 이유는 사전 공개 모델에 쓰인 데이터셋의 시야각과 환경이 (주)일성하이스코의 현장과 많이 다르기 때문.
![스크린샷 2023-12-02 213104](https://github.com/jk9169/yolact/assets/50520447/577a1a6e-a066-4dbc-ae54-01eface1aec9) <br/><br/>
![스크린샷 2023-12-02 212430](https://github.com/jk9169/yolact/assets/50520447/13716f05-0523-4b49-b558-4794c4a7b1dc)
