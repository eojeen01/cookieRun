# CookieRun

# 1. 기능 설명
* 플레이어는 최대 2명까지 접속 가능하다.
* 캐릭터를 선택할 수 있다. 능력치는 캐릭터마다 다르다.
* 달리기를 시작하는 순간부터 일정 점수에 도달한 순간까지의 시간을 기준으로 순위가 정해진다.
* 달리는 중간에 랜덤으로 배치된 장애물을 피해서 달려야 한다. 장애물에 닿을 경우 체력이 줄어든다.
* 총 3가지의 아이템이 맵 내에 랜덤으로 배치된다. (속도 증가, 감소, 체력 증가)
* 맵 내에 랜덤으로 배치된 코인을 먹으면 점수가 올라가고, 점수가 200점이 되면 게임이 끝난다.

# 2. Class Diagram
![image](https://user-images.githubusercontent.com/76842423/155287470-e1e47495-51d8-40e3-b889-5f6e0cb41834.png)

# 3. GUI와 서버
![image](https://user-images.githubusercontent.com/76842423/155288127-befbf9ca-ea6e-4580-8b5b-108dedbe9630.png)

Open 버튼을 클릭하면 Server Open이라는 문구가 뜨면서 서버가 열린다. Clear 버튼을 클릭하면 listBox가 비워진다. 

![image](https://user-images.githubusercontent.com/76842423/155287894-b952aba2-1932-40a8-bcd6-b52f2a9c609e.png)

클라이언트가 접속하면 Server Connected라는 문구와 함께 접속한 인원 수와 클라이언트가 선택한 캐릭터 번호를 띄운다.

![image](https://user-images.githubusercontent.com/76842423/155287956-c49a1cdf-aea2-48b0-8bec-17e1c86b243a.png)

클라이언트의 결과창이 닫히면 게임을 끝내는데 걸린 시간을 아이디와 함께 밀리 초로 나타낸다.




