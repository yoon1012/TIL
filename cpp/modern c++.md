# Modern C++

Last Updated: 03-05-2021

## 스마트 포인터

1. unique : 일반적으로 사용하는 포인터로, 객체를 한 곳에서만 소유할 수 있다.
2. shared : 같은 객체를 여러 곳에서 소유할 수 있다. Reference 횟수를 세며, 0이 되면 객체를 제거한다.
3. weak
    * shared와 다르게 reference 횟수를 세지 않는다.
    * shared 포인터로 참조를 순환되는 형태로 수행 시, 레퍼런스 카운트가 0이 되지 않아 객체가 사라지지 않는 문제를 해결할 수 있다.

## std::variant (C++ 17)

* union (열거형)은 type safe하지 않기 때문에 오류가 발생할 수 있다.
* std::visit 함수를 통해 각 멤버에 접근할 수 있다.
