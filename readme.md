## MDM, MES, SPC, EES, YMS 시스템 정의

### MDM(Master Data Management)
![기준정보 기반의 빅데이터 관리](https://image.samsungsds.com/global/ko/support/insights/mdm_img02.jpg?queryString=20200103093439)

### MES(Manufacturing Execution System)
- 기업의 생산 현장에서 작업 일정, 작업 지시, 품질 관리, 작업 실적 집계 등 제반 활동을 지원하기 위한 관리 시스템

### SPC(Statistical Process Control)
- 공정에 얻어진 DATA(검사 DATA)를 통계적으로 해석하여 샘플 DATA에 의한 평가의 오류를 최소화하기 위한 공정 관리 시스템
- 공정모니터, 통계해석, 관리도, 공정능력
- [정밀측정기기의 단편 지식](http://www.mitutoyokorea.com/upload/Customer/Catalog/2016012710226384.pdf)
- [교정측정분야 입문자를 위한 입문자를 위한 측정기 관리의 이해](https://www.kasto.or.kr/program/%EC%B8%A1%EC%A0%95%EA%B8%B0%EA%B4%80%EB%A6%AC%EC%9D%98_%EC%9D%B4%ED%95%B4.pdf)
 - ![6시그마 관리도](https://t1.daumcdn.net/cfile/tistory/272F0E4258724DE603)
 - ![6시그마와 공정능력](https://t1.daumcdn.net/cfile/tistory/270B9A3758724F7004)

### EES(Equipment Engineering System)
- 장비 Data 기반의 공정 최적화 시스템
- FDC, RMS, APC 
  
  RMS(Recipe Management System)

  제품을 진행하는 Recipe와 Parameter(Recipe의 세부조건)를 통합 관리하여 작업자나 엔지니어의 실수로 인한 Recipe 관련 대형 사고를 예방. 
  RMS는 현장에서 운영하는 Recipe의 변경이력을 관리하고, System에 등록된 Recipe와 설비에 존재하는 Recipe의 Spec을 매 제품 진행시마다 
  Validation 및 Interlock을 통하여 품질사고를 방지.
  
  - 레시피는 경보 또는 제어를 설정하는방법 혹은 룰을 의미합니다.
  - 기본적으로 수집하는 데이터의 임계값을 통해 경보를 설정합니다.
  - 하나의 레시피를 통해 여러 장비의 경보를 설정할 수 있습니다.
  - 특정 경보설정을 선행조건으로 하는 경보를 만들 수 있습니다.
  - 통보받을 사용자, 통보 방식을 설정할 수 있습니다.
  - 통보 방식은 이메일, sms 문자 수신, 앱 사용자의 push메세지 등이 있습니다.
  
  FDC(Fault Detection and Classification) 
  
  설비 Data(각종 센서의 시그널) 실시간으로 수집하고 분석하여 설비의 Fault를 실시간 감지 및 모니터링 한다. 
  이를 통하여 공정이나 설비에서 일어나는 문제를 적시에 대처할 수 있고 누적된 Data의 분석을 통하여 적절한 주기의 PM을 설정하여 
  설비의 장애를 최소화, 각기 다른 Data 간의 상관관계를 파악하고 조합


### YMS(Yield Management System)
- 품질 수율 분석 시스템


