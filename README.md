# EDA_MINI_4TEAM


💡팀명


"---"


"우리는 데이터를 분석하는 데서 멈추지 않고, 인사이트를 통해 행동으로 옮깁니다."



✨팀원 소개
김규호, 김수진, 박정은, 이동민, 정석원

-----

### 📌 프로젝트 배경 및 동기: 기록적인 기상 이변 속, 우리 삶은 정말 변했을까?

매년 여름과 겨울이면 어김없이 '역대급'이라는 수식어가 붙은 뉴스 헤드라인을 마주합니다. 기후 위기가 일상이 된 지금, 우리는 문득 이런 의문을 품게 되었습니다.

(관련 뉴스 헤드라인 이미지 넣기)

* **날씨가 활동을 멈추게 하는가:** 생존을 위협할 정도의 무더위와 추위가 정말로 사람들의 외부 활동 의지를 꺾고 있을까?
* **공간의 재발견:** 야외 활동이 힘들어질수록 사람들은 단순히 집 안에 머무는 것이 아니라, 오히려 쾌적한 환경이 보장된 실내 문화 거점으로 모여드는 것이 아닐까?

본 프로젝트는 단순한 수치 계산을 넘어, 날씨라는 거대한 변수가 우리 사회의 즐기는 방식을 어떻게 바꾸고 있는지 확인해보고자 시작되었습니다. 한국 문화예술을 대표하는 **예술의전당** 방문객 데이터를 현미경 삼아, 기상 특보라는 극한 상황 속에서 시민들이 선택한 새로운 일상의 패턴을 분석합니다.

---

### 🪟 프로젝트 필요성

이제 기후 문제는 환경의 영역을 넘어 우리가 여가를 누리는 생태계 자체를 뒤흔들고 있습니다. 본 프로젝트는 다음 세 가지 측면에서 그 필요성을 강조합니다.

**1. 변화하는 여가 패러다임의 실증적 확인**
기후 위기는 이제 생존의 문제를 넘어 우리가 문화를 향유하고 삶의 질을 유지하는 방식에 실질적인 제약을 걸고 있습니다. 막연한 느낌이 아닌 구체적인 통계 자료를 통해, 날씨가 우리의 문화생활을 어떻게 강제로 재편하고 있는지 그 실태를 분명하게 증명할 필요가 있습니다.

**2. 문화 시설의 새로운 역할 탐색**
극심한 폭염과 한파 속에서 오프라인 문화 공간이 단순히 작품을 감상하는 곳을 넘어, 시민들에게 안전하고 쾌적한 휴식처가 되어주는 '기상 대피소'의 기능을 수행하는지 살펴봅니다. 이를 통해 기후 변화에 유연하게 대응할 수 있는 문화 공간의 운영 전략과 마케팅 방향을 제시하고자 합니다.

**3. 직관을 넘어선 데이터 기반의 행동 분석**
현장의 막연한 추측은 불확실성을 키울 뿐입니다. 기상 정보와 실제 방문객 수 사이의 연관성을 정밀하게 분석하여, 기온 변화에 따라 사람들이 어떻게 움직이는지 그 행동 패턴을 정의합니다. 이는 앞으로 더욱 잦아질 기상이변 시대에 문화 소비 트렌드를 예측하는 중요한 지표가 될 것입니다.

---




✅ 데이터 출처



https://data.seoul.go.kr/dataList/OA-15969/S/1/datasetView.do#

https://www.data.go.kr/data/15010271/fileData.do




✅ 데이터 전처리


**예시: 함파, 폭염** 


**예시: 관람 수** 
1. 로드된 데이터

<img width="574" height="336" alt="1" src="https://github.com/user-attachments/assets/801376dd-7eae-4d65-a785-dea59fda5738" />
<img width="584" height="280" alt="2" src="https://github.com/user-attachments/assets/3e443ede-0313-48d5-9cd5-3d3c269efd6d" />

2. 기후이상 데이터 날짜 컬럼 추가
<img width="444" height="78" alt="3" src="https://github.com/user-attachments/assets/11b33939-2642-41dc-ba2d-36627e3bfb46" />


3. 전처리된 기후이상 데이터

<img width="432" height="337" alt="4" src="https://github.com/user-attachments/assets/e8dfae3a-f3a5-44a9-8151-2ab416a8fc22" />

4. 병합된 데이터
<img width="527" height="79" alt="5" src="https://github.com/user-attachments/assets/cac4d7f0-091c-48a4-8a1d-2b6d2008414d" />



      

<img width="243" height="629" alt="6" src="https://github.com/user-attachments/assets/f27dbf83-230a-44d1-a54a-a0f473688e8e" />

5. 이상치 제거
<img width="672" height="94" alt="스크린샷 2026-02-03 195803" src="https://github.com/user-attachments/assets/ae0cbaf3-2af7-4889-94ff-088dea75ec91" />



6. 이상치 제거된 데이터

<img width="210" height="330" alt="9" src="https://github.com/user-attachments/assets/5edcde18-7ba5-4054-a229-60f2c8b35212" />
<img width="211" height="328" alt="8" src="https://github.com/user-attachments/assets/710dfe1f-237c-42f3-89f4-a5d9d9d34458" />

📊시각화 자료


이미지
< 그래프 설명 >
<img width="430" height="488" alt="10" src="https://github.com/user-attachments/assets/b582a004-dc4d-46bb-9212-4cf38be36e8d" />
<img width="431" height="488" alt="11" src="https://github.com/user-attachments/assets/69182957-9ae6-4bc4-a7ff-9784cb1e4754" />
<img width="278" height="394" alt="12" src="https://github.com/user-attachments/assets/5dc1c553-b9dc-4d85-8eb3-4b1be18756fb" />
<img width="278" height="394" alt="13" src="https://github.com/user-attachments/assets/aedbe394-518c-4279-b1fd-46de00b8df43" />
<img width="244" height="470" alt="14" src="https://github.com/user-attachments/assets/7cd65ba7-80b4-4b0c-8f3e-b3826ae52683" />
<img width="244" height="470" alt="15" src="https://github.com/user-attachments/assets/ab73cbe2-8498-4454-88ab-2e9e144099b7" />








인사이트 도출
1. 




🗨️한줄 회고록


