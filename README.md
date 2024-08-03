# 케이앤웍스 카카오워크 API

### 알림 API 사용법

\# **모듈 임포트**<br>
import kakaowork_api
<br><br>


\# **Info 함수**<br>
kakaowork_api.Info(codename='APY001', msg='여기에 메시지 입력', email_adress_list=['archon@knworks.co.kr'],api_key='as123ras23g')
- codename: 과제명(코드) ,
- msg: 텍스트 메시지 내용 ,
- email_adress_list: 수신자 이메일주소(리스트형태로 다수 발송가능) ,
- api_key: Bot 생성 시 인증키
<br><br>
![KAKAOWORK_Share_2024_08_03_0 - 복사본](https://github.com/user-attachments/assets/c1e12754-694b-4229-87b2-b2eeed4a7ed6)


\# **Success 함수**<br>
kakaowork_api.Success(codename='APY001', msg='여기에 메시지 입력', email_adress_list=['archon@knworks.co.kr'],api_key='as123ras23g')
- codename: 과제명(코드) ,
- msg: 텍스트 메시지 내용 ,
- email_adress_list: 수신자 이메일주소(리스트형태로 다수 발송가능) ,
- api_key: Bot 생성 시 인증키
<br><br>


\# **Error 함수**<br>
kakaowork_api.Error(codename='APY001', msg='여기에 메시지 입력', email_adress_list=['archon@knworks.co.kr'],api_key='as123ras23g')
- codename: 과제명(코드) ,
- msg: 텍스트 메시지 내용 ,
- email_adress_list: 수신자 이메일주소(리스트형태로 다수 발송가능) ,
- api_key: Bot 생성 시 인증키
<br><br>


\# **txt 함수**<br>
kakaowork_api.txt(text='여기에 메시지 입력', email_adress_list=['archon@knworks.co.kr'], api_key='as123ras23g')
- text: 텍스트 메시지 내용 ,
- email_adress_list: 수신자 이메일주소(리스트형태로 다수 발송가능) ,
- api_key: Bot 생성 시 인증키
