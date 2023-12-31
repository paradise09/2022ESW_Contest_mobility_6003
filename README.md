# BCCS (Built-in Cam Cloud System)
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/99b55bc2-3883-43c1-bccf-de8f5154b22d)


## 목차
1. 작품 소개
2. 작품 시연
3. 어플리케이션 UI
4. Hardware 구성
5. Software 구성
6. 기술스택


## 1. 작품소개
### 작품 설명
본 시스템은 차량에서 발생한 이벤트를 별도의 저장소 없이 클라우드에서 관리하여 자료의 유실을 방지하고, 사용자가 해당 정보를 편리하게 관리할 수 있는 플랫폼이다. 주행 중/주차 중 이벤트로 나누어 차량에서 발생하는 다양한 상황으로부터 위험을 감지한 경우 서버와 클라우드에 영상 정보 및 차량 정보 데이터를 실시간으로 전송한다. 이는 어플리케이션에서 실시간으로 사용자에게 제공된다.

### 작품 개요
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/7b9d35a9-38c7-4631-9a46-47f8f4743a2b)

* 센서 영역 : 위험 상황 감지에 필요한 외부 정보를 받아오는 센서들이 작동하는 영역이다.
  
* 빌트인 캠 영역 : 상시 촬영을 하며 위험상확이 감지되었을 때 서버에 영상의 프레임 및 기타 주행 정보를 전송한다.
  
* 서버 영역 : 빌트인 캠에서 수신받은 데이터를 처리하여 클라우드의 데이터 베이스에 저장한다.
  
* 클라우드 영역 : 서버에서 수신받은 데이터를 필요한 정보별로 분류하여 데이터베이스에 저장한다.
  
* 어플리케이션 영역 : 클라우드의 데이터베이스에 접근하여 필요한 정보를 IOS와 안드로이드 어플을 통하여 받아볼 수 있다.

### 작품의 필요성 및 기대효과
* 블랙박스는 데이터를 오직 SD카드에 의존하여 저장한다. 내장된 SD카드등의 플래시메모리는 영상정보를 입력하고 삭제하는 방식으로 사용하기에 장기간 사용 시 고장이 잦다. 그렇기에 SD카드의 오작동으로 인하여 이를 활용하지 못할 가능성이 높다. 하지만 '빌트인 캠 클라우드 시스템'은 위험상황이 감지되면 즉시 녹화하여 클라우드에 업로드 하기 때문에 어플리케이션을 통해 시간과 장소에 구애받지 않고 즉시 확인 가능하다.

* 차량의 형체를 알아볼 수 없을 정도로 큰 사고나 전소 상황의 경우 블랙박스의 데이터 유실 가능성이 매우 높다. 하지만 '빌트인 캠 클라우드 시스템'은 위험 상황이 감지되면 즉시 녹화하여 서버에 업로드하기 때문에 대형 사고 발생 직전까지의 정보를 서버에서 처리할 수 없다. 때문에 빌트인캠이 완전히 파손되기 직전까지의 정보를 클라우드에 전송하고 사고 데이터 유실을 방지한다.

* 전기차의 수요와 공급이 늘어나고 전기차에 대한 소비자의 관심은 나날이 높아지고 있다. 하지만 전기차의 배터리에서 발생하는 화재 이슈는 소비자에게 있어 큰 불안감으로 다가온다. 또한 화재의 원인을 규명하기 위해서는 블랙박스 데이터가 필요하지만 블랙박스가 전소된 경우에는 데이터를 확보할 수 없게 된다. ‘빌트인 캠 클라우드 시스템’은 화재 상황을 위험 상황으로 감지하여 클라우드에 저장한다. 사전에 녹화된 데이터의 유실도 막고 화재 상황까지도 클라우드에 저장되기 때문에 화재 원인 규명 및 데이터 확보에 용이하다.


## 2. 작품시연
### **[시연 영상 (현재 링크에서 확인 가능)](https://www.youtube.com/watch?v=tWeJjAyStjo)**

### 1) 주행상황
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/53df3a7e-18b0-42d2-830c-37f853899aea)

### 2) 주차상황
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/afcfb6b2-289d-4843-b11c-9b06a1fabeba)


## 3. 어플리케이션 UI
### 1) 홈 화면
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/6d356738-780f-4a48-8567-d1d72a6f315f)
### 2) 녹화영상 화면
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/056e341b-3901-4767-9eb6-9bc9250adb25)
### 3) 알림 화면
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/bd59c68a-6567-4592-be7b-d38701d46e4f)
### 4) 설정 화면
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/a1101001-488e-463d-9944-3cd2fb276691)


## 4. Hardware 구성
### 1) 작품 외관
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/a8d4e047-89ef-4440-9a32-3883f215c20a)
### 2) 센서 회로도
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/789f7f68-8b01-45bb-aba1-15b674fa9fe6)
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/41dd40e6-021b-41af-8598-effdc00af07e)


