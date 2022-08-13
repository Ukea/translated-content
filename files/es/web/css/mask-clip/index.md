---
title: '-webkit-mask-clip'
slug: Web/CSS/mask-clip
tags:
  - CSS
translation_of: Web/CSS/mask-clip
translation_of_original: Web/CSS/-webkit-mask-clip
original_slug: Web/CSS/-webkit-mask-clip
---
<p>{{ CSSRef() }}</p>

<p>{{ Non-standard_header() }}</p>

<p>Si se especificado {{ Cssxref("-webkit-mask-image") }} , <code style="font-size: 14px; font-style: normal; line-height: 1.5;">-webkit-mask-clip</code> determina el comportamiento de recorte (clipping) de la imagen de máscara.</p>

<p>{{cssinfo}}</p>

<h2 id="Síntaxis">Síntaxis</h2>

{{csssyntax}}

<p>donde:</p>

<dl>
 <dt>&lt;clip-style&gt;</dt>
 <dd><code>border | padding | content | text</code></dd>
</dl>

<h2 id="Valores">Valores</h2>

<dl>
 <dt>border</dt>
 <dd><code><font face="Open Sans, Arial, sans-serif">Si se ha especificado </font>border</code> , la máscara de imagen se extiende hasta el borde del elemento.</dd>
 <dt>padding</dt>
 <dd>Si se ha especificado <code>padding</code> , la imagen de máscara de extiendo hasta el padding (relleno) del elemento.</dd>
 <dt>content</dt>
 <dd>Si se ha espeficiado c<code>ontent</code> , la imagen de máscara se recorta al tamaño del contenido del elemento.</dd>
 <dt>text</dt>
 <dd>Si se ha especificado  <code>text</code> , la imagen de máscara de recorta al tamaño del texto del elemento.</dd>
</dl>

<h2 id="Ejemplo">Ejemplo</h2>

<pre class="brush: css">div {
    -webkit-mask-image: url('images/mask.png');
    -webkit-mask-clip: padding;
}
</pre>

<h2 id="Browser_Compatibility" name="Browser_Compatibility">Compatibilidad con los distintos navegadores</h2>

{{Compat("css.properties.mask-clip")}}

<h2 id="Ver_además">Ver además</h2>

<p>{{ cssxref("-webkit-mask") }}, {{ cssxref("-webkit-mask-origin") }}, {{ cssxref("-webkit-mask-box-image") }}, {{ cssxref("-webkit-mask-image") }},{{ cssxref("-webkit-mask-composite") }},{{ cssxref("-webkit-mask-repeat") }}</p>