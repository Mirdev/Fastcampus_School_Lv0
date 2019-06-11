# [필수1]

1. id
2. letter-spacing
3. overflow, hidden
4. `input[type="email"]`
5. border-radius

<br>

# [필수2]

1. action: submit시 해당 form의 정보를 보낼 대상
   method: 보내는 방식. get방식과 post방식이 대표적.
2. input tag에 대한 설명
3. 정보를 한번에 보낼 수 있기 때문에, 회원가
4. ```
p::after {
  content: ">";
}```
5. 라디오 버튼은 단일 선택, 체크박스는 중복 선택

<br>

# [필수3]

- :nth-child(3)

	세번째 요소 선택

- :nth-child(n+2)
	두번째 요소 부터 그 이후 요소들 선택

- :nth-child(-n+2)

	두번째 요소 부터 그 앞 요소들 선택

- :nth-child(odd)

	홀수번째 요소 선택

- :nth-child(even)

	짝수번째 요소 선택

<br>

# [필수4]

1. text인 경우 그냥 단일 라인 입력 줄 생성
   password인 경우 그냥 단일 라인 입력 줄 생성 되지만, 내용이 표시 안되고 * 혹은 ∙으로 표시됨
2. button인 경우 버튼이 하나 생성되며 이 버튼에 여러 기능을 추가 가능
   submit인 경우 버튼이 하나 생성되긴 하지만 이 버튼은 form요소를 action에 method 방식으로 전달하는 기능을 하는 버튼

<br>

# [심화1]

```
h2 {
  position: absolute;
  width: 1px;
  height: 1px;
  overflow: hidden;
  margin: -1px;
  clip: rect(0, 0, 0, 0);
}
```
