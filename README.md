[패스트캠퍼스 온라인 강의](https://fastcampus.co.kr/dev_online_javaend)를 수강하며 작성한 내용입니다.   
<br>


## 네이버 지역검색 API를 활용한 맛집 List 만들기

![](https://img.shields.io/badge/Java-007396?style=flat&logo=Java&logoColor=white)
![](https://img.shields.io/badge/IntelliJ-000000?style=flat&logo=IntelliJIDEA&logoColor=white)
![](https://img.shields.io/badge/Gradle-02303A?style=flat&logo=Gradle&logoColor=white)
<br>

<br>

    src
    ㄴmain
        ㄴjava/com/example/restaurant
            ㄴcontroller
                ㄴApiController.java
                ㄴPageController.java
            ㄴdb
                ㄴMemoryDbEntity.java
                ㄴMemoryDbEntityRepositoryAbstract.java
                ㄴMemoryDbEntityRepositoryIfs.java
            ㄴnaver
                ㄴdto
                    ㄴSearchImageReq.java
                    ㄴSearchImageRes.java
                    ㄴSearchLocalReq.java
                    ㄴSearchLocalRes.java
                ㄴNaverClient.java
            ㄴwishlist
                ㄴdto
                    ㄴWishListDto.java
                ㄴentity
                    ㄴWishListEntity.java
                ㄴrepository
                    ㄴWishListRepository.java
                ㄴservice
                    ㄴWishListService.java
            ㄴRestaurantApplication.java
        ㄴresources
            ㄴstatic/js
                ㄴmain.js
            ㄴtemplates/aaaa
                ㄴmain.html
            ㄴapplication.yml
    ㄴtest
    build.gradle
