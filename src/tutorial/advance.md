## 支持 HTML 元素

- 不在 Markdown 涵盖范围之内的标签，都可以直接在文档里面用 HTML 撰写
- 目前支持的 HTML 元素有：\<kbd\> \<b\> \<i\> \<em\> \<sup\> \<sub\> \<br>等
- eg:
  - <b>加粗</b>
  - <i>斜体</i>
  - 使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

## 转义

- Markdown 使用了很多特殊符号来表示特定的意义，使用特定的符号需要转义符（\）

```javascript
\   反斜线
`   反引号
*   星号
_   下划线
{}  花括号
[]  方括号
()  小括号
#   井字号
+   加号
-   减号
.   英文句号
!   感叹号号
```

## 公式

- \$...\$ 或者 \(...\) 中的数学表达式将会在行内显示
- \$\$...\$\$ 或者 \\[...\\] 或者 ```math 中的数学表达式将会在块内显示

$$
\begin{Bmatrix}
   a & b \\
   c & d
\end{Bmatrix}
$$

$$
\begin{CD}
   A @>a>> B \\
@VbVV @AAcA \\
   C @= D
\end{CD}
$$
