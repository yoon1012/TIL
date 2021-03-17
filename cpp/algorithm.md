# Algorithm

Last Updated: 03-17-2021

## 최대/최소 함수

* max_element: 구간의 최댓값을 가리키는 iterator를 반환한다.
* min_element: 구간의 최솟값을 가리키는 iterator를 반환한다.

* 오름차순 정렬: greater<int>

## 비교 함수

* Strict weak ordering 조건을 만족해야 한다.
  * 조건에 위배되면 런타임 오류가 발생한다.
  * 특히, 비교하는 순서가 바뀌면 결과 값이 달라야 한다.
