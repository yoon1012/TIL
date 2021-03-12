# C++ 개발환경 설정

Last Updated: 03-12-2021

## Windows 10

1. MinGW-w64 설치
    * http://mingw-w64.org/doku.php/download
    * x86_64-posix-seh
2. MinGW-w64의 bin 폴더 경로를 시스템 환경 변수 PATH에 추가
3. Command Palette (Ctrl+Shift+P) → C/C++ Extension 설치
4. C/C++ Configuration을 gcc-x64로 설정
5. Preferences>Keyboard Shortcuts(Ctrl+K,S)에 단축키 추가
6. tasks.json에 빌드 작업 정의

## macOS (Modern C++)

1. Marketplace에서 Code Runner Extension 설치
2. 우클릭을 하여 Extension Settings 메뉴 열기
3. User 탭에서 Executor Map을 찾아 settings.json 편집
4. 컴파일할 C++ 버전을 -std=c++11 이상으로 변경

```
"cpp": "cd $dir && g++ -std=c++17 $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt"
```