## 5. Software 구성
### Software 전체 구조
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/14951d8e-c29c-4168-9ac8-4647de14bba1)
### 1) 센서 영역 동작 원리
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/86ceb92d-6399-458b-ab8b-6e7db538aeb4)
### 2) 주차 시 위험상황 판단 및 데이터 송신 과정
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/1f20646e-2964-4492-a65d-82603c15e3f6)
### 3) 주행 시 위험상황 판단 및 데이터 송신 과정
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/c04d50d4-c19d-4d7a-b720-ceebe8df5f1e)
### 4) 서버 영역 동작 원리
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/6d808299-d886-4bc3-8877-c2911293a98f)
### 5) 데이터베이스 구조
![image](https://github.com/paradise09/2022ESW_Contest_mobility_6003/assets/99300776/b5beb81b-f9f3-4c85-9c8d-4bcd335ad565)


## 6. 기술 스택
|하드웨어|빌트인 캠|서버|클라우드|어플리케이션|
|:---:|:---:|:---:|:---:|:---:|
|![image](https://camo.githubusercontent.com/4303329d99a984bee1072fe8bb49f8271f4d098435edbf5618d5d6c325aec55c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d41726475696e6f2d3030393739443f7374796c653d666f722d7468652d6261646765266c6f676f3d41726475696e6f266c6f676f436f6c6f723d7768697465) ![image](https://camo.githubusercontent.com/5859172b2d0854f4d70d35118ae1fbb8d92f967ea654f1bb1bdae4a346d03926/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f632d2532333030353939432e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d63266c6f676f436f6c6f723d7768697465) ![image](https://camo.githubusercontent.com/891c1fd9d2ab2adf1053e8514f469b94049769ccd9d2765c8e06e9c1b6da1b8c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f632b2b2d2532333030353939432e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d63253242253242266c6f676f436f6c6f723d7768697465)|![image](https://camo.githubusercontent.com/5a19333ccd9cc87637214d3a5c251c8fa43bf4e18ae84b1b4f78d150350a64c9/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d52617370626572727950692d4335314134413f7374796c653d666f722d7468652d6261646765266c6f676f3d5261737062657272792d5069) ![image](https://camo.githubusercontent.com/a1b2dac5667822ee0d98ae6d799da61987fd1658dfeb4d2ca6e3c99b1535ebd8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f707974686f6e2d3336373041303f7374796c653d666f722d7468652d6261646765266c6f676f3d707974686f6e266c6f676f436f6c6f723d666664643534) ![image](https://camo.githubusercontent.com/01a0e0358e1ce867c57b40f3fc5e037d6f0b7b8946ad9856749b3cf1830c0767/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6f70656e63762d25323377686974652e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6f70656e6376266c6f676f436f6c6f723d7768697465) ![image](https://camo.githubusercontent.com/a1c5e9056e3be1e1058d8517b025af60f61f75395a78245776db71a7703aff9c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6e756d70792d2532333031333234332e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6e756d7079266c6f676f436f6c6f723d7768697465)|![image](https://camo.githubusercontent.com/a1b2dac5667822ee0d98ae6d799da61987fd1658dfeb4d2ca6e3c99b1535ebd8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f707974686f6e2d3336373041303f7374796c653d666f722d7468652d6261646765266c6f676f3d707974686f6e266c6f676f436f6c6f723d666664643534) ![image](https://camo.githubusercontent.com/01a0e0358e1ce867c57b40f3fc5e037d6f0b7b8946ad9856749b3cf1830c0767/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6f70656e63762d25323377686974652e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6f70656e6376266c6f676f436f6c6f723d7768697465) ![image](https://camo.githubusercontent.com/a1c5e9056e3be1e1058d8517b025af60f61f75395a78245776db71a7703aff9c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6e756d70792d2532333031333234332e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6e756d7079266c6f676f436f6c6f723d7768697465)|![image](https://camo.githubusercontent.com/5b148e7e2d5fdb541ea3cae400ea95884b75202ebe9846d996a20971602a8f01/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f46697265626173652d3033394245353f7374796c653d666f722d7468652d6261646765266c6f676f3d4669726562617365266c6f676f436f6c6f723d7768697465)|![image](https://camo.githubusercontent.com/b6d2d66adc138025ea9cdf8444cdc29a588c98d062c263f8651ba6b7ad46fef0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f466c75747465722d2532333032353639422e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d466c7574746572266c6f676f436f6c6f723d7768697465) ![image](https://camo.githubusercontent.com/a0a1ad90011aa02e7e6f32be4998b8843f0884eed20b575c8a2189859550824d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646172742d2532333031373543322e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d64617274266c6f676f436f6c6f723d7768697465) ![image](https://camo.githubusercontent.com/5b7886225855c2c5ac8bcc15effcb289c238c597680d61c24e5e7541af59ee10/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f416e64726f69642d3344444338343f7374796c653d666f722d7468652d6261646765266c6f676f3d616e64726f6964266c6f676f436f6c6f723d7768697465) ![image](https://camo.githubusercontent.com/aed50ad10015be965f5e23eb27a2c2094d335d3cf8b334014c3676ac5425a013/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f694f532d3030303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d696f73266c6f676f436f6c6f723d7768697465)|
