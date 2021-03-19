# Algorithm

Last Updated: 03-19-2021

## 최대와 최소

* max_element: 구간의 최댓값을 가리키는 iterator를 반환한다.
* min_element: 구간의 최솟값을 가리키는 iterator를 반환한다.

## 비교

* 오름차순 정렬: greater<int>
* Strict weak ordering 조건을 만족해야 한다.
  * 조건에 위배되면 런타임 오류가 발생한다.
  * 특히, 비교하는 순서가 바뀌면 결과 값이 달라야 한다.

## 순열

* next_permutation
  * 주어진 구간의 요소들을 사전상 다음번째 순열로 배열해준다.

## 중복 제거하기

* unique에 특정 범위의 iterator 인자를 전달한다.
