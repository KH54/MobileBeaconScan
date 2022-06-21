# 휴대폰 분실 알림이

### 휴대전화를 떨어뜨리고 인지하지 못했을 때 저장한 연락처로 문자 메시지를 발송하는 Application

#### Language and Tool :hammer:
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Android Studio-3DDC84?style=flat-square&logo=Android&logoColor=white"/></a>

#### Development period / personnel
    2 Weeks / 1 person
    
#### Library
    ACCELEROMETER(가속도계), GPS(Location, Latitude, Longitude)

<br><br>
#### Order :egg:

1. 휴대전화 낙하시 메시지를 보낼 연락처 입력<br>

2. 전송할 메시지 입력

3. 많은 실험을 통해 보행 중에나, 가볍게 휴대폰을 놓을 때는 발신이 되지 않도록 가속도 센서 값을 조정하였습니다.

4. 일정한 가속도 값을 넘었을 때, GPS 위치가 업데이트 되고, 타이머를 작동시켜 7초 동안 카운트를 시작합니다.

5. 7초 내에 Application의 휴대전화 습득 확인 버튼을 클릭하면 쓰레드가 interrupt 되어 분실 메시지가 발송되지 않습니다.

6. 7초 이후에는 Application에 저장된 연락처로 분실 메시지를 발송합니다. 


<br><br>
#### Image 🖼️
![image](https://user-images.githubusercontent.com/66667857/174766906-4c64d6c1-d0ad-4372-8c72-e27c603b1090.png)
![image](https://user-images.githubusercontent.com/66667857/174767218-fb6dfe18-2635-4073-a85e-4f7cbc764f6c.png)
##### 낙하 이벤트 발생
![image](https://user-images.githubusercontent.com/66667857/174772184-f43cc112-8ac5-451b-b589-8a79fd035eec.png)


<br><br>
#### utilization 🌟
##### 휴대폰 수리 시장에 사용하면 좋을 것 같습니다. 
##### 본인의 과실로 휴대폰을 낙하시켰을 때 로그 기록을 남겨 낙하로 인한 과실인지 판단할 수 있을 것이라 예상합니다.

