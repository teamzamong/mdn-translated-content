---
title: 411 Length Required
slug: Web/HTTP/Status/411
translation_of: Web/HTTP/Status/411
---
<div>{{HTTPSidebar}}</div>

<p>超文本傳輸協定 (HTTP) <code><strong>411 Length Required</strong></code> 用戶端錯誤表示伺服器拒絕接收沒有定義 {{HTTPHeader("Content-Length")}} 頭的請求。 </p>

<div class="note">
<p><strong>Note: </strong>by specification, when sending data in a series of chunks, the <code>Content-Length</code> header is omitted and at the beginning of each chunk you need to add the length of the current chunk in hexadecimal format. See {{HTTPHeader("Transfer-Encoding")}} for more details.</p>
</div>

<h2 id="狀態">狀態</h2>

<pre class="syntaxbox">411 Length Required</pre>

<h2 id="規範">規範</h2>

{{Specifications}}

<h2 id="參見">參見</h2>

<ul>
 <li>{{HTTPHeader("Content-Length")}}</li>
 <li>{{HTTPHeader("Transfer-Encoding")}}</li>
</ul>