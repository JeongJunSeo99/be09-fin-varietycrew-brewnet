# Brew Net: 프랜차이즈 주문 관리 시스템
> Brew Net(브루넷)은 프랜차이즈 기업들이 사용할 수 있는 주문관리 시스템(OMS)입니다.<br>
> 본 시스템은 가맹점의 주문을 신속하게 처리하고, 재고 및 물류 관리를 최적화하여 전체적인 운영 효율성을 높이는 것을 목표로 합니다.<br>

> 특징 1. 가맹점 주문 처리<br>
> ➡️ 본사는 모든 가맹점의 주문을 한 곳에서 통합 관리할 수 있어, 주문 상태를 쉽게 파악하고 빠르게 대응할 수 있습니다.<br>

> 특징 2. 거래처 관리<br>
> ➡️ 다양한 거래처를 시스템에 등록하여 거래처로부터 공급받을 수 있는 상품들을 통합적으로 관리할 수 있습니다.<br>

> 특징 3. 알림 시스템<br>
> ➡️ 재고 부족, 주문 상태 변경 등 중요한 이벤트에 대해 알림을 제공하여, 운영자 신속하게 대응할 수 있도록 지원합니다.<br>

> 특징 4. 전자결재 시스템 도입<br>
> ➡️ 가맹점의 주문 승인 및 결재 과정을 전자결재로 처리하여, 종이 문서의 사용을 줄이고 효율성을 높였습니다. 이로 인해 결재 절차가 신속해지고, 문서 관리에 소요되는 시간을 최소화할 수 있습니다.<br>

## 요구사항 정의서
<details>
<summary>회원</summary>

<img width="1575" alt="요구사항_회원1" src="https://github.com/user-attachments/assets/90799603-0f6a-418c-914b-8fe6047047cd">
<img width="1571" alt="요구사항_회원2" src="https://github.com/user-attachments/assets/75287e97-774a-4ec1-8771-d900ec142c38">
</details>

<details>
<summary>통계</summary>

<img width="1571" alt="요구사항_통계" src="https://github.com/user-attachments/assets/6aad33a3-6562-49fd-8904-c06401706577">
</details>

<details>
<summary>창고</summary>

<img width="1574" alt="요구사항_창고" src="https://github.com/user-attachments/assets/3aea40a6-9735-4338-8b06-df15a7134815">
</details>

<details>
<summary>주문</summary>

<img width="1576" alt="요구사항_주문1" src="https://github.com/user-attachments/assets/a8806126-d15a-49a6-823f-8354e3ec086f">
<img width="1573" alt="요구사항_주문2" src="https://github.com/user-attachments/assets/d5fe5505-79ff-4c1a-9e49-e9d0c9b78a91">
</details>

<details>
<summary>상품</summary>

<img width="1582" alt="요구사항_상품" src="https://github.com/user-attachments/assets/d770d64b-d9c7-4acb-8b43-06a9c1ded341">
</details>

<details>
<summary>배송</summary>

<img width="1618" alt="요구사항_배송" src="https://github.com/user-attachments/assets/a3ce9828-b7e6-4b69-a79b-159fddc6b876">
</details>

<details>
<summary>발주</summary>

<img width="1582" alt="요구사항_발주" src="https://github.com/user-attachments/assets/9b609da6-5ab1-483c-8168-808df0e63c82">
</details>

<details>
<summary>반품</summary>

<img width="1579" alt="요구사항_반품1" src="https://github.com/user-attachments/assets/c3f20b18-75a5-4a96-9d46-679ed11f328e">
<img width="1576" alt="요구사항_반품2" src="https://github.com/user-attachments/assets/257f2be8-d56c-4bb2-95e7-b087498c7249">
<img width="1575" alt="요구사항_반품3" src="https://github.com/user-attachments/assets/04fc055a-bcc4-4c77-8f42-016df80ce09f">
</details>

<details>
<summary>문서</summary>

<img width="1579" alt="요구사항_문서" src="https://github.com/user-attachments/assets/234f7af0-ed5e-4ad1-b976-d925f0158193">
</details>

<details>
<summary>교환</summary>

