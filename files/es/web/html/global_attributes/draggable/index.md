---
title: draggable
slug: Web/HTML/Global_attributes/draggable
tags:
  - Atributos globales
  - Experimental
  - HTML
  - Referencia
translation_of: Web/HTML/Global_attributes/draggable
original_slug: Web/HTML/Atributos_Globales/draggable
browser-compat: html.global_elements.draggable
---
<p class="note">{{HTMLSidebar("Global_attributes")}}{{SeeCompatTable}}</p>

<p>El <a href="/es/docs/Web/HTML/Atributos_Globales">atributo global </a>draggable es un atributo enumerado que indica si el elemento puede ser arrastrado , usando el {{domxref("HTML_Drag_and_Drop_API","HTML Drag and Drop API")}} . Puede tener los siguientes valores :</p>

<ul>
 <li><code>true</code> , indica que el elemento puede ser arrastrado.</li>
 <li><code>false</code>, indica que el elemento no puede ser arrastrado .</li>
</ul>

<p>Si este atriuto no se establece , su valor por default es <code>auto</code> , significando que el comportamiento debe de ser el definido por default en el explorador .</p>

<p>Este es un atributo <em>enumerado </em> y no uno <em>booleano</em> . Esto signigica que el uso explícito de uno de los valores <em>true </em>o <em>false </em>es obligatorio y que una declaración como <code>&lt;label draggable&gt;Example Label&lt;/label&gt; </code>no está permitida . El uso correcto es  <code>&lt;label draggable="true"&gt;Example Label&lt;/label&gt;</code>.</p>

<p>Por default , unicamente el texto , las imagenes y los vínculos pueden ser arrastrados . Para todos los demás elementos el evento <strong>{{domxref('GlobalEventHandlers.ondragstart','ondragstart')}}</strong>  debe de ser establecido para el mecanismo de arrastrar y soltar para que funcione , como se muestra en este <a href="/en-US/docs/DragDrop/Drag_Operations" title="https://developer.mozilla.org/En/DragDrop/Drag_Operations">ejempl</a>o .</p>

<p> </p>

<h2 id="Especificaciones">Especificaciones</h2>

{{Specifications}}

<h2 id="Compatibilidad_de_Navegadores">Compatibilidad de Navegadores</h2>

{{Compat}}

<p><span style="font-size: 30.002px; letter-spacing: -1px; line-height: 30.002px;"><strong>Ver también</strong></span></p>

<ul>
 <li><a href="/es/docs/Web/HTML/Atributos_Globales">atributos globales </a></li>
</ul>