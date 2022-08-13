---
title: Document.pointerLockElement
slug: Web/API/Document/pointerLockElement
translation_of: Web/API/DocumentOrShadowRoot/pointerLockElement
original_slug: Web/API/DocumentOrShadowRoot/pointerLockElement
---
<div>{{APIRef("DOM")}}</div>

<p>La propiedad <code>pointerLockElement</code> conserva el elemento adquirido, para el evento del mouse, mientras el bloqueo se encuentre activo .  Es <code>null</code> si el bloqueo se encuentra en estado pendiente para bloqueo, o si el bloqueo se ha liberado, es decir ya no se encuentra en estado bloqueado, o si el elemento bloqueado se encuentra en otro documento.</p>

<h2 id="Sintaxis">Sintaxis</h2>

<pre class="syntaxbox">var elemento = document.pointerLockElement;
</pre>

<h3 id="Valor_retornado">Valor retornado</h3>

<p>Un {{domxref("Element")}} o <code>null</code>.</p>

<h2 id="Especificaciones">Especificaciones</h2>

<table class="standard-table">
 <tbody>
  <tr>
   <th scope="col">Especificación</th>
   <th scope="col">Estado</th>
   <th scope="col">Comentario</th>
  </tr>
  <tr>
   <td>{{SpecName('Bloquear puntero','l#extension-to-the-document-interface','Document')}}</td>
   <td>{{Spec2('Pointer lock')}}</td>
   <td>Extiende de la interfaz <code>Document</code></td>
  </tr>
 </tbody>
</table>

<h2 id="Browser_compatibility" name="Browser_compatibility">Compatibilidad del Navegador</h2>

{{Compat("api.Document.pointerLockElement")}}

<h2 id="Véase_también">Véase también:</h2>

<ul>
 <li>{{ domxref("Document.exitPointerLock()") }}</li>
 <li>{{ domxref("Element.requestPointerLock()") }}</li>
 <li><a href="/en-US/docs/WebAPI/Pointer_Lock">Pointer Lock</a></li>
</ul>