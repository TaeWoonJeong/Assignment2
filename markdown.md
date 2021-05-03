# 마크다운 프로젝트입니다.

# 개요
> 마크다운의 기본문법에 대해 설명합니다.

# 머리말

> 머리말은 `#` 을 구문 앞에다 붙이면 된다. `#` 의 개수 만큼 글자가 작아진다. 1개부터 최대 6개까지 붙일 수 있다.

> 주의사항 : `#` 뒤에 한칸 띄워줘야 적용이 된다는 점이다.
```
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6
```
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

## 대체 문법

> 텍스트 밑에 `=`(몇개든 상관 없음)을 붙이면 "#"과 효과가 같고 텍스트 밑에 `-`(몇개든 상관 없음)을 붙이면 "##"과 효과가 같다.
```
Heading Level 1
=
Heading Level 2
-
```
Heading Level 1
=
Heading Level 2
-

<br>

# 구문

> 구문을 만들고 싶으면 문장과 문장 사이 1개이상의 빈 줄을 만들면 된다.

```
I really like using Markdown.

I think I'll use it to format all of my documents from now on.
```

I really like using Markdown.

I think I'll use it to format all of my documents from now on.

> 주의사항 : 탭을 먼저 써주게 되면 코드블럭화 되서 구문처리가 되지 않는다.
```
    This can result in unexpected formatting problems.
```
    This can result in unexpected formatting problems.

> 권고사항 : 구문이 리스트에 포함되어있지 않으면 구문을 쓰기 전에 스페이스바를 써주는것을 좋지 않다. (무시하고 그냥 써도 되긴 한다.)

# 줄바꿈
> 텍스트를 입력하고 뒤에 스페이스바 2번 한뒤에 엔터하고 글을 쓰면 줄바꿈이 된다. 또는 끝에 `<br>` 을 붙이면 줄바꿈이 된다.  
그냥 엔터만 누를경우 줄바꿈이 되지 않고 한줄로 표시된다.
```
This is the first line.  
And this is the second line.

First line with the HTML tag after.<br>
And the next line.
```
This is the first line.  
And this is the second line.

First line with the HTML tag after.<br>
And the next line.


# 강조

## 굵게
> 굵은글씨로 표시하기 위해서는 `**`나 `__`를 굵게하고싶은 문장의 양끝에 붙이면 된다.
```
I just love **bold text**.

I just love __bold text__.
```
I just love **bold text**.

I just love __bold text__.
> 한 단어에서 일부만 굵게 표시하고 싶다면 `**`만 일부 단어의 처음과 끝에 붙이면 된다.
```
Love**is**bold.

Love__is__bold.
```
Love**is**bold.

Love__is__bold. 는 적용되지 않는다.
## 이태릭체

> 이태릭체로 쓰고 싶다면 `*`나 `_`를 문장의 양끝에 붙여주면 된다.
```
Italicized text is the *cat's meow*.

Italicized text is the _cat's meow_.
```
Italicized text is the *cat's meow*.

Italicized text is the _cat's meow_.

> 한 단어에서 일부만 이태릭체로 표시하고 싶다면 "*"만 일부 단어의 처음과 끝에 붙이면 된다.
```
- A*cat*meow

- A_cat_meow. 는 적용되지 않는다.
```
A*cat*meow

A_cat_meow. 는 적용되지 않는다.

## 굵은 이태릭체

> 문장에서 굵은 이태릭체를 쓰고싶다면 `***   ***` , `___   ___` , `__*   *__` , `**_   _**` 이렇게만 된다.

```
- ***really import***

- ___really import___

- __*really import*__
        
- **_really import_**
```
***really import***

___really import___

__*really import*__
        
**_really import_**

> 한 단어에서 일부만 굵은 이태릭체로 표시하고 싶다면 `***`만 일부 단어의 처음과 끝에 붙이면 된다.
```
This is really***very***important text.

This is really___very___important text.
```
This is really***very***important text.

This is really___very___important text. 는 적용되지 않는다.
# 인용문

