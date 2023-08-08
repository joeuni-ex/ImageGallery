# Image Gallery

```
section : div와 같이 영역을 표시하는 태그이나 좀 더 큰 영역을 표시할 때 사용함
```

- 이미지 다운로드 사이트
  (https://unsplash.com/ko/t/travel)
  사이즈: 보통

  ### 초기화 작업

  ```
  * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  }
  ```

### 이미지 박스

- ul class="images"

```
  columns : 5 310px ;
  -> 5열 310px 으로 배치하되 310px 안될 경우 자동으로 줄어듬

  gap : 15px
  -> 이미지들 사이의 간격 15xp

```

- li class="image"

```
  cursor: pointer;
  -> 커서 올리면 포인터로 바뀜

  overflow: hidden;
  -> 안의 이미지가 밖으로 나올 때 안보이게함 (숨김)
```

- img 태그

```
  transform : scale(1.1)
  -> 확대

  transition : 0.2 s ease;
  -> transform의 변화 시간
```

- transition 속성값에 대한 참고 블로그
  (https://blog.naver.com/yumdidi/223086747765)
