---
title: Range.getClientRects()
slug: Web/API/Range/getClientRects
tags:
  - API
  - Experimental
  - Rango
  - Vista CSSOM
  - metodo
translation_of: Web/API/Range/getClientRects
---
<p>{{ApiRef("DOM")}}{{ seeCompatTable }}</p>

<p>El método <strong><code>Range.getClientRects()</code></strong><strong> </strong>regresa una lista de objetos {{ domxref("DOMRect") }} los cuales representan el área de la pantalla ocupada por el <a href="/es/DOM/range" title="https://developer.mozilla.org/es/dom:range">rango</a>. El resultado es generado al agregar los resultados de las llamadas a {{ domxref("Element.getClientRects()") }} para cada uno de los elementos dentro del rango.</p>

<h2 id="Syntax" name="Syntax">Sintaxis</h2>

<pre class="syntaxbox"><em>rectList</em> = <em>range</em>.getClientRects()
</pre>

<h2 id="Example" name="Example">Ejemplo</h2>

<pre class="brush: js">range = document.createRange();
range.selectNode(document.getElementsByTagName("div").item(0));
rectList = range.getClientRects();
</pre>

<h2 id="Specification" name="Specification">Especificación</h2>

<table class="standard-table">
 <tbody>
  <tr>
   <th scope="col">Especificación</th>
   <th scope="col">Estatus</th>
   <th scope="col">Comentario</th>
  </tr>
  <tr>
   <td>{{SpecName('CSSOM View', '#dom-range-getclientrects', 'Range.getClientRects()')}}</td>
   <td>{{Spec2('CSSOM View')}}</td>
   <td>Especificación inicial.</td>
  </tr>
 </tbody>
</table>

<h2 id="Compatibilidad_en_los_Navegadores">Compatibilidad en los Navegadores</h2>

{{Compat("api.Range.getClientRects")}}

<h2 id="Ver_también">Ver también</h2>

<ul>
 <li>{{domxref("Range")}}</li>
</ul>