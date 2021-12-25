# 모바일 환경에 적용하기 위해 만들어진

#

```
.box1 {
  background-color: red;
}
.box2 {
  background-color: blue;
}

.box3 {
  background-color: blueviolet;
}
```

div태그만 있으면 block속성인데  
해당 div를 포함하는 div속성이 flex가 되면 inline-block으로 변경된다?  
속성 자체는 block이다.
-> flex속성값인 stretch의 속성으로 움직이게 된다. width height값이 없다면 inline-block처럼 컨텐츠 사이즈만 표시가 된다.

컨테이너의 높이 만큼 쭉 늘어나게 된다.

# flex 속성값

.item {
flex: 1 0 100px;
}

flex-grow 1
flex-shrink 0
flex-basis 100px

최소 길이 100px이하로 줄지 않고 각 아이템들은 1:1:1로 들어가게 된다.

.item {
flex: 1;
}

flex-grow 1
flex-shrink 1
flex-basis 0
