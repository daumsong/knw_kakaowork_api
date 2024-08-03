# 케이앤웍스 카카오워크 API

## 사용법
import kakaowork_api

kakaowork_api.Info(codename='APY001', msg='여기에 메시지 입력', email_adress_list=['archon@knworks.co.kr'],api_key='as123ras23g')
- codename: 과제명(코드) ,
- msg: 텍스트 메시지 내용 ,
- email_adress_list: 수신자 이메일주소(리스트형태로 다수 발송가능) ,
- api_key: 



kakaowork_api.Success(codename='APY001', msg='여기에 메시지 입력', email_adress_list=['archon@knworks.co.kr'],api_key='as123ras23g')

kakaowork_api.Error(codename='APY001', msg='여기에 메시지 입력', email_adress_list=['archon@knworks.co.kr'],api_key='as123ras23g')

kakaowork_api.txt(text='여기에 메시지 입력', email_adress_list=['archon@knworks.co.kr'], api_key='as123ras23g')
