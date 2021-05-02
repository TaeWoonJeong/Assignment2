# 마크다운 프로젝트입니다.
# 확장 문법
- 비쥬얼스튜디오코드에서는 적용이 안되는 것도 있음 깃허브에 가면 적용됨.

## 표 (확장)

### 생성
> 표를 추가하고싶으면 3개 이상의 하이픈(`-`)으로 각 열의 헤더를 구분해준뒤 `|` 로 열을 분리할수 있다. 셀의 가로 길이는 자동조정된다.
```
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
```
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
### 정렬
> 3개 이상의 하이픈(`-`)ㅇ,로 각 열의 헤더를 구분할때 ":"의 위치로 정렬을 할 수 있다. 세미콜론이 왼쪽에 붙으면 왼쪽 정렬 오른쪽에 붙으면 오른쪽 정렬 양쪽에 붙으면 가운데 정렬이다.
```
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
```
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
### 추가적인 것들
> 첫 행에 파이프를 양 끝에 붙였다면 다음 행부터는 안붙여도 된다. 단 비어있는 셀일 경우에는 파이프로 구분을 해줘야 한다.
```
| abc | defghi |
:-: | -----------:
bar | baz
|    |aaa|
```
| abc | defghi |
:-: | -----------:
bar | baz
|    |aaa|
> 헤더를 구분해주는 하이픈은 반드시 열의 개수만큼 있어야 한다. 없으면 표로 인식되지 않는다.
```
| abc | def |
| --- |
| bar |
```
| abc | def |
| --- |
| bar |
> 헤더를 구분해 준다면 밑의 항목들은 비어있어도 되고 넘치면 자동으로 잘린다.
```
| abc | def |
| --- | --- |
| bar |
| bar | baz | boo |
```
| abc | def |
| --- | --- |
| bar |
| bar | baz | boo |

## 리스트 버튼
> "-"와 스페이스바 한칸 하고 "[ ]"를 붙인뒤 스페이스바 한칸 하고 버튼명을 적으면 된다.
```
- [ ] foo
- [x] bar
```
- [ ] foo
- [x] bar
> 중첩 리스트 또한 가능 하다.
```
- [x] foo
  - [ ] bar
  - [x] baz
- [ ] bim
```
- [x] foo
  - [ ] bar
  - [x] baz
- [ ] bim

## 취소선
> 취소선을 넣고싶은 문장의 앞뒤에 "~"를 2번 써주면 된다.
```
~~Hi~~ Hello, world!
```
~~Hi~~ Hello, world!

> 단 구문이 분리 되있으면 적용되지 않는다.
```
This ~~has a

new paragraph~~.
```
This ~~has a

new paragraph~~.
