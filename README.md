# emmet
Справочник EMMET сокращений для ускорения верстки

<p>Справочник EMMET сокращений или шпаргалка <strong>EMMET</strong> представляет собой сборник всех комбинаций команд или аббревиатур широко известного плагина для ускорения верстки. EMMET может <s>все</s> использоваться совместно с такими редакторами, как <strong>Sublime Text</strong>, <strong>PHPStorm</strong> и <strong>WebStorm</strong>, <strong>NetBeans</strong>, <strong>Eclipse</strong>, <strong>Aptana</strong>, <strong>Coda</strong>, <strong>TextMate</strong>, <strong>Komodo Edit</strong>, <strong>Notepad++</strong>, <strong>CodeMirror</strong>, <strong>Brackets</strong>, <strong>Adobe Dreamviewer</strong> и <strong>Ace</strong></p>

<div class="table-wrapper"><table style="table-layout: auto">
<tbody><tr>
<td><h4>Сокращение</h4></td>
<td><h4>Расшифровка сокращения</h4></td>
</tr>
<tr>
<td colspan="2"><h5>Базовый синтаксис EMMET</h5></td>
</tr>
<tr>
<td>Дочерний: &gt;</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">nav&gt;ul&gt;li</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tag">&lt;<span class="hljs-name">nav</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">ul</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">li</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;/<span class="hljs-name">ul</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="6"><div class="hljs-ln-n" data-line-number="6"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="6"><span class="hljs-tag">&lt;/<span class="hljs-name">nav</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>Соединение: +</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">div+p+bq</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tag">&lt;<span class="hljs-name">div</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tag">&lt;<span class="hljs-name">p</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"><span class="hljs-tag">&lt;<span class="hljs-name">blockquote</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">blockquote</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>Поместить выше (в дереве HTML): ^</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">div&gt;p&gt;span+em^bq</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tag">&lt;<span class="hljs-name">div</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">p</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">span</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">em</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">em</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">blockquote</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">blockquote</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>Группировать: ()</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">div&gt;(header&gt;ul&gt;li)+footer&gt;p</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">div</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">header</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">ul</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">li</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="6"><div class="hljs-ln-n" data-line-number="6"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="6"><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-tag">&lt;/<span class="hljs-name">ul</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="7"><div class="hljs-ln-n" data-line-number="7"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="7"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;/<span class="hljs-name">header</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="8"><div class="hljs-ln-n" data-line-number="8"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="8"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">footer</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="9"><div class="hljs-ln-n" data-line-number="9"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="9"><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">p</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="10"><div class="hljs-ln-n" data-line-number="10"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="10"><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-tag">&lt;/<span class="hljs-name">footer</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="11"><div class="hljs-ln-n" data-line-number="11"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="11"><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>Умножение: *</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">ul&gt;li*3</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tag">&lt;<span class="hljs-name">ul</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">li</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">li</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">li</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="6"><div class="hljs-ln-n" data-line-number="6"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="6"><span class="hljs-tag">&lt;/<span class="hljs-name">ul</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>Нумерация: $</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">ul&gt;li.item_$*3</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tag">&lt;<span class="hljs-name">ul</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"item_1"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"item_2"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"item_3"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="6"><div class="hljs-ln-n" data-line-number="6"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="6"><span class="hljs-tag">&lt;/<span class="hljs-name">ul</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>id и class</td>
<td>
<div class="code-wrapper"><pre class="hljs stylus"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">#header+<span class="hljs-selector-class">.class</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">&lt;<span class="hljs-selector-tag">div</span> id=<span class="hljs-string">"header"</span>&gt;&lt;/div&gt;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">&lt;<span class="hljs-selector-tag">div</span> class=<span class="hljs-string">"class"</span>&gt;&lt;/div&gt;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"> </td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-selector-id">#hdr</span><span class="hljs-selector-class">.cl_1</span><span class="hljs-selector-class">.cl_2</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="6"><div class="hljs-ln-n" data-line-number="6"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="6">&lt;<span class="hljs-selector-tag">div</span> id=<span class="hljs-string">"hdr"</span> class=<span class="hljs-string">"cl_1 cl_2"</span>&gt;&lt;/div&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>Атрибуты: []</td>
<td>
<div class="code-wrapper"><pre class="hljs stylus"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-selector-tag">a</span>[title=<span class="hljs-string">"Подсказка ссылки"</span>]</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">&lt;<span class="hljs-selector-tag">a</span> href=<span class="hljs-string">""</span> title=<span class="hljs-string">"Подсказка ссылки"</span>&gt;&lt;/a&gt;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"> </td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"><span class="hljs-selector-tag">td</span>[rowspan colspan title]</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5">&lt;<span class="hljs-selector-tag">td</span> rowspan=<span class="hljs-string">""</span> colspan=<span class="hljs-string">""</span> title=<span class="hljs-string">""</span>&gt;&lt;/td&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>Текст: {}</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">.class{свободный текст}</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"class"</span>&gt;</span>свободный текст<span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"> </td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">p&gt;{Кликните }+a{сюда}+{ скорее}</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-tag">&lt;<span class="hljs-name">p</span>&gt;</span>Кликните <span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">href</span>=<span class="hljs-string">""</span>&gt;</span>сюда<span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span> скорее<span class="hljs-tag">&lt;/<span class="hljs-name">p</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>Сокращение тегов</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">.class</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tag">&lt;<span class="hljs-name">div</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"class"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"> </td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">em&gt;.class</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-tag">&lt;<span class="hljs-name">em</span>&gt;</span><span class="hljs-tag">&lt;<span class="hljs-name">span</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"class"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">em</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="6"><div class="hljs-ln-n" data-line-number="6"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="6"> </td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="7"><div class="hljs-ln-n" data-line-number="7"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="7">ul&gt;.class</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="8"><div class="hljs-ln-n" data-line-number="8"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="8"><span class="hljs-tag">&lt;<span class="hljs-name">ul</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="9"><div class="hljs-ln-n" data-line-number="9"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="9"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">li</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"class"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="10"><div class="hljs-ln-n" data-line-number="10"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="10"><span class="hljs-tag">&lt;/<span class="hljs-name">ul</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="11"><div class="hljs-ln-n" data-line-number="11"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="11"> </td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="12"><div class="hljs-ln-n" data-line-number="12"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="12">table&gt;.row&gt;.col</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="13"><div class="hljs-ln-n" data-line-number="13"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="13"><span class="hljs-tag">&lt;<span class="hljs-name">table</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="14"><div class="hljs-ln-n" data-line-number="14"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="14"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">tr</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"row"</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="15"><div class="hljs-ln-n" data-line-number="15"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="15"><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">td</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"col"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="16"><div class="hljs-ln-n" data-line-number="16"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="16"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;/<span class="hljs-name">tr</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="17"><div class="hljs-ln-n" data-line-number="17"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="17"><span class="hljs-tag">&lt;/<span class="hljs-name">table</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td colspan="2"><h5>HTML сокращения</h5></td>
</tr>
<tr>
<td>!</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-meta">&lt;!doctype <span class="hljs-meta-keyword">html</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tag">&lt;<span class="hljs-name">html</span> <span class="hljs-attr">lang</span>=<span class="hljs-string">"en"</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">head</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">meta</span> <span class="hljs-attr">charset</span>=<span class="hljs-string">"UTF-8"</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">title</span>&gt;</span>Document<span class="hljs-tag">&lt;/<span class="hljs-name">title</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="6"><div class="hljs-ln-n" data-line-number="6"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="6"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;/<span class="hljs-name">head</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="7"><div class="hljs-ln-n" data-line-number="7"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="7"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">body</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="8"><div class="hljs-ln-n" data-line-number="8"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="8"> </td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="9"><div class="hljs-ln-n" data-line-number="9"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="9"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;/<span class="hljs-name">body</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="10"><div class="hljs-ln-n" data-line-number="10"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="10"><span class="hljs-tag">&lt;/<span class="hljs-name">html</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>a</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">href</span>=<span class="hljs-string">""</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>a:link</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"http://"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>a:mail</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">a</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"mailto:"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">a</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>base</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">base</span> <span class="hljs-attr">href</span>=<span class="hljs-string">""</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>br</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">br</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>link</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">link</span> <span class="hljs-attr">rel</span>=<span class="hljs-string">"stylesheet"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">""</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>link:css</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">link</span> <span class="hljs-attr">rel</span>=<span class="hljs-string">"stylesheet"</span> <span class="hljs-attr">href</span>=<span class="hljs-string">"style.css"</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>link:favicon</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;link rel=<span class="hljs-string">"shortcut icon"</span> <span class="hljs-built_in">type</span>=<span class="hljs-string">"image/x-icon"</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">href=<span class="hljs-string">"favicon.ico"</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>link:rss</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;link rel=<span class="hljs-string">"alternate"</span> <span class="hljs-built_in">type</span>=<span class="hljs-string">"application/rss+xml"</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">title=<span class="hljs-string">"RSS"</span> href=<span class="hljs-string">"rss.xml"</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>link:atom</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;link rel=<span class="hljs-string">"alternate"</span> <span class="hljs-built_in">type</span>=<span class="hljs-string">"application/atom+xml"</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">title=<span class="hljs-string">"Atom"</span> href=<span class="hljs-string">"atom.xml"</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>meta:utf</td>
<td>
<div class="code-wrapper"><pre class="hljs stylus"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;meta http-equiv=<span class="hljs-string">"Content-Type"</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-attribute">content</span>=<span class="hljs-string">"text/html;charset=UTF-8"</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>meta:vp</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">meta</span> <span class="hljs-attr">name</span>=<span class="hljs-string">"viewport"</span> <span class="hljs-attr">content</span>=<span class="hljs-string"><span class="hljs-string">"width=device-width,</span></span></span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-string">user-scalable=no, initial-scale=1.0,</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-string">maximum-scale=1.0, minimum-scale=1.0"</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>meta:compat</td>
<td>
<div class="code-wrapper"><pre class="hljs stylus"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;meta http-equiv=<span class="hljs-string">"X-UA-Compatible"</span> <span class="hljs-attribute">content</span>=<span class="hljs-string">"IE=7"</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>script:src</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">script</span> <span class="hljs-attr">src</span>=<span class="hljs-string">""</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">script</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>img</td>
<td>
<div class="code-wrapper"><pre class="hljs stylus"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;<span class="hljs-selector-tag">img</span> src=<span class="hljs-string">""</span> alt=<span class="hljs-string">""</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ifr</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">iframe</span> <span class="hljs-attr">src</span>=<span class="hljs-string">""</span> <span class="hljs-attr">frameborder</span>=<span class="hljs-string">"0"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">iframe</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>emb</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;embed src=<span class="hljs-string">""</span> <span class="hljs-built_in">type</span>=<span class="hljs-string">""</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>obj</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">object</span> <span class="hljs-attr">data</span>=<span class="hljs-string">""</span> <span class="hljs-attr">type</span>=<span class="hljs-string">""</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">object</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>map</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">map</span> <span class="hljs-attr">name</span>=<span class="hljs-string">""</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">map</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>map+</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">map</span> <span class="hljs-attr">name</span>=<span class="hljs-string">""</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">area</span> <span class="hljs-attr">shape</span>=<span class="hljs-string">""</span> <span class="hljs-attr">coords</span>=<span class="hljs-string">""</span> <span class="hljs-attr">href</span>=<span class="hljs-string">""</span> <span class="hljs-attr">alt</span>=<span class="hljs-string">""</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tag">&lt;/<span class="hljs-name">map</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>area</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">area</span> <span class="hljs-attr">shape</span>=<span class="hljs-string">""</span> <span class="hljs-attr">coords</span>=<span class="hljs-string">""</span> <span class="hljs-attr">href</span>=<span class="hljs-string">""</span> <span class="hljs-attr">alt</span>=<span class="hljs-string">""</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>form</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">form</span> <span class="hljs-attr">action</span>=<span class="hljs-string">""</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">form</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>form:get<br>form:post</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">form</span> <span class="hljs-attr">action</span>=<span class="hljs-string">""</span> <span class="hljs-attr">method</span>=<span class="hljs-string">"get"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">form</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tag">&lt;<span class="hljs-name">form</span> <span class="hljs-attr">action</span>=<span class="hljs-string">""</span> <span class="hljs-attr">method</span>=<span class="hljs-string">"post"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">form</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>label</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">label</span> <span class="hljs-attr">for</span>=<span class="hljs-string">""</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">label</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>input</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;input <span class="hljs-built_in">type</span>=<span class="hljs-string">"text"</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>inp</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;input <span class="hljs-built_in">type</span>=<span class="hljs-string">"text"</span> name=<span class="hljs-string">""</span> id=<span class="hljs-string">""</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>input:h</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;input <span class="hljs-built_in">type</span>=<span class="hljs-string">"hidden"</span> name=<span class="hljs-string">""</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>input:p</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;input <span class="hljs-built_in">type</span>=<span class="hljs-string">"password"</span> name=<span class="hljs-string">""</span> id=<span class="hljs-string">""</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>input:c</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;input <span class="hljs-built_in">type</span>=<span class="hljs-string">"checkbox"</span> name=<span class="hljs-string">""</span> id=<span class="hljs-string">""</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>input:r</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;input <span class="hljs-built_in">type</span>=<span class="hljs-string">"radio"</span> name=<span class="hljs-string">""</span> id=<span class="hljs-string">""</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>input:f</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;input <span class="hljs-built_in">type</span>=<span class="hljs-string">"file"</span> name=<span class="hljs-string">""</span> id=<span class="hljs-string">""</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>input:s</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;input <span class="hljs-built_in">type</span>=<span class="hljs-string">"submit"</span> value=<span class="hljs-string">""</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>input:i</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;input <span class="hljs-built_in">type</span>=<span class="hljs-string">"image"</span> src=<span class="hljs-string">""</span> alt=<span class="hljs-string">""</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>input:b</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;input <span class="hljs-built_in">type</span>=<span class="hljs-string">"button"</span> value=<span class="hljs-string">""</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>input:reset</td>
<td>
<div class="code-wrapper"><pre class="hljs bash"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">&lt;input <span class="hljs-built_in">type</span>=<span class="hljs-string">"reset"</span> value=<span class="hljs-string">""</span>&gt;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>select</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">select</span> <span class="hljs-attr">name</span>=<span class="hljs-string">""</span> <span class="hljs-attr">id</span>=<span class="hljs-string">""</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">select</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>select+</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">select</span> <span class="hljs-attr">name</span>=<span class="hljs-string">""</span> <span class="hljs-attr">id</span>=<span class="hljs-string">""</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">option</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">option</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tag">&lt;/<span class="hljs-name">select</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>opt</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">option</span> <span class="hljs-attr">value</span>=<span class="hljs-string">""</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">option</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>tarea</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">textarea</span> <span class="hljs-attr">name</span>=<span class="hljs-string">""</span> <span class="hljs-attr">id</span>=<span class="hljs-string">""</span> <span class="hljs-attr">cols</span>=<span class="hljs-string">"30"</span> <span class="hljs-attr">rows</span>=<span class="hljs-string">"10"</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tag">&lt;/<span class="hljs-name">textarea</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>video</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">video</span> <span class="hljs-attr">src</span>=<span class="hljs-string">""</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">video</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>audio</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">audio</span> <span class="hljs-attr">src</span>=<span class="hljs-string">""</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">audio</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bq</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">blockquote</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">blockquote</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>fst</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">fieldset</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">fieldset</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>btn</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">button</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">button</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>btn:s</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">button</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"submit"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">button</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>btn:b</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">button</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"button"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">button</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>btn:r</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">button</span> <span class="hljs-attr">type</span>=<span class="hljs-string">"reset"</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">button</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>sect</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">section</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">section</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>art</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">article</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">article</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>hdr</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">header</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">header</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ftr</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">footer</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">footer</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>str</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">strong</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">strong</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ol+</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">ol</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">li</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tag">&lt;/<span class="hljs-name">ol</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ul+</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">ul</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">li</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">li</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tag">&lt;/<span class="hljs-name">ul</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>dl+</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">dl</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">dt</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">dt</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">dd</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">dd</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"><span class="hljs-tag">&lt;/<span class="hljs-name">dl</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>table+</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">table</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">tr</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;/<span class="hljs-name">tr</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-tag">&lt;/<span class="hljs-name">table</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>tr+</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-tag">&lt;<span class="hljs-name">tr</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tab">	</span><span class="hljs-tag">&lt;<span class="hljs-name">td</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">td</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tag">&lt;/<span class="hljs-name">tr</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>c</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-comment">&lt;!-- Комментарий --&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cc:ie6</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-comment"><span class="hljs-comment">&lt;!--[if lte IE 6]&gt;</span></span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-comment"> </span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-comment">&lt;![endif]--&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cc:ie</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-comment"><span class="hljs-comment">&lt;!--[if IE]&gt;</span></span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-comment"> </span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-comment">&lt;![endif]--&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cc:noie</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-comment">&lt;!--[if !IE]&gt;&lt;!--&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"> </td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-comment">&lt;!--&lt;![endif]--&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>Любой тег</td>
<td>
<div class="code-wrapper"><pre class="hljs xml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">div</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tag">&lt;<span class="hljs-name">div</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">div</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"> </td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">span</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-tag">&lt;<span class="hljs-name">span</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">span</span>&gt;</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="6"><div class="hljs-ln-n" data-line-number="6"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="6"> </td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="7"><div class="hljs-ln-n" data-line-number="7"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="7">Любой другой тег</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="8"><div class="hljs-ln-n" data-line-number="8"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="8"><span class="hljs-tag">&lt;<span class="hljs-name">tagname</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-name">tagname</span>&gt;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td colspan="2"><h5>CSS сокращения</h5></td>
</tr>
<tr>
<td>pos</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">position</span>: relative;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>posa</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">position</span>: absolute;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>posr</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">position</span>: relative;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>posf</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">position</span>: fixed;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>t</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">top</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>t:a</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">top</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>r</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">right</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>r:a</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">right</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>b</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">bottom</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>b:a</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">bottom</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>l</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">left</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>l:a</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">left</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>z</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">z-index</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>za</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">z-index</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>fl</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">float</span>: left;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>fln</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">float</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>fr</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">float</span>: right;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cl</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">clear</span>: both;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>d</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">display</span>: block;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>dn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">display</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>di</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">display</span>: inline;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>dib</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">display</span>: inline-block;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>dt</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">display</span>: table;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>dtc</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">display</span>: table-cell;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>dtr</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">display</span>: table-row;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>v</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">visibility</span>: hidden;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>vv</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">visibility</span>: visible;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>oh</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">overflow</span>: hidden;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ovv</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">overflow</span>: visible;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>os</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">overflow</span>: scroll;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>oa</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">overflow</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>zm</td>
<td>
<div class="code-wrapper"><pre class="hljs yaml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attr">zoom:</span> <span class="hljs-number">1</span><span class="hljs-string">;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cu</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">cursor</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cup</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">cursor</span>: pointer;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cud</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">cursor</span>: default;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cuh</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">cursor</span>: hand;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cuhe</td>
<td>
<div class="code-wrapper"><pre class="hljs sql"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">cursor: <span class="hljs-keyword">help</span>;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cum</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">cursor</span>: move;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cut</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">cursor</span>: text;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>m</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">margin</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>m:a</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">margin</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>mt</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">margin-top</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>mta</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">margin-top</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>mr</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">margin-right</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>mra</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">margin-right</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>mb</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">margin-bottom</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>mba</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">margin-bottom</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ml</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">margin-left</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>mla</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">margin-left</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>p</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">padding</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>pt</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">padding-top</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>pr</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">padding-right</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>pb</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">padding-bottom</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>pl</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">padding-left</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bsh</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">box-shadow</span>: inset hoff voff blur color;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-<span class="hljs-attribute">box-shadow</span>: inset hoff voff blur color;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-attribute">box-shadow</span>: inset hoff voff blur color;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bshn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">box-shadow</span>: none;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-<span class="hljs-attribute">box-shadow</span>: none;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-attribute">box-shadow</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>w</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">width</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>wa</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">width</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>h</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">height</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ha</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">height</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>maw</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">max-width</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>mah</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">max-height</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>mw</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">min-width</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>mh</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">min-height</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>f</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>f+</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font</span>: <span class="hljs-number">1em</span> Arial,sans-serif;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>fw</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font-weight</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>fwn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font-weight</span>: normal;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>fwb</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font-weight</span>: bold;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>fs</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font-style</span>: italic;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>fsn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font-style</span>: normal;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>fsi</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font-style</span>: italic;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>fz</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font-size</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ff</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font-family</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ffs</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font-family</span>: serif;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ffss</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font-family</span>: sans-serif;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ffm</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font-family</span>: monospace;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ffa</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">font-family</span>: Arial, <span class="hljs-string">"Helvetica Neue"</span>, Helvetica,</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">sans-serif;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>va</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">vertical-align</span>: top;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>vm</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">vertical-align</span>: middle;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>vabl</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">vertical-align</span>: baseline;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>vb</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">vertical-align</span>: bottom;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>vs</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">vertical-align</span>: sub;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ta</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">text-align</span>: left;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>tac</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">text-align</span>: center;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>tar</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">text-align</span>: right;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>taj</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">text-align</span>: justify;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>td</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">text-decoration</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>tdu</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">text-decoration</span>: underline;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>tdo</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">text-decoration</span>: overline;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>tdl</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">text-decoration</span>: line-through;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>tt</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">text-transform</span>: uppercase;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ttn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">text-transform</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ttl</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">text-transform</span>: lowercase;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ts</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">text-shadow</span>: hoff voff blur <span class="hljs-number">#000</span>;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>tra</td>
<td>
<div class="code-wrapper"><pre class="hljs yaml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attr">text-shadow:</span> <span class="hljs-string">h</span> <span class="hljs-string">v</span> <span class="hljs-string">blur</span> <span class="hljs-string">rgba(0,</span> <span class="hljs-number">0</span><span class="hljs-string">,</span> <span class="hljs-number">0</span><span class="hljs-string">,</span> <span class="hljs-number">.5</span><span class="hljs-string">);</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ts+</td>
<td>
<div class="code-wrapper"><pre class="hljs yaml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attr">text-shadow:</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-comment">#000;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>tsn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">text-shadow</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>lh</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">line-height</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>lts</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">letter-spacing</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ws</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">white-space</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>wsn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">white-space</span>: normal;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>wsnw</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">white-space</span>: nowrap;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bg</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">background</span>: <span class="hljs-number">#000</span>;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bg+</td>
<td>
<div class="code-wrapper"><pre class="hljs less"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">background</span>: <span class="hljs-number">#fff</span> url(<span class="hljs-string"></span>) <span class="hljs-number">0</span> <span class="hljs-number">0</span> no-repeat;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">background</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bgc</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">background-color</span>: <span class="hljs-number">#fff</span>;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bgt</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">background-color</span>: transparent;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bgi</td>
<td>
<div class="code-wrapper"><pre class="hljs less"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">background-image</span>: url(<span class="hljs-string"></span>);</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bgin</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">background-image</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bgr</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">background-repeat</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bgrn</td>
<td>
<div class="code-wrapper"><pre class="hljs yaml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attr">background-repeat:</span> <span class="hljs-literal">no</span><span class="hljs-string">-repeat;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bgrx</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">background-repeat</span>: repeat-x;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bgry</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">background-repeat</span>: repeat-y;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bga</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">background-attachment</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>baf</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">background-attachment</span>: fixed;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bas</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">background-attachment</span>: scroll;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bgp</td>
<td>
<div class="code-wrapper"><pre class="hljs yaml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attr">background-position:</span> <span class="hljs-number">0</span> <span class="hljs-number">0</span><span class="hljs-string">;</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bgs</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">background-size</span>: ;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-attribute">background-size</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bsa</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">background-size</span>: auto;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-attribute">background-size</span>: auto;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>c</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">color</span>: <span class="hljs-number">#000</span>;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cra</td>
<td>
<div class="code-wrapper"><pre class="hljs yaml"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attr">color:</span> <span class="hljs-string">rgba(0,</span> <span class="hljs-number">0</span><span class="hljs-string">,</span> <span class="hljs-number">0</span><span class="hljs-string">,</span> <span class="hljs-number">.5</span><span class="hljs-string">);</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>op</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">opacity</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ct</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">content</span>: <span class="hljs-string">''</span>;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>q</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">quotes</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ol</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">outline</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>on</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">outline</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>tbl</td>
<td>
<div class="code-wrapper"><pre class="hljs less"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">table-layout</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cs</td>
<td>
<div class="code-wrapper"><pre class="hljs less"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">caption-side</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ec</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">empty-cells</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bd</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bd+</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border</span>: <span class="hljs-number">1px</span> solid <span class="hljs-number">#000</span>;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bdn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bdc</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-color</span>: <span class="hljs-number">#000</span>;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bdi</td>
<td>
<div class="code-wrapper"><pre class="hljs less"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">-webkit-border-image</span>: url(<span class="hljs-string"></span>);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-attribute">-moz-border-image</span>: url(<span class="hljs-string"></span>);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-attribute">-o-border-image</span>: url(<span class="hljs-string"></span>);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"><span class="hljs-attribute">border-image</span>: url(<span class="hljs-string"></span>);</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bdin</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">border-image</span>: none;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-<span class="hljs-attribute">border-image</span>: none;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">-o-<span class="hljs-attribute">border-image</span>: none;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"><span class="hljs-attribute">border-image</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bf</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">border</span>-fit: repeat;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-attribute">border</span>-fit: repeat;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bdle</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border</span>-length: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bsp</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-spacing</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bds</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-style</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bw</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-width</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bt</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-top</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bt+</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-top</span>: <span class="hljs-number">1px</span> solid <span class="hljs-number">#000</span>;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bdtn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-top</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>br</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-right</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>br+</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-right</span>: <span class="hljs-number">1px</span> solid <span class="hljs-number">#000</span>;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bdrn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-right</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bb</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-bottom</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bb+</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-bottom</span>: <span class="hljs-number">1px</span> solid <span class="hljs-number">#000</span>;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bdbn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-bottom</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bl</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-left</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bl+</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-left</span>: <span class="hljs-number">1px</span> solid <span class="hljs-number">#000</span>;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bdln</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-left</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bdrs</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">border-radius</span>: ;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-<span class="hljs-attribute">border-radius</span>: ;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-attribute">border-radius</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>btrr</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-top-right-radius</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bdtrs</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-top-left-radius</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bbrr</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-bottom-right-radius</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bblr</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">border-bottom-left-radius</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>lis</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">list-style</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>lisn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">list-style</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>lst</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">list-style-type</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>lstn</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">list-style-type</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>lstd</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">list-style-type</span>: disc;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>lstc</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">list-style-type</span>: circle;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>lsts</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">list-style-type</span>: square;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>lstdc</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">list-style-type</span>: decimal;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>lsi</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">list-style-image</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>lsin</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">list-style-image</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>!</td>
<td>
<div class="code-wrapper"><pre class="hljs properties"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-comment">!important</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>@f</td>
<td>
<div class="code-wrapper"><pre class="hljs css"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-keyword">@font-face</span> {</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-attribute">font-family</span>:;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-attribute">src</span>:<span class="hljs-built_in">url</span>();</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">}</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>@f+</td>
<td>
<div class="code-wrapper"><pre class="hljs css"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-keyword">@font-face</span> {</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-tab">	</span><span class="hljs-attribute">font-family</span>: <span class="hljs-string">'FontName'</span>;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tab">	</span><span class="hljs-attribute">src</span>: <span class="hljs-built_in">url</span>(<span class="hljs-string">'FileName.eot'</span>);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4"><span class="hljs-tab">	</span><span class="hljs-attribute">src</span>: <span class="hljs-built_in">url</span>(<span class="hljs-string">'FileName.eot?#iefix'</span>)</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-tab">	</span><span class="hljs-built_in">format</span>(<span class="hljs-string">'embedded-opentype'</span>),</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="6"><div class="hljs-ln-n" data-line-number="6"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="6"><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-built_in">url</span>(<span class="hljs-string">'FileName.woff'</span>) <span class="hljs-built_in">format</span>(<span class="hljs-string">'woff'</span>),</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="7"><div class="hljs-ln-n" data-line-number="7"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="7"><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-built_in">url</span>(<span class="hljs-string">'FileName.ttf'</span>) <span class="hljs-built_in">format</span>(<span class="hljs-string">'truetype'</span>),</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="8"><div class="hljs-ln-n" data-line-number="8"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="8"><span class="hljs-tab">	</span><span class="hljs-tab">	</span><span class="hljs-built_in">url</span>(<span class="hljs-string">'FileName.svg#FontName'</span>) <span class="hljs-built_in">format</span>(<span class="hljs-string">'svg'</span>);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="9"><div class="hljs-ln-n" data-line-number="9"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="9"><span class="hljs-tab">	</span><span class="hljs-attribute">font-style</span>: normal;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="10"><div class="hljs-ln-n" data-line-number="10"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="10"><span class="hljs-tab">	</span><span class="hljs-attribute">font-weight</span>: normal;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="11"><div class="hljs-ln-n" data-line-number="11"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="11">}</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>@i</td>
<td>
<div class="code-wrapper"><pre class="hljs less"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-keyword">@import</span> url(<span class="hljs-string"></span>);</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>@m</td>
<td>
<div class="code-wrapper"><pre class="hljs css"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-keyword">@media</span> screen {</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"> </td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">}</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>anim</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">animation</span>: ;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-o-<span class="hljs-attribute">animation</span>: ;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-attribute">animation</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>ap</td>
<td>
<div class="code-wrapper"><pre class="hljs less"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">-webkit-appearance</span>: none;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-attribute">-moz-appearance</span>: none;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-attribute">appearance</span>: none;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>bgie</td>
<td>
<div class="code-wrapper"><pre class="hljs less"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">filter</span>:<span class="hljs-attribute">progid</span>:DXImageTransform</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">.Microsoft.AlphaImageLoader</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">(src=<span class="hljs-string">'x.png'</span>,sizingMethod=<span class="hljs-string">'crop'</span>);</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>cm</td>
<td>
<div class="code-wrapper"><pre class="hljs less"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-comment">/* Комментарий */</span></td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>colm</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-attribute">columns</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>trf</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">transform</span>: ;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-<span class="hljs-attribute">transform</span>: ;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">-ms-<span class="hljs-attribute">transform</span>: ;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">-o-<span class="hljs-attribute">transform</span>: ;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-attribute">transform</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>trfr</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">transform</span>: rotate(angle);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-<span class="hljs-attribute">transform</span>: rotate(angle);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">-ms-<span class="hljs-attribute">transform</span>: rotate(angle);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">-o-<span class="hljs-attribute">transform</span>: rotate(angle);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-attribute">transform</span>: rotate(angle);</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>trfsc</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">transform</span>: scale(x, y);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-<span class="hljs-attribute">transform</span>: scale(x, y);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">-ms-<span class="hljs-attribute">transform</span>: scale(x, y);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">-o-<span class="hljs-attribute">transform</span>: scale(x, y);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-attribute">transform</span>: scale(x, y);</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>trft</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">transform</span>: translate(x, y);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-<span class="hljs-attribute">transform</span>: translate(x, y);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">-ms-<span class="hljs-attribute">transform</span>: translate(x, y);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">-o-<span class="hljs-attribute">transform</span>: translate(x, y);</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-attribute">transform</span>: translate(x, y);</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>tfo</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">transform-origin</span>: ;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-<span class="hljs-attribute">transform-origin</span>: ;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">-ms-<span class="hljs-attribute">transform-origin</span>: ;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">-o-<span class="hljs-attribute">transform-origin</span>: ;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-attribute">transform-origin</span>: ;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>trs</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">transition</span>: prop time;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-<span class="hljs-attribute">transition</span>: prop time;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">-ms-<span class="hljs-attribute">transition</span>: prop time;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">-o-<span class="hljs-attribute">transition</span>: prop time;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-attribute">transition</span>: prop time;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>trsde</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">transition-delay</span>: time;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-<span class="hljs-attribute">transition-delay</span>: time;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">-ms-<span class="hljs-attribute">transition-delay</span>: time;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">-o-<span class="hljs-attribute">transition-delay</span>: time;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-attribute">transition-delay</span>: time;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>trsdu</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">transition-duration</span>: time;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-<span class="hljs-attribute">transition-duration</span>: time;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">-ms-<span class="hljs-attribute">transition-duration</span>: time;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">-o-<span class="hljs-attribute">transition-duration</span>: time;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-attribute">transition-duration</span>: time;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>trsp</td>
<td>
<div class="code-wrapper"><pre class="hljs scss"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-<span class="hljs-attribute">transition-property</span>: prop;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-<span class="hljs-attribute">transition-property</span>: prop;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">-ms-<span class="hljs-attribute">transition-property</span>: prop;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">-o-<span class="hljs-attribute">transition-property</span>: prop;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"><span class="hljs-attribute">transition-property</span>: prop;</td></tr></tbody></table></pre></div>
</td>
</tr>
<tr>
<td>us</td>
<td>
<div class="code-wrapper"><pre class="hljs sql"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1">-webkit-user-<span class="hljs-keyword">select</span>: <span class="hljs-keyword">none</span>;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2">-moz-user-<span class="hljs-keyword">select</span>: <span class="hljs-keyword">none</span>;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3">-ms-user-<span class="hljs-keyword">select</span>: <span class="hljs-keyword">none</span>;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">user-<span class="hljs-keyword">select</span>: <span class="hljs-keyword">none</span>;</td></tr></tbody></table></pre></div>
</td>
</tr>
</tbody></table></div>