## 블럭 인용문

- `>` 를 문장 시작시 붙여주면 된다.
```
>Dorothy followed her through many of the beautiful rooms in her castle.
```
>Dorothy followed her through many of the beautiful rooms in her castle.

## 여러문단 블럭인용문

- 여러 문단을 한개의 블럭인용문으로 만들고 싶으면 각 문단에 `>` 의 개수를 같게 붙여주면 된다.
```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## 중첩 블럭인용문

- `>` 의 개수로 단계를 표시한다.
```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## 다른 요소와 같이 쓰는 블럭인용문
>다른요소와 같이 쓰일 수 있다.
```
> # The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
```
> # The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

# 리스트

## 순서있는 리스트

> 순서있는 리스트를 만들때는 숫자를 적어주고 `.` 을 붙인뒤 한칸 띄워주고 리스트명을 적으면 된다.

```
1. first
2. second
5. third(5라고 써도 3이라고 됨)
```

1. first
2. second
5. third(5라고 써도 3이라고 됨)

> 처음 숫자는 1로 시작하는게 권장 된다. 하지만 시작숫자를 자기가 정할수 있다. 예를들어 3으로 시작했으면 다음은 4, 5,... 이런식으로 간다.

```
2. second
3. third
5. fourth (5라고 써도 4라고 됨)
```

2. second
3. third
5. fourth (5라고 써도 4라고 됨)

> 순서있는 리스트 안에 순서있는 리스트를 쓰려면 안의 리스트의 숫자를 1로 시작해야한다.

```
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item
```

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

> 그러지 않을 경우 원하지 않은 결과가 나온다.

```
1. First item
2. Second item
3. Third item
    2. Indented item
    4. Indented item
5. Fourth item
```

1. First item
2. Second item
3. Third item
    2. Indented item
    4. Indented item
5. Fourth item (역시 5라고 써도 4라고 나온다)

## 순서없는 리스트

> `+` , `-` , `*` 를 먼저 쓰고 한칸 띄워준뒤 리스트명을 적는다.

```
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
```

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

> 연속된 리스트끼리는 같은 기호를 써주도록 한다.

```
- First item
- Second item
- Third item
- Fourth item
```

- First item
- Second item
- Third item
- Fourth item

> 다른 기호를 쓰면 다른 리스트로 인식한다. (그렇지 않은 경우와 비교하면 줄 간격의 차이가 있다.)

```
+ First item
* Second item
- Third item
+ Fourth item
```

+ First item
* Second item
- Third item
+ Fourth item

## 리스트 합치기

> 순서있는 리스트 안에 순서없는 리스트가 들어갈수 있고 그 반대도 가능하다.

```
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item

- First item
- Second item
- Third item
    1. Indented item
    2. Indented item
- Fourth item
```

1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item

- First item
- Second item
- Third item
    1. Indented item
    2. Indented item
- Fourth item

## 리스트 보존

> 리스트 사이에 구문이나 블럭인용문을 넣어도 리스트의 순서는 유지가 된다.

```
1. This is the first list item.
2.  Here's the second list item.

    I need to add another paragraph below the second list item.

    > A blockquote would look great below the second list item.
5. And here's the third list item. (5라고 해도 3으로 됨)
```

1. This is the first list item.
2.  Here's the second list item.

    I need to add another paragraph below the second list item.

    > A blockquote would look great below the second list item.
5. And here's the third list item. (5라고 해도 3으로 됨)

# 코드

