# Queue

Last Updated: 05-12-2021

* queue에는 iterator를 사용할 수 없다.
* pop은 값을 리턴하지 않으므로 맨 앞의 것을 보고 싶으면 front를 쓰자.

## Priority Queue

* 기본은 Max Heap
* std::greater를 사용하면 반대로 사용 가능

### 비교 함수

```cpp
struct compare
{
    bool operator()(vector<int> a, vector<int> b)
    {
        return a[1] > b[1];
    }
};
```
