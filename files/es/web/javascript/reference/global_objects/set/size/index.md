---
title: Set.prototype.size
slug: Web/JavaScript/Reference/Global_Objects/Set/size
translation_of: Web/JavaScript/Reference/Global_Objects/Set/size
original_slug: Web/JavaScript/Referencia/Objetos_globales/Set/size
---
<div>{{JSRef}}</div>

<p>La propiedad de acceso <code><strong>size</strong></code> devuelve el número de elementos que hay en el objeto {{jsxref("Set")}}.</p>

<h2 id="Descripción">Descripción</h2>

<p>El valor de <code>size</code> es un entero que representa cuantas entradas tiene el objeto <code>Set</code>. La función de accesso set para <code>size</code> es <code>undefined</code>; no se puede cambiar esta propiedad.</p>

<h2 id="Ejemplos">Ejemplos</h2>

<h3 id="Usando_size">Usando <code>size</code></h3>

<pre class="brush:js">var mySet = new Set();
mySet.add(1);
mySet.add(5);
mySet.add("un texto")

mySet.size; // 3
</pre>

<h2 id="Especificaciones">Especificaciones</h2>

<table class="standard-table">
 <tbody>
  <tr>
   <th scope="col">Especificación</th>
   <th scope="col">Estatus</th>
   <th scope="col">Comentario</th>
  </tr>
  <tr>
   <td>{{SpecName('ES6', '#sec-get-set.prototype.size', 'Set.prototype.size')}}</td>
   <td>{{Spec2('ES6')}}</td>
   <td>Definición inicial</td>
  </tr>
  <tr>
   <td>{{SpecName('ESDraft', '#sec-get-set.prototype.size', 'Set.prototype.size')}}</td>
   <td>{{Spec2('ESDraft')}}</td>
   <td> </td>
  </tr>
 </tbody>
</table>

<h2 id="Compatibilidad_de_navegadores">Compatibilidad de navegadores</h2>

{{Compat("javascript.builtins.Set.size")}}

<h2 id="Ver_también">Ver también</h2>

<ul>
 <li>{{jsxref("Set")}}</li>
</ul>