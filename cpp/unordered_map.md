# Unordered Map

Last Updated: 03-03-2021

## 구현
* hash table

## 특징
* key의 hash를 따라 bucket에 각 요소를 보관
* 시간 복잡도
  * 탐색, 추가 및 삭제 작업에 평균적으로 상수 시간 → O(1)
  * 같은 hash를 갖는 요소가 여러 개일 때 탐색하면 최악 → O(n)

## map의 특징 (참고)
* 정렬되어 있음 (기본적으로 오름차순)
* Red-black Tree를 비롯한 **균형 이진 탐색 트리** Self Balanced BST로 구현
* 탐색에 log(n) 소요
* 추가 및 삭제 작업에 log(n)과 트리의 균형을 맞추는 시간을 필요로 함
