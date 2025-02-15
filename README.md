# Tomato-do (뽀모도로 타이머 + 투두리스트)

## 담당한 부분

> 타이머 시간에 따라 변하는 애니메이션 구현 <br>
> 알림음 구현 <br>
> 사용자정보 저장(이름입력) 구현 <br>

## Description

> 2022.04. - 2022.05. <br>
> page: [오늘도 Tomato-do!](https://happy-jm.github.io/Tomato-do/) <br/>
> notion: [Team 'tomato-do' notion](https://www.notion.so/tomato-do/Tomato-do-37daf0329b314e6c81ae99cb37fa2899)

### Summary

- 투두리스트, 타이머, 프로필, 뱃지, 테마 기능
- IndexedDB 사용으로 인한 브라우저(기기) 변경 시 데이터 이동 불가능

## About Project

### FE

<img src="https://img.shields.io/badge/Language-HTML-green?style=flat"/> <img src="https://img.shields.io/badge/Language-CSS-green?style=flat"/> <img src="https://img.shields.io/badge/Language-JavaScript-green?style=flat"/> <img src="https://img.shields.io/badge/Platform-Web-blue?style=flat"/> <img src="https://img.shields.io/badge/Platform-Android-blue?style=flat"/>

- 투두리스트 : DB와 통신하여 CRUD 기능 수행
- 타이머 : 집중-휴식 타이머 기능, 집중 타이머 종료시 음성알람 제공, 타이머 사용 시 시간 정보 DB에 저장
- 프로필 : 이름, 사진
- 뱃지 : DB에 쌓인 시간 데이터에 따른 뱃지 제공
- 테마 : 데이-나이트 모드

### BE

<img src="https://img.shields.io/badge/Language-JavaScript-green?style=flat"/> <img src="https://img.shields.io/badge/DB-IndexedDB-yellow?style=flat"/>

- IndexedDB 사용
- IndexedDB 구조
  ```js
  todolist:  "++id,todo,check",
  time:  "++id",
  userInfo:  "++id,userName,userimg,type",
  report:"++id,date,startTime,endTime"
  ```

## Results

### Web

|                                  기능                                   |                     화면                      |
| :---------------------------------------------------------------------: | :-------------------------------------------: |
| 투두리스트 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | <img src="./img/todolist.png"  width="30%"/>  |
|                                 타이머                                  |   <img src="./img/timer.png"  width="30%"/>   |
|                                  테마                                   | <img src="./img/nightmode.png"  width="30%"/> |

## Developers

| <img src="https://avatars.githubusercontent.com/u/102483942?v=4" width="80" height="80"> | <img src="https://avatars.githubusercontent.com/u/98958768?v=4" width="80" height="80"> | <img src="https://avatars.githubusercontent.com/u/94153997?v=4" width="80" height="80"> | <img src="https://avatars.githubusercontent.com/u/59535609?v=4" width="80" height="80"> | <img src="https://avatars.githubusercontent.com/u/85178602?v=4" width="80" height="80"> | <img src="https://avatars.githubusercontent.com/u/82685793?v=4" width="80" height="80"> |
| :--------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------: |
|                          [서정민](https://github.com/HAPPY-JM)                           |                          [김동철](https://github.com/GreyFBTT)                          |                          [박태훈](https://github.com/ekdh0858)                          |                         [배성현](https://github.com/seonghbae)                          |                        [지재영](https://github.com/jaeyeong815)                         |                         [이수정](https://github.com/tinashome)                          |

<br/>

---

<div align=center>

![image](https://user-images.githubusercontent.com/102483942/169540397-71d32a84-e6df-412e-848e-7f9a27689908.png)
![image](https://user-images.githubusercontent.com/102483942/169540482-2d8d8310-f1b5-4afe-bca2-23c82e66dc97.png)
![image](https://user-images.githubusercontent.com/102483942/169540641-5148effa-6bbe-4c2e-8d8f-705e9ebef874.png)
![image](https://user-images.githubusercontent.com/102483942/169540896-da8d0e30-e08c-4f94-bd61-37816cba4519.png)
![image](https://user-images.githubusercontent.com/102483942/169540833-42459d37-59cd-42a4-a7af-713b1aef4801.png)

</div>
