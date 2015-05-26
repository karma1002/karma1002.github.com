---
layout: post
title: "Donggi Kim"
---

제목, 목록, 강조(기울인 글씨, 굵은 글씨), 인용, 링크(인라인 링크, 참조 링크), 이미지, 표, 코드   
를 포함한 포스트 만들기


# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

*기울여 쓰기*

**굵게 쓰기**

* 번호 없는 리스트
* 번호 없는 리스트

1. 번호 있는 리스트
2. 번호 있는 리스트
  * 리스트 안의 리스트
    1. 리스트 안의 리스트 안의 리스트
  * 리스트 안의 리스트 2

> 인용
>> 인용인용

인라인링크 : [Google](http://www.google.com)

참조 링크 : [Google][구글 링크]

![네이버로고](http://img.naver.net/static/www/u/2013/0731/nmms_224940510.gif)

---
수평선

표

| 항목1 | 항목2 | 항목3 | 항목4 |
|:-----|:-----:|:-----:|------:|
| 내용11 | 내용12 | 내용13 | 내용14 |
| 내용21 | 내용22 | 내용23 | 내용24 |

```
// 코드  
 #include <cstdio>  
  {  
    int a;  
  }
```

    // 코드  2
    #include <cstdio>  
    {  
        int a;  
    }

    // 코드  3
        #include <cstdio>  
        {  
            int a;  
        }

아래 내용은 코드가 제대로 구현되지 않는 것 같아 비교를 위해   
https://stackedit.io/editor 의 코드 부분 내용을 그대로 복사한 것입니다.  



[구글 링크]: http://www.google.com


### Fenced code blocks

GitHub's fenced code blocks are also supported with **Highlight.js** syntax highlighting:

```
// Foo
var bar = 0;
```

> **Tip:** To use **Prettify** instead of **Highlight.js**, just configure the **Markdown Extra** extension in the <i class="icon-cog"></i> **Settings** dialog.

> **Note:** You can find more information:

> - about **Prettify** syntax highlighting [here][5],
> - about **Highlight.js** syntax highlighting [here][6].



아래는 html코드를 그대로 붙여넣은 것.

    <h2 id="section">큰 제목</h2>

<h1 id="section-1">작은 제목</h1>

<h2 id="section-2">굵은 글씨 1</h2>

<h3 id="section-3">굵은 글씨 2</h3>

<h4 id="section-4">굵은 글씨 3</h4>

<h5 id="section-5">굵은 글씨 4</h5>

<h6 id="section-6">굵은 글씨 5</h6>

<p><em>기울여쓰기(Italic)</em></p>

<p><strong>굵게쓰기(Bold)</strong></p>

<ul>
  <li>바나나</li>
  <li>사과</li>
  <li>수박</li>
</ul>

<ol>
  <li>banana</li>
  <li>apple</li>
  <li>watermelon</li>
</ol>

<ul>
  <li>목록 안에 목록
    <ul>
      <li>또다시 리스트가
        <ul>
          <li>한단계 더 아래!</li>
        </ul>
      </li>
      <li>한단계 위로!</li>
    </ul>
  </li>
</ul>

<blockquote>
  <p>이것이 인용입니다.
인용인용~
인용~</p>
</blockquote>

<p>인라인 링크 :  <a href="http://www.google.com/">Google</a></p>

<p>참조 링크 : <a href="http://www.google.com/">Google</a>.</p>

<p><img src="http://img.naver.net/static/www/u/2013/0731/nmms_224940510.gif" alt="Naver" />.</p>

<p>표</p>

<table>
  <thead>
    <tr>
      <th>항목 1</th>
      <th>항목 2</th>
      <th>항목 3</th>
      <th>항목 4</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>내용 11</td>
      <td>내용 12</td>
      <td>내용 13</td>
      <td>내용 14</td>
    </tr>
    <tr>
      <td>내용 21</td>
      <td>내용 22</td>
      <td>내용 23</td>
      <td>내용 24</td>
    </tr>
  </tbody>
</table>
<div class="highlight"><pre><code class="language-ruby" data-lang="ruby"><span class="sr">//</span><span class="err">코드입니다</span><span class="o">.</span>
    <span class="c1">#include&lt;stdio.h&gt;</span>
    <span class="n">int</span> <span class="n">main</span> <span class="p">(</span><span class="n">void</span><span class="p">)</span>
    <span class="p">{</span>
	<span class="nb">printf</span><span class="p">(</span><span class="s2">&quot;hello world</span><span class="se">\n</span><span class="s2">&quot;</span><span class="p">);</span>
	<span class="k">return</span> <span class="mi">0</span><span class="p">;</span>
    <span class="p">}</span></code></pre></div>
