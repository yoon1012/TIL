# String

Last Updated: 05-17-2021

## 문자열을 특정 문자 기준으로 자르기

```cpp
istringstream ss(operation);
string s;

vector<string> commands;

while (getline(ss, s, ' '))
{
    commands.push_back(s);
}
```
