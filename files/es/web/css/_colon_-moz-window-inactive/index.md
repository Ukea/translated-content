---
title: ':-moz-window-inactive'
slug: 'Web/CSS/:-moz-window-inactive'
tags:
  - CSS
  - 'CSS:Extensiones Mozilla'
  - NeedsMobileBrowserCompatibility
  - No estándar(2)
  - Referencia CSS
translation_of: 'Web/CSS/:-moz-window-inactive'
---
<div>{{CSSRef}}</div>

<h2 id="Resumen">Resumen</h2>

<p>La <a href="/es/docs/Web/CSS/Pseudo-classes">pseudo-clase </a><a href="/es/docs/Web/CSS">CSS</a> <a href="/en-US/docs/Web/CSS/Pseudo-classes"> </a><code>:-moz-window-inactive</code> selecciona cualquier elemento mientras está en una ventana inactiva.</p>

<div class="note"><strong>Nota:</strong> Antes de añadir esta pseudo-clase, dar  dieferentes estilos a las ventanas de fondo podría lograrse con el atributo (<code>active="true"</code>) en la venta del nivel superior XUL. Este atributo ya no se usa.</div>

<p><code>:-moz-window-inactive</code> funciona también en documentos de contenido HTML.</p>

<h2 id="Ejemplo">Ejemplo</h2>

<p>Este ejemplo modifica la apariencia del fondo de una caja dependiendo de si está o no en una ventana activa.</p>

<pre class="brush: html">&lt;style type="text/css"&gt;
#mybox {
  background: linear-gradient(to bottom, blue, cyan);
}

#mybox:-moz-window-inactive {
  background: cyan;
}
&lt;/style&gt;

&lt;div id="mybox" style="width:200px; height:200px;"&gt;
  &lt;p&gt;This is a box!&lt;/p&gt;
&lt;/div&gt;
</pre>

<p>Puedes verlo aquí en un <a href="/samples/cssref/moz-window-inactive.html">ejemplo en directo</a>.</p>

<h2 id="Especificaciones">Especificaciones</h2>

<p>No es parte de ninguna especificación.</p>

<h2 id="Compatibilidad_con_los_distintos_navegadores">Compatibilidad con los distintos navegadores</h2>

{{Compat("css.selectors.-moz-window-inactive")}}