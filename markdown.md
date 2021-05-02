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