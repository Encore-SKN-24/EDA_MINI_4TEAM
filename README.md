# EDA_MINI_4TEAM


💡팀명


"---"


"우리는 데이터를 분석하는 데서 멈추지 않고, 인사이트를 통해 행동으로 옮깁니다."


✨팀원 소개
| 팀원 | 팀원 | 팀원 | 팀원 | 팀원 |
| --- | --- | --- | --- | --- |
| 김규호 | 김수진 | 박정은 | 이동민 | 정석원 |

-----

## 📌 프로젝트 배경 및 동기: 기록적인 기상 이변 속, 우리 삶은 정말 변했을까?

<img width="1315" height="329" alt="한파" src="https://github.com/user-attachments/assets/040c780b-50c5-4d28-8293-905c9454ee38" />

<img width="1265" height="361" alt="폭염" src="https://github.com/user-attachments/assets/94b19659-4b04-4438-8caf-7fd31b8c170d" />

매년 여름과 겨울이면 어김없이 '역대급'이라는 수식어가 붙은 뉴스 헤드라인을 마주합니다. 기후 위기가 일상이 된 지금, 우리는 문득 이런 의문을 품게 되었습니다.

* **날씨가 활동을 멈추게 하는가:** 생존을 위협할 정도의 무더위와 추위가 정말로 사람들의 외부 활동 의지를 꺾고 있을까?
* **공간의 재발견:** 야외 활동이 힘들어질수록 사람들은 단순히 집 안에 머무는 것이 아니라, 오히려 쾌적한 환경이 보장된 실내 문화 거점으로 모여드는 것이 아닐까?

본 프로젝트는 단순한 수치 계산을 넘어, 날씨라는 거대한 변수가 우리 사회의 즐기는 방식을 어떻게 바꾸고 있는지 확인해보고자 시작되었습니다. 한국 문화예술을 대표하는 **예술의전당** 방문객 데이터를 현미경 삼아, 기상 특보라는 극한 상황 속에서 시민들이 선택한 새로운 일상의 패턴을 분석합니다.

-----

## 🪟 프로젝트 필요성

이제 기후 문제는 환경의 영역을 넘어 우리가 여가를 누리는 생태계 자체를 뒤흔들고 있습니다. 본 프로젝트는 다음 세 가지 측면에서 그 필요성을 강조합니다.

**1. 변화하는 여가 패러다임의 실증적 확인**
기후 위기는 이제 생존의 문제를 넘어 우리가 문화를 향유하고 삶의 질을 유지하는 방식에 실질적인 제약을 걸고 있습니다. 막연한 느낌이 아닌 구체적인 통계 자료를 통해, 날씨가 우리의 문화생활을 어떻게 강제로 재편하고 있는지 그 실태를 분명하게 증명할 필요가 있습니다.

**2. 문화 시설의 새로운 역할 탐색**
극심한 폭염과 한파 속에서 오프라인 문화 공간이 단순히 작품을 감상하는 곳을 넘어, 시민들에게 안전하고 쾌적한 휴식처가 되어주는 '기상 대피소'의 기능을 수행하는지 살펴봅니다. 이를 통해 기후 변화에 유연하게 대응할 수 있는 문화 공간의 운영 전략과 마케팅 방향을 제시하고자 합니다.

**3. 직관을 넘어선 데이터 기반의 행동 분석**
현장의 막연한 추측은 불확실성을 키울 뿐입니다. 기상 정보와 실제 방문객 수 사이의 연관성을 정밀하게 분석하여, 기온 변화에 따라 사람들이 어떻게 움직이는지 그 행동 패턴을 정의합니다. 이는 앞으로 더욱 잦아질 기상이변 시대에 문화 소비 트렌드를 예측하는 중요한 지표가 될 것입니다.

---
### ✅ 데이터 출처
<서울 열린데이터 광장>
https://data.seoul.go.kr/dataList/OA-15969/S/1/datasetView.do#

<공공 데이터 포털>
https://www.data.go.kr/data/15010271/fileData.do

---

### ✅ 데이터 전처리


**예시: 한파, 폭염** 

**예시: 관람 수** 
### 1. 로드된 데이터
<폭염/한파 데이터 로드><br>
<img width="574" height="336" alt="1" src="https://github.com/user-attachments/assets/801376dd-7eae-4d65-a785-dea59fda5738" />
<img width="584" height="280" alt="2" src="https://github.com/user-attachments/assets/3e443ede-0313-48d5-9cd5-3d3c269efd6d" />

<img width="641" height="157" alt="dataload1" src="https://github.com/user-attachments/assets/09e3a17d-eea1-40c4-b9ec-9b9dc326a5ea" />
<img width="674" height="315" alt="dataload2" src="https://github.com/user-attachments/assets/543f9906-0c5f-4f5d-a288-44dcc2b25d52" />

### 2. 이상기후 데이터 날짜 컬럼 추가
<img width="444" height="78" alt="3" src="https://github.com/user-attachments/assets/11b33939-2642-41dc-ba2d-36627e3bfb46" />

< 입장객 (합계) 요일데이터 컬럼 추가 ><br>
<img width="275" height="362" alt="2024_dataframe" src="https://github.com/user-attachments/assets/5ab2ca6f-348d-414c-8fab-58794abbc4f9" />

### 3. 전처리된 이상기후 데이터

<img width="432" height="337" alt="4" src="https://github.com/user-attachments/assets/e8dfae3a-f3a5-44a9-8151-2ab416a8fc22" />

<입장객 (합계) 전처리><br>

<img width="663" height="200" alt="스크린샷 2026-02-03 203044" src="https://github.com/user-attachments/assets/910014e5-c2a8-4910-9667-681428bef556" />
<img width="599" height="401" alt="스크린샷 2026-02-03 203107" src="https://github.com/user-attachments/assets/46df9a58-88f8-47db-85f5-8c83a77a4e61" />

