# BUZZER

## 1. Git

### 1.1 이름 설정 (GitHub 계정명과 동일하게 권장)
```
git config --global user.name "홍길동"
```

### 1.2 이메일 설정 (GitHub 가입 이메일과 동일하게)
```
git config --global user.email "gildong@example.com"
```

### 1.3 설정 확인
```
git config --list
```

### 1.4 모든 파일 스테이징
```
git add .
```

### 1.5 커밋 (변경사항 저장)
```
git commit -m "Initial STM32F103 project setup"
```

### 1.6 GitHub에 업로드
```
git push origin main
```

---

github 마트다운 문법

마크다운(Markdown) 문법 가이드
마크다운은 텍스트를 HTML로 변환하기 위한 경량 마크업 언어입니다.
📝 제목 (Headers)
markdown# H1 제목
## H2 제목  
### H3 제목
#### H4 제목
##### H5 제목
###### H6 제목
🔤 텍스트 스타일링
강조 텍스트
markdown*이탤릭체* 또는 _이탤릭체_
**볼드체** 또는 __볼드체__
***볼드 이탤릭*** 또는 ___볼드 이탤릭___
~~취소선~~
`인라인 코드`
결과:
이탤릭체, 볼드체, 볼드 이탤릭, 취소선, 인라인 코드
📋 목록 (Lists)
순서 없는 목록
markdown- 항목 1
- 항목 2
  - 하위 항목 1
  - 하위 항목 2
    - 더 깊은 하위 항목

* 별표로도 가능
+ 플러스로도 가능
순서 있는 목록
markdown1. 첫 번째 항목
2. 두 번째 항목
   1. 하위 항목 1
   2. 하위 항목 2
3. 세 번째 항목
체크리스트
markdown- [x] 완료된 작업
- [ ] 미완료 작업
- [x] 또 다른 완료 작업
🔗 링크 (Links)
markdown[링크 텍스트](https://example.com)
[링크 텍스트](https://example.com "툴팁 텍스트")
<https://example.com&gt;
[참조 링크][1]
[1]: https://example.com "참조 링크"

// 내부 링크 (앵커)
[목차로 이동](#목차)
🖼️ 이미지 (Images)
markdown![대체 텍스트](이미지주소.jpg)
![대체 텍스트](이미지주소.jpg "이미지 제목")

// 이미지에 링크 추가
[![이미지](이미지주소.jpg)](https://example.com)

// 참조 방식
![대체 텍스트][image1]
[image1]: 이미지주소.jpg "이미지 제목"
💻 코드 (Code)
인라인 코드
markdown`console.log('Hello World')`
코드 블록
markdown```javascript
function hello() {
    console.log('Hello World');
}
```
```python
def hello():
    print("Hello World")
```
```bash
npm install package-name
```
들여쓰기 코드 블록
markdown    // 4개의 공백으로 들여쓰기
    console.log('Hello');
📊 표 (Tables)
markdown| 열1 | 열2 | 열3 |
|-----|-----|-----|
| 데이터1 | 데이터2 | 데이터3 |
| 데이터4 | 데이터5 | 데이터6 |

// 정렬
| 왼쪽 정렬 | 중앙 정렬 | 오른쪽 정렬 |
|:----------|:---------:|-----------:|
| 데이터1   |  데이터2  |     데이터3 |
📑 인용문 (Blockquotes)
markdown> 이것은 인용문입니다.
> 여러 줄의 인용문도 가능합니다.
>
> > 중첩된 인용문
➖ 구분선 (Horizontal Rules)
markdown---
***
___
🔧 HTML 태그
마크다운 안에서 HTML 태그 사용 가능:
html<details>
<summary>클릭하면 펼쳐집니다</summary>
숨겨진 내용입니다.
</details>

<kbd>Ctrl</kbd> + <kbd>C</kbd>

<mark>하이라이트된 텍스트</mark>

<sub>아래첨자</sub> <sup>위첨자</sup>
🚫 이스케이프 문자
특수 문자를 그대로 표시하려면 백슬래시(\) 사용:
markdown\*별표\*
\#해시태그
\`백틱\`
📚 GitHub 확장 문법
이모지
markdown:smile: :heart: :thumbsup: :octocat:
멘션과 이슈 참조
markdown@username
#123 (이슈 번호)
커밋해시: a1b2c3d
각주 (Footnotes)
markdown여기에 각주가 있습니다[^1].

[^1]: 이것은 각주입니다.
수학 수식 (LaTeX)
markdown$E = mc^2$ (인라인)

$$
\sum_{i=1}^{n} x_i = x_1 + x_2 + ... + x_n
$$
(블록)
🎨 배지 (Badges) 예제
markdown![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Build Status](https://img.shields.io/travis/user/repo)****
