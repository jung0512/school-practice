# DB
![image](https://user-images.githubusercontent.com/102035198/186084334-73d0ea5e-8580-4745-abf0-8881ea06a72a.png)<br>
회원번호는 숫자와 고객이름과 같은 나머지 데이터들은 문자로 받게 
member_tbl 테이블을 만들어 줍니다<br>
![image](https://user-images.githubusercontent.com/102035198/186084458-47b72212-e751-4ea9-9974-6fb52f1481c7.png)<br>
테이블을 만들때 정해 놓은 형식에 맞게 데이터들을 입력하여 줍니다<br>
# join
![image](https://user-images.githubusercontent.com/102035198/186065532-1babd118-9b8f-42b5-9d44-f935bf4127f6.png)<br>
회원의 정보를 미리 만들어 놓은 member_tbl 테이블에 추가해 주는 창입니다<br>
![image](https://user-images.githubusercontent.com/102035198/186093812-a1111c32-9ce4-4433-a7a3-c0b860f2ae41.png)<br>
입력칸과 등록버튼을 만들어 주는 코드입니다<br>
![image](https://user-images.githubusercontent.com/102035198/186065622-9fb957b1-2b38-438a-b523-4421f69e9340.png)<br>
member_tbl테이블에서 가장 마지막 회원번호에서 1을 더해준 다음 회원번호를 자동 생성해줍니다<br>
![image](https://user-images.githubusercontent.com/102035198/186083498-4a6514b0-11ad-448e-9a0f-69cdb005f1cd.png)<br>
![image](https://user-images.githubusercontent.com/102035198/186083562-05b4279e-c055-44ba-a27e-7f5525227506.png)<br>
if 문을 통해 작성하지 않은 칸이 있다면 
경고창을 띄워준 다음 포커스를 입력하지 않은 칸으로 이동한다<br>
# join_p
![image](https://user-images.githubusercontent.com/102035198/186089600-859dbe18-428b-481e-880e-5cb643ac8c7e.png)<br>
퀴리문이 들어갈 자리를 만들어 줍니다.<br>
![image](https://user-images.githubusercontent.com/102035198/186095264-b86d9ac5-3034-4e9d-ac0d-71da14a27f38.png)<br>
DB와 연결해 준다<br>
![image](https://user-images.githubusercontent.com/102035198/186087752-ee30aec3-ffac-4dc6-921d-c6ae267f5c7c.png)<br>
pstmt변수를 이용하여
회원번호는 문자열형태로 넘어온 데이터를 int로 변환하여 반환해준다<br>
![image](https://user-images.githubusercontent.com/102035198/186086519-97327cdc-51c3-43e1-aa93-323f2e0ef16a.png)<br>
회원정보를 입력후에 등록을 할시 index 페이지로 이동하는 코드입니다<br>
# 결과화면
![image](https://user-images.githubusercontent.com/102035198/186097391-d928b408-9469-49e0-952b-3315d26e06c2.png)
