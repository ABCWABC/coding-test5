# coding-test5
평균 구하기


  * 매개변수
    1. 정수를 담고 있는 배열 arr


## 구현과정
  1. 향상된 for문으로 합계구함
  2. (double)로 변환후 arr.length로 나누어줌

## 보완할점
  1. 배열에 아무 정수도 없을경우도 생각해야됨 > if(array == null || array.length == 0) { }
  2. 이경우에 사용할수 있는 API가 있음 (속도가 느려지므로 사용X) > return (int) Arrays.stream(array).average().orElse(0);
