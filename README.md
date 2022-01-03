# Instagram_Unfollow_Bot [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fbaka9131%2Fhit-counter&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

### 인스타그램 언팔로우 Bot 입니다.
제작환경 Jupyter Notebook 이며, 주석처리가 있으므로 쉽게 이해할 수 있습니다. 
+ [ 셀레니움 사용 ]

### 사용방법
1. elem.send_keys('아이디') # 아이디 입력
2. elem.send_keys('비밀번호') # 비밀번호 입력
3. 위에 계정정보 입력하신 다음 차례대로 실행하시면 됩니다.
4. if (count <= 10): # 이 부분에 숫자를 변경하여 1번 실행될때 최대 언팔로우 수를 지정할 수 있습니다 [ * MAX 20 까지 가능 ] <BR> [ 권장설정은 10 ]


### 주의사항
1. API 방식이 아닌 XPATH를 사용하여 Element를 찾는 방식이므로 주기적으로 XPATH 경로가 바뀔 수 있습니다. 변경사항이 발생했을 경우 수동으로 변경해주셔야 작동 됩니다.
2. 수정 사항이 발생될 경우 주기적으로 업데이트 하겠습니다.
  
### 추가 개발 사항
1. 텔레그램과 연동하여 실시간으로 진행사항 알림 설정 추가하기
