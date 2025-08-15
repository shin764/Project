# 팀명 : 실버브릿지

### 1. 프로젝트 개요
 주제 : 공공데이터 및 Open AI 기반 고령자 복지 정보 통합 서비스
   -  개인 맞춤형 복지 프로그램을 추천하는 서비스 제공
   -  모바일 앱 기반의 실시간 정보를 통합 기능 제공
   -  고령층 전용 UI/UX를 설계하여 쉽고 편한 서비스 제공
   -  커뮤니티 기능을 탑재하여 소통을 증진
### 2. 주요 기능
#### 개발목표
  - 본인에게 맞는 복지 프로그램을 도와주는 웹/앱 구현
  - 프로그램 후기를 볼 수 있는 랭킹 시스템이 도입된 커뮤니티 서비스 구현
#### 개발내용
![image](https://github.com/user-attachments/assets/e7e4309b-004a-4145-95a3-3c522e330c08)
### 3. 개발환경
![image](https://github.com/user-attachments/assets/a15b4f2f-f1f2-4704-8b0a-b08090acfdc8)
### 4. 유스케이스
![image](https://github.com/user-attachments/assets/5157ef8f-85f6-4c78-9d86-afb5e978d756)
### 5. 서비스 아키텍처
![image](https://github.com/user-attachments/assets/a5f406ac-b289-4a19-8277-ba5268bd6f9b)
### 6. ER 다이어그램
![image](https://github.com/user-attachments/assets/fa6ba2d3-7781-4995-9df7-3350138b3a62)
### 7. 모델 구현
![image](https://github.com/user-attachments/assets/cac79d59-3f55-4e9d-98d1-42e6616ed892)
### 8. WEB/앱 
복지시설 찾기 및 등록 : ![image](https://github.com/user-attachments/assets/bce5812d-628b-49aa-8e86-075e0df2e448)
내 일정 및 프로그램 : ![image](https://github.com/user-attachments/assets/7d28b92a-d3bd-4045-970b-17ea57f819cd)
프로그램 랭킹 및 후기 작성하기 :![image](https://github.com/user-attachments/assets/357f3b1b-d3a9-45af-85c8-6d9955d01dc7)
고객센터(챗봇) : ![image](https://github.com/user-attachments/assets/ecd4b419-b3cb-4e58-ad83-39beef89091f)
### 9. 모델개발 트러블 슈팅
#### 첫번째 시안
 - Python에서 데이터를 가져와 STS에서 출력하는 과정에서 이미지가 깨지고 데이터를 출력하는데 어려움을 겪음 → 데이터를 DB에 저장후 STS에서 불러오는 방식으로 변경 하였더니 이미지 및 데이터가 정상적으로 출력되기 시작하였습니다.
![image](https://github.com/user-attachments/assets/d76e1c0f-79c9-422d-b976-6b3312515a1c)
#### 두번째 시안
 - API로 지도를 가져와서 마커는 찍는 과정에서 지정한 위치에 마커가 마우스 "클릭" 버튼으로 마커가 이동되는 오류가 발생 → 위치 설정 코드 및 위도와 경도 부분을 수정하였더니 오류가 해결되었습니다.
![image](https://github.com/user-attachments/assets/4ac7a871-2e8c-4fc4-9222-2f963e892ec1)
### 10. 팀원역활
![image](https://github.com/user-attachments/assets/8552a369-ed4f-4a31-b214-3da9eacebf2a)
### 11. 시연영상
https://github.com/user-attachments/assets/1cfda77c-8faa-4cb4-b9a7-9ef625f23242
### 12. 참고문헌
![image](https://github.com/user-attachments/assets/dacf78d8-a16c-41bd-bdfc-be3fa8b364f1)