<img width="1574" alt="요구사항_교환1" src="https://github.com/user-attachments/assets/81074a04-887b-43a0-819b-15d611f23f15">
<img width="1579" alt="요구사항_교환2" src="https://github.com/user-attachments/assets/3593a8bb-31ce-4af0-89ae-3294e1ae4728">
</details>

<details>
<summary>공지사항</summary>

<img width="1578" alt="요구사항_공지사항" src="https://github.com/user-attachments/assets/8a0c5bb9-e8d5-4589-8218-ed9bbdc8b8ba">
</details>

<details>
<summary>거래처</summary>

<img width="1576" alt="요구사항_거래처" src="https://github.com/user-attachments/assets/c57f0df2-5e90-481f-a8be-eb0e126fef53">
</details>

<details>
<summary>가맹점</summary>

<img width="1584" alt="요구사항_가맹점" src="https://github.com/user-attachments/assets/b864552d-e5ac-418f-9d28-a99a058621a3">
</details>


## 시스템 아키텍처

## WBS
<img width="1284" alt="wbs" src="https://github.com/user-attachments/assets/f5764ab2-6c93-4f61-a98c-43128c7d6952">

## DDD(Domain Driven Design)
<details>
<summary>Bounded Context</summary>

![ddd_1](https://github.com/user-attachments/assets/0d69838a-89dc-4cc3-a697-6a31f7b5fd57)
![ddd_2](https://github.com/user-attachments/assets/259e06e4-bf14-4673-9fd4-33fa472a462c)
![ddd_3](https://github.com/user-attachments/assets/a02db4f2-dc08-4713-8fb0-50bab0a11178)
![ddd_4](https://github.com/user-attachments/assets/6f916dfc-9315-4315-b5a2-667b9ca3fda3)
</details>

## ERD
<details>
<summary>논리 모델링</summary>
  
![모델링_논리](https://github.com/user-attachments/assets/7fb9fdb7-1190-4a6e-86f7-faf50c34c758)
</details>

<details>
<summary>물리 모델링</summary>

![모델링_물리](https://github.com/user-attachments/assets/e1a65814-1372-45e5-83de-03d8b0e661a1)
</details>

## 화면설계서
<details>
<summary>피그마(Figma)</summary>

![figma_1_창고](https://github.com/user-attachments/assets/87b39ff3-11d6-44a9-8b88-e6225bc9c0de)
![figma_2_발주](https://github.com/user-attachments/assets/f368db63-aea7-45d6-845d-6a178fa228fc)
![figma_3_거래처](https://github.com/user-attachments/assets/02f753ef-204d-4d1e-97da-02a72ec107d8)
![figma_4_주문](https://github.com/user-attachments/assets/a7037315-6f73-4319-ac21-deba16da4ba2)
![figma_5_교환](https://github.com/user-attachments/assets/68b97843-8d89-4646-b112-d612b8c12d8a)
![figma_6_반품](https://github.com/user-attachments/assets/9fa5f08c-6442-4ea2-9cd5-99d141af31fa)
![figma_7_가맹점_주문교환](https://github.com/user-attachments/assets/2f9aa68f-6feb-4c79-a07d-586622ab86b5)
![figma_8_타부서](https://github.com/user-attachments/assets/2c1c7561-1574-4e6f-beef-f5e64030b4e5)
![figma_9_가맹점_반품알림](https://github.com/user-attachments/assets/20b5c62f-3923-4292-aa99-1e4c6a1c2272)
![figma_10_로그인_직원결재라인회사](https://github.com/user-attachments/assets/a41ad47d-8ca8-4f68-a512-11e1bf0d727a)
![figma_11_인감_공지사항](https://github.com/user-attachments/assets/5a95a2a6-aac9-4aca-a383-5e2fc0d1c7af)
![figma_12_가맹점계정](https://github.com/user-attachments/assets/0eff1d86-f163-4efd-91ee-9d028916d1e5)
![figma_13_로그아웃_기안서결재함](https://github.com/user-attachments/assets/0bd105d9-db8d-4da9-bbc4-1fd507f38f7e)
![figma_14_배송](https://github.com/user-attachments/assets/b159a334-cdf4-4d54-ba68-ba4b2d772a07)
![figma_15_상품_통계](https://github.com/user-attachments/assets/373aaffe-d5d3-417a-8450-b8c55e80358e)
</details>

