# 마크다운 문법

## :pushpin: Header 헤더

제목은 # 기호를 사용하여 설정할 수 있습니다. #의 개수에 따라 제목의 크기가 달라집니다.

### 입력

```markdown
# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6
```

### 출력

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

## :pushpin: Blockquotes 인용

">" 기호를 사용하여 인용문을 작성할 수 있습니다.

### 입력

```markdown
> 이것은 인용문입니다.
```

### 출력

> 이것은 인용문입니다.

## :pushpin: Emphasis 강조

텍스트를 강조할 수 있습니다. 이탤릭체와 볼드체를 사용할 수 있습니다.

### 입력

```markdown
_이탤릭체_ 또는 _이탤릭체_

**볼드체** 또는 **볼드체**
```

### 출력

_이탤릭체_ 또는 _이탤릭체_

**볼드체** 또는 **볼드체**

## :pushpin: Horizontal Rules 수평선

수평선은 ---, \*\*\*, 또는 \_\_\_를 사용하여 만들 수 있습니다.

### 입력

```
---

***

___
```

### 출력

---

---

---

## :pushpin: Line Breaks 줄바꿈

문단은 두 번의 엔터키로 구분합니다.

### 입력

```markdown
첫 번째 문단입니다.

두 번째 문단입니다.
```

### 출력

첫 번째 문단입니다.

두 번째 문단입니다.

## :pushpin: Unordered Lists 순서가 없는 목록

순서 있는 목록과 순서 없는 목록을 작성할 수 있습니다.
\*, +, - 를 이용해서 순서가 없는 목록을 만들 수 있습니다.

### 입력

```
* 순서 없는 목록
  * 항목 1
  * 항목 2
    * 하위 항목 1
```

### 출력

- 순서 없는 목록
  - 항목 1
  - 항목 2
    - 하위 항목 1

## :pushpin: Ordered lists 순서가 있는 목록

숫자를 기입하면 순서가 있는 목록이 됩니다.

### 입력

```
1. 항목 1
2. 항목 2
4. 항목 3 <- 4번으로 해도 3번으로 바뀐다.
```

### 출력

1. 항목 1
2. 항목 2
3. 항목 3

## :pushpin: Image 이미지

이미지를 삽입할 수 있습니다.

### 입력

```
![텍스트](이미지파일경로.jpg)
![김수현](../assets/images/suhyeon.jpeg)
```

### 출력

![김수현](../assets/images/suhyeon.jpeg)

## :pushpin: Links 링크

링크를 삽입할 수 있습니다.

### 입력

```
[링크 텍스트](링크 url)
[멋쟁이 사자처럼](https://likelion.net/)
```

### 출력

[멋쟁이 사자처럼](https://likelion.net/)

## :pushpin: Table 테이블

표를 작성할 수 있는 문법이 있습니다.

### 입력

```
헤더1|헤더2|헤더3|헤더4
---|---|---|---
셀1|셀2|셀3|셀4
셀5|셀6|셀7|셀8
셀9|셀10|셀11|셀12
```

### 출력

| 헤더1 | 헤더2 | 헤더3 | 헤더4 |
| ----- | ----- | ----- | ----- |
| 셀1   | 셀2   | 셀3   | 셀4   |
| 셀5   | 셀6   | 셀7   | 셀8   |
| 셀9   | 셀10  | 셀11  | 셀12  |