### 4. 병합된 데이터
<img width="527" height="79" alt="5" src="https://github.com/user-attachments/assets/cac4d7f0-091c-48a4-8a1d-2b6d2008414d" /><br>

<img width="243" height="629" alt="6" src="https://github.com/user-attachments/assets/f27dbf83-230a-44d1-a54a-a0f473688e8e" />


### 5. 이상치 제거
서울시의 역대 최고기온 39.6도 최저기온 -23.7도라는 데이터를 기준으로 이상치 제거

<img width="672" height="94" alt="스크린샷 2026-02-03 195803" src="https://github.com/user-attachments/assets/ae0cbaf3-2af7-4889-94ff-088dea75ec91" />


### 6. 이상치 제거된 데이터

<img width="210" height="330" alt="9" src="https://github.com/user-attachments/assets/5edcde18-7ba5-4054-a229-60f2c8b35212" />
<img width="211" height="328" alt="8" src="https://github.com/user-attachments/assets/710dfe1f-237c-42f3-89f4-a5d9d9d34458" />


< 입장객 (합계) 이상치 결측 제거된 데이터>
<img width="1026" height="75" alt="2023_2024_missing_dates" src="https://github.com/user-attachments/assets/626ad993-df88-470e-93bf-d8ac1549bf03" />

<img width="221" height="169" alt="null값" src="https://github.com/user-attachments/assets/b0e5a297-bda2-4672-9679-2eed04ba7de1" />





## 📊시각화 자료


< 폭염, 한파 >


<img width="430" height="488" alt="10" src="https://github.com/user-attachments/assets/b582a004-dc4d-46bb-9212-4cf38be36e8d" />
<img width="431" height="488" alt="11" src="https://github.com/user-attachments/assets/69182957-9ae6-4bc4-a7ff-9784cb1e4754" />
<img width="278" height="394" alt="12" src="https://github.com/user-attachments/assets/5dc1c553-b9dc-4d85-8eb3-4b1be18756fb" />
<img width="278" height="394" alt="13" src="https://github.com/user-attachments/assets/aedbe394-518c-4279-b1fd-46de00b8df43" />
<img width="244" height="470" alt="14" src="https://github.com/user-attachments/assets/7cd65ba7-80b4-4b0c-8f3e-b3826ae52683" />
<img width="244" height="470" alt="15" src="https://github.com/user-attachments/assets/ab73cbe2-8498-4454-88ab-2e9e144099b7" />

<br><br>
< 입장객 (합계) 2023, 2024 >
<br><br>
<img width="573" height="411" alt="2023_boxplot" src="https://github.com/user-attachments/assets/657e6640-338a-4b95-9bb8-86434f2c0207" />
<img width="570" height="409" alt="2024_boxplot" src="https://github.com/user-attachments/assets/c6cbb109-6780-40aa-bf43-66989b706876" />


<img width="735" height="548" alt="2023_heatmap" src="https://github.com/user-attachments/assets/49b8db65-2440-4da5-8074-0f2224ada0a1" />
<img width="733" height="549" alt="2024_heatmap" src="https://github.com/user-attachments/assets/67d2c4c7-f0a8-4562-90ac-efd24da4d158" />


<img width="687" height="546" alt="2023_histogram" src="https://github.com/user-attachments/assets/1d71b5e8-15c7-4d50-ac78-a66a221a8e56" />
<img width="687" height="543" alt="2024_histogram" src="https://github.com/user-attachments/assets/d8d2b7ac-158f-402e-83af-13b9d4e04bb7" />

< 입장객 (합계) 2023,2024 월별 총 입장객>
<img width="1486" height="500" alt="스크린샷 2026-02-03 194724" src="https://github.com/user-attachments/assets/325c8e84-20ea-41ac-8e7f-af0a483cb5e1" />
< 입장객 (합계) 2023,2024 연도별 총 입장객>

<img width="501" height="409" alt="스크린샷 2026-02-03 203522" src="https://github.com/user-attachments/assets/3f3f62b7-c7a9-4853-a5dd-395f87000999" />

인사이트 도출

Insight 1 — 날씨 영향은 제한적
폭염·한파 특보 여부에 따른 관람객 수 변화는 일관된 증감 패턴이 뚜렷하지 않았습니다.

Insight 2 — 변동의 주된 설명요인은 ‘콘텐츠/캘린더’
관람객 수 변동은 기상 요인보다 작품 흥행, 주말/공휴일, 시즌성 등 운영·콘텐츠 요인의 영향이 더 큰 것으로 해석됩니다.

Insight 3 — 실내·예매형 소비의 ‘완충 효과’
예술의전당은 실내 시설이며 관람은 예매 중심의 계획형 소비 특성이 있어, 단기 기상 변화에 대한 수요 민감도가 상대적으로 낮을 수 있음을 시사합니다.

Project Overview

본 프로젝트는 2023~2025년 서울시 기온(시간별/일별) 및 폭염·한파 특보 데이터를 예술의전당 공연·전시 입장객 데이터와 결합하여, 극한 기상이 관람객 수 변화에 미치는 영향을 분석했습니다. 수요 예측/운영 측면에서는 폭염·한파를 핵심 변수로 두기보다, 라인업·요일·시즌성을 중심으로 모델을 구성하고 날씨 변수는 보조적으로 활용하는 전략이 합리적이라고 판단하였고 향후에는 체감온도·강수·미세먼지 등 상세 기상 지표와 예매/취소 데이터를 추가로 결합하고, 타 문화시설로 분석 범위를 확장하여 일반화 가능성을 높일 예정입니다.



🗨️한줄 회고록