<p>В некоторые CSS сокращения можно подставлять свои значения, например:</p>

<div class="code-wrapper"><pre class="hljs css"><table class="hljs-ln"><tbody><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="1"><div class="hljs-ln-n" data-line-number="1"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="1"><span class="hljs-comment">/* mt20 */</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="2"><div class="hljs-ln-n" data-line-number="2"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="2"><span class="hljs-selector-class">.class</span>{</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="3"><div class="hljs-ln-n" data-line-number="3"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="3"><span class="hljs-tab">	</span><span class="hljs-attribute">margin-top</span>: <span class="hljs-number">20px</span>;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="4"><div class="hljs-ln-n" data-line-number="4"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="4">}</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="5"><div class="hljs-ln-n" data-line-number="5"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="5"> </td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="6"><div class="hljs-ln-n" data-line-number="6"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="6"><span class="hljs-comment">/* fsz20 */</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="7"><div class="hljs-ln-n" data-line-number="7"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="7"><span class="hljs-selector-class">.class</span>{</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="8"><div class="hljs-ln-n" data-line-number="8"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="8"><span class="hljs-tab">	</span><span class="hljs-attribute">font-size</span>: <span class="hljs-number">20px</span>;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="9"><div class="hljs-ln-n" data-line-number="9"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="9">}</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="10"><div class="hljs-ln-n" data-line-number="10"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="10"> </td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="11"><div class="hljs-ln-n" data-line-number="11"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="11"><span class="hljs-comment">/* p15 */</span></td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="12"><div class="hljs-ln-n" data-line-number="12"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="12"><span class="hljs-selector-class">.class</span>{</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="13"><div class="hljs-ln-n" data-line-number="13"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="13"><span class="hljs-tab">	</span><span class="hljs-attribute">padding</span>: <span class="hljs-number">15px</span>;</td></tr><tr><td class="hljs-ln-line hljs-ln-numbers" data-line-number="14"><div class="hljs-ln-n" data-line-number="14"></div></td><td class="hljs-ln-line hljs-ln-code" data-line-number="14">}</td></tr></tbody></table></pre></div>

								