> 단어나 문장이 코드라면 백틱(`)으로 둘러싸면 된다.

```
At the command prompt, type `nano`.
```

At the command prompt, type `nano`.

## 코드블럭
> 코드블럭은 보통 스페이스 4번이나 탭으로 들여쓰기 한다. 하지만 리스트에 들어가 있으면 스페이스8번이나 탭2번을 해야한다. 또는 \`\`\` 를 코드블록으로 하고싶은 코드의 위 아래에 붙여준다.

    <html>
        <head>
            <title>Test</title>
        </head>
    <body>
    </body>
    </html>

1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

5.  Update the title to match the name of your website. (5라고 해도 3으로 됨)

# 이미지
> 사용방법 : `[![로딩 안될때 표시될 이름](이미지 내부URL "이미지에 마우스 올리면 나오는 글자")](이미지 원본 웹 주소)`

[![Tux, the Linux mascot](image/tux.png "펭귄")](https://d33wubrfki0l68.cloudfront.net/e7ed9fe4bafe46e275c807d63591f85f9ab246ba/e2d28/assets/images/tux.png)

# 수평선
> `***` , `---` , `___` 를 위랑 아래에 빈줄을 만든다음에 넣으면 수평선이 만들어 진다.

```
Try to put a blank line before...

---

...and after a horizontal rule.
```

Try to put a blank line before...

---

...and after a horizontal rule.

# 링크
> 사용법 : `[어떤 URL인지 설명](URL "하이퍼링크된곳에 마우스 올리면 나오는 글자")`
```
My favorite search engine is [Google](https://www.google.co.kr "구글")
```
My favorite search engine is [Google](https://www.google.co.kr "구글")

> URL과 이메일주소를 빠르게 링크로 바꾸고 싶으면 꺽새("<" ">")에 넣으면 된다.
```
<https://www.markdownguide.org>
<fake@example.com>
```

<https://www.markdownguide.org>

<fake@example.com>

## 링크 강조
> `**`로 감싸면 굵어지고 `*`로 감싸면 이태릭체가 된다. 링크가 코드임을 알리고 싶으면 주소에 대한 설명 부분을 백틱(`)으로 감싸주면 된다.

```
I love supporting the **[EFF](https://eff.org)**.

This is the *[Markdown Guide](https://www.markdownguide.org)*.

See the section on [`code`](#code).
```

I love supporting the **[EFF](https://eff.org)**.

This is the *[Markdown Guide](https://www.markdownguide.org)*.

See the section on [`code`](#code).

# 레퍼런스 스타일 링크

> 레퍼런스 스타일 링크는 두가지 부분으로 나뉜다. 첫번째부분은 `[hobbit-hole][1]` 두번째 부분은 `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle` 이런식으로 하면 hobbit-hole를 클릭하면 1번라벨의 주소로 가게 된다. 다음은 두번째부분의 링크 예시이다. 차이를 글로 쓰는것 보다 밑의 예시를 보고 이렇구나 하고 넘어가면 좋겠다.

```
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)
```

> 다음은 레퍼런스 스타일의 적절한 예시이다.
```
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
```

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

> 주의사항 : URL에 공백이 있다면 공백을 `%20` 으로 매꿔줘야한다.

```
[link](https://www.example.com/my%20great%20page)
```

[link](https://www.example.com/my%20great%20page)

# 탈출 문자
> `*` 는 순서없는 리스트에서 쓰이기 때문에 그냥 `*` 를 쓰고싶다면 앞에 `\` 를 붙여서 쓰면 `*` 가 나온다.

```
\* Without the backslash, this would be a bullet in an unordered list.
```

\* Without the backslash, this would be a bullet in an unordered list.

> 백슬래시와 같이 쓸 수 있는 문자들

| Character | Name |
| ---- | ----|
| \\ | backslash |
| \' | backtick |
| \* | asterisk |
| \_ | underscore |
| \{ \} | curly braces |
| \[ \] | brackets |
| \< \> | angle brackets |
| \( \) | parentheses |
| \# | pound sign |
| \+ | plus sign |
| \- | minus sign |
| \. | dot |
| \! | exclamation mark |
| \| | pipe |

# HTML
> 마크다운에서 전부는 아니지만 일부 HTML 태그를 사용할 수 있다.

```
This **word** is bold. This <em>word</em> is italic.
```

This **word** is bold. This <em>word</em> is italic.

# 깃허브 주소
> https://github.com/TaeWoonJeong/Markdown

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
