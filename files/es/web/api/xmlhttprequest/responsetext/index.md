---
title: XMLHttpRequest.responseText
slug: Web/API/XMLHttpRequest/responseText
translation_of: Web/API/XMLHttpRequest/responseText
---

<div>{{APIRef('XMLHttpRequest')}}</div>

<p>La propiedad <strong><code>XMLHttpRequest.responseText</code></strong>  devuelve un <strong><code>DOMString</code></strong> que contiene la  respuesta a la consulta como un texto o null si la consulta  no tuvo exito o  aun no ha sido completada. la propiedad <strong><code>responseText</code> </strong> tendra una respuesta parcial como retorno aunque la consulta no haya sido  completada. si <strong>responseType</strong> contiene algo que no sea un string vacio o un "text", el acceso a <strong>responseText</strong> sera <strong>throw <code>InvalidStateError</code> exception</strong>.</p>

<h2 id="Ejemplo._Lanza_una_excepción_InvalidStateError">Ejemplo. Lanza  una excepción <strong><code>InvalidStateError</code></strong></h2>

<pre class="brush: js">var xhr = new XMLHttpRequest();
xhr.open('GET', '/server', true);

// If specified, responseType must be empty string or "text"
xhr.responseType = 'text';

xhr.onload = function () {
    if (xhr.readyState === xhr.DONE) {
        if (xhr.status === 200) {
            console.log(xhr.response);
            console.log(xhr.responseText);
        }
    }
};

xhr.send(null);</pre>

<h2 id="Especificaciones">Especificaciones</h2>

<table class="standard-table">
 <tbody>
  <tr>
   <th scope="col">Especificaciones</th>
   <th scope="col">estado</th>
   <th scope="col">Comentarios</th>
  </tr>
  <tr>
   <td>{{SpecName('XMLHttpRequest', '#the-responsetext-attribute')}}</td>
   <td>{{Spec2('XMLHttpRequest')}}</td>
   <td>WHATWG living standard</td>
  </tr>
 </tbody>
</table>

<h2 id="Compatibilidad_con_navegadores">Compatibilidad con navegadores</h2>

{{Compat("api.XMLHttpRequest.responseText")}}