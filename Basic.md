# Paragraphs
문단, \<br>, \&nbsp;
그냥 입력하면 문단이 됩니다.
This is a paragraph.

This is another paragraph.
\<br> 를 입력하면 새 줄이 입력됩니다.
<br>
Multiple &nbsp;&nbsp;&nbsp; adjacent &nbsp;&nbsp;&nbsp; spaces

# Headings
\# 기호는 헤더를 표현합니다.
# This is a heading 1 \#
## This is a heading 2 \#\#
### This is a heading 3 \#\#\#
#### This is a heading 4 \#\#\#\#
##### This is a heading 5 \#\#\#\#\#
###### This is a heading 6 \#\#\#\#\#\#

# Styling text
**Bold text**
*Italic text*
~~Striked out text~~
==Highlighted text==
**Bold text and _nested italic_ text**
***Bold and italic text***

# Quotes
\> 기호는 인용문을 나타냅니다.

> Human beings face ever more complex and urgent problems, and their effectiveness in dealing with these problems is a matter that is critical to the stability and continued progress of society.
> 
> \\- Doug Engelbard, 1961

# Code

## Inline code
\`\`(backtick) 기호는 인라인 코드를 표현할 때 사용합니다.
Text inside `backticks` on a line will be formatted like code.

## Code blocks
\`\`\` 기호를 사용하여 코드 블록을 지정할 수 있습니다.
```
cd ~/Desktop
```

```js
function fancyAlert(arg) {
	if(arg) {
		$.facebox({div:'#foo'})
	}
}
```

# External links
\[]() 를 사용하여 연결할 수 있는 외부 링크를 입력할 수 있습니다.
[Obsidian Help](https://help.obsidian.md)

옵시디언 링크를 입력할 수도 있습니다.
[Note](obsidian://open?vault=MainVault&file=Noe.md)

# External images
!\[]() 를 사용하여 외부 이미지를 추가할 수 있습니다.
![Engelbart](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)

이름 옆에 |가로x세로 해상도를 입력하면 이미지의 크기를 지정할 수 있습니다.

![Engelbart|100x145](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)

이름 옆에 |scale 스케일을 입력하면 이미지 스케일에 따라 크기를 저장할 수 있습니다.

![Engelbart|50](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)

# Lists

(-, \*, +) 를 사용해서 리스트를 표현할 수 있습니다.
- First list item
- Second list item
- Third list item

숫자. 를 사용해서 숫자 리스트를 표현할 수 있습니다.
1. First list item
2. Second list item
3. Third list item

단계별로 추가할 수도 있습니다.
1. First list item
	1. Ordered nested list item
2. Second list item
	- Unordered nested list item

## Task lists
\- \[] 할일 목록 을 입력하면 할일을 만들 수 있습니다.
- [ ] This is a completed task.
- [x] This is an incomplete task.

# Horizontal bar

\*\*\*, \-\-\-, \_\_\_ 를 입력하여 수평 바를 입력할 수 있습니다.

---

# Footnotes
\[^1]. 를 입력하여 각주를 달 수 있습니다.

This is a simple footnote[^1].
This is a new footnote[^2].
You can also use inline footnotes. ^[This is an inline footnotes.]

[^1]: This is the referenced text.
[^2]: Add 2 spaces at the start of each new line.
  This lets you write footnotes that span multiple lines.
[^note]: Named footnotes still appear as numbers, but can make it easier to identify and link references.

# Comments
\%% 를 입력하여 코멘트를 작성할 수 있습니다.

This is an %%inline%% comment.

%%
This is a block comment.

Block comments can span multiple lines.
%%
