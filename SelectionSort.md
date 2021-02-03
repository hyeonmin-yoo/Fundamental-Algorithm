# 선택 정렬(Bubble sort)
![](https://upload.wikimedia.org/wikipedia/commons/9/94/Selection-Sort-Animation.gif)

image url: https://upload.wikimedia.org/wikipedia/commons/9/94/Selection-Sort-Animation.gif

## Download Material
[Xcode Playgound file]()

## 버블 정렬이란?
제자리 정렬(in-place sort) 알고리즘의 하나로 주어진 리스트 중에 최소값을 찾아 그 값을 맨 앞의 숫자와 교체하여 정렬

## 구체적인 개념
* 1회전에서는 **첫 번째부터 마지막까지** 자료까지 차례대로 비교하여 비교하여 가장 작은 값을 첫 번째 자리에 놓음
* 1회전에 끝나고 나면 가장 작은 값이 첫 번째 자리에 오게 되므로
* 2회전에서는 **두 번째부터 마지막까지** 자료까지 차례대로 비교하여 비교하여 가장 작은 값을 첫 번째 자리에 놓음
* 위와 같은 방식으로 마지막 하나의 자료가 남을때 까지 반복

## 특징
* 자료의 이동 횟수가 미리 결정됨
* k번째로 큰 자료를 찾는 경우 유용함
* 같은 값이 있을 경우 상대적 위치가 변경 될 수 있음(비안정 정렬)

## References
* https://ko.wikipedia.org/wiki/%EC%84%A0%ED%83%9D_%EC%A0%95%EB%A0%AC
