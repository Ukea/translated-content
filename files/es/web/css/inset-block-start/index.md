---
title: inset-block-start
slug: Web/CSS/inset-block-start
translation_of: Web/CSS/inset-block-start
---
<div>{{CSSRef}}{{SeeCompatTable}}</div>

<p>La propiedad de <a href="/en-US/docs/Web/CSS" title="CSS">CSS</a><span class="seoSummary"> <strong><code>inset-block-start</code></strong> define el desplazamiento de inicio de bloque lógico de un elemento, que se asigna a una inserción física en función del modo de escritura, la direccionalidad y la orientación del texto del elemento. Corresponde a la propiedad {{cssxref ("top")}}, {{cssxref ("right")}}, {{cssxref ("bottom")}}, o {{cssxref ("left")}} dependiendo de la propiedad en los valores definidos para {{cssxref ("modo de escritura")}}, {{cssxref ("dirección")}} y {{cssxref ("orientación de texto")}}.</span></p>

<pre class="brush:css no-line-numbers">/* &lt;length&gt; values */
inset-block-start: 3px;
inset-block-start: 2.4em;

/* &lt;percentage&gt;s of the width or height of the containing block */
inset-block-start: 10%;

/* Keyword value */
inset-block-start: auto;

/* Global values */
inset-block-start: inherit;
inset-block-start: initial;
inset-block-start: unset;
</pre>

<p>{{cssinfo}}</p>

<h2 id="Sintaxis">Sintaxis</h2>

<h3 id="Valores">Valores</h3>

<p>La propiedad <code>inset-block-start</code> toma los mismos valores de la propiedad {{cssxref("left")}}.</p>

<h3 id="Sintaxis_formal">Sintaxis formal</h3>

{{csssyntax}}

<h2 id="Ejemplo">Ejemplo</h2>

<h3 id="Contenido_HTML">Contenido HTML</h3>

<pre class="brush: html">&lt;div&gt;
  &lt;p class="exampleText"&gt;Example text&lt;/p&gt;
&lt;/div&gt;
</pre>

<h3 id="Contenido_CSS">Contenido CSS</h3>

<pre class="brush: css">div {
  background-color: yellow;
  width: 120px;
  height: 120px;
}

.exampleText {
  writing-mode: vertical-lr;
  position: relative;
  inset-block-start: 20px;
  background-color: #c8c800;
}</pre>

<p>{{EmbedLiveSample("Ejemplo", 140, 140)}}</p>

<h2 id="Especificación">Especificación</h2>

<table class="standard-table">
 <thead>
  <tr>
   <th scope="col">Especificación</th>
   <th scope="col">Estado</th>
   <th scope="col">Comentario</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>{{SpecName("CSS Logical Properties", "#propdef-inset-block-start", "inset-block-start")}}</td>
   <td>{{Spec2("CSS Logical Properties")}}</td>
   <td>Definición inicial.</td>
  </tr>
 </tbody>
</table>

<h2 id="Compatibilidad_en_navegadores">Compatibilidad en navegadores</h2>

<p>{{Compat("css.properties.inset-block-start")}}</p>

<h2 id="Mira_también">Mira también</h2>

<ul>
 <li>Las propiedades que definen otras inserciones:: {{cssxref("inset-block-end")}}, {{cssxref("inset-inline-start")}}, y {{cssxref("inset-inline-end")}}</li>
 <li>Las propiedades físicas mapeadas: {{cssxref("top")}}, {{cssxref("right")}}, {{cssxref("bottom")}}, y {{cssxref("left")}}</li>
 <li>{{cssxref("writing-mode")}}, {{cssxref("direction")}}, {{cssxref("text-orientation")}}</li>
</ul>