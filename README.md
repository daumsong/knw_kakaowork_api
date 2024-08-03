# 케이앤웍스 카카오워크 API

## 알림 API 사용법

\# 모듈 임포트
import kakaowork_api


\# **Info 함수**
kakaowork_api.Info(codename='APY001', msg='여기에 메시지 입력', email_adress_list=['archon@knworks.co.kr'],api_key='as123ras23g')
- codename: 과제명(코드) ,
- msg: 텍스트 메시지 내용 ,
- email_adress_list: 수신자 이메일주소(리스트형태로 다수 발송가능) ,
- api_key: Bot 생성 시 인증키


\# **Success 함수**
kakaowork_api.Success(codename='APY001', msg='여기에 메시지 입력', email_adress_list=['archon@knworks.co.kr'],api_key='as123ras23g')
- codename: 과제명(코드) ,
- msg: 텍스트 메시지 내용 ,
- email_adress_list: 수신자 이메일주소(리스트형태로 다수 발송가능) ,
- api_key: Bot 생성 시 인증키


\# **Error 함수**
kakaowork_api.Error(codename='APY001', msg='여기에 메시지 입력', email_adress_list=['archon@knworks.co.kr'],api_key='as123ras23g')
- codename: 과제명(코드) ,
- msg: 텍스트 메시지 내용 ,
- email_adress_list: 수신자 이메일주소(리스트형태로 다수 발송가능) ,
- api_key: Bot 생성 시 인증키


kakaowork_api.txt(text='여기에 메시지 입력', email_adress_list=['archon@knworks.co.kr'], api_key='as123ras23g')
- text: 텍스트 메시지 내용 ,
- email_adress_list: 수신자 이메일주소(리스트형태로 다수 발송가능) ,
- api_key: Bot 생성 시 인증키
