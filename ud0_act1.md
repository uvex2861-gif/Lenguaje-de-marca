# Ejercicio1

Si el texto lo abres no se  podra leer nada porque no esta en el formato correspondiente pero si lo cambias y se pone .html en vez de .txt si que lo podra leer

```
<h1>Texto grande</h1>
<h3>Texto Pequeño</h3>
```
# Ejercicio2

```
<dam>
  <modulo><titulo>Lenguaje de Marcas</titulo>
    <contenido>
      <unidad>Introducción</unidad>
      <unidad>HTML</unidad>
      <unidad>CSS</unidad>
    …
    </contenido>
  </modulo>

  <modulo><titulo>Base de Datos</titulo>
    <contenido>
      <unidad>Introducción</unidad>
      <unidad>Sistemas de almacenamiento de la información</unidad>
      <unidad>Diseño lógico de bases de datos</unidad>
      …
    </contenido>
  </modulo>

  <modulo><titulo>Implantació de Sistemes Operatius</titulo>
    <contenido>
      <unidad>Introducción a los sistemas operativos</unidad>
      <unidad>Windows Server 2022</unidad>
…
    </contenido>
  </modulo>

…
</dam>
```

# Ejercicio3

```
<mundo>
  <pais>
    <nombre>España</nombre>
      <continente>Europa</continente>
      <capital>Madrid</capital>
      <poblacion>48 millones</poblacion>
  </pais>
  <pais>
      <nombre>Japón</nombre>
      <continente>Asia</continente>
      <capital>Tokio</capital>
      <poblacion>125 millones</poblacion>
  </pais>
  <pais>
    <nombre>Argentina</nombre>
      <continente>América del Sur</continente>
      <capital>Buenos Aires</capital>
      <poblacion>46 millones</poblacion>
  </pais>
</mundo>
```


# Ejercicio 4

Vocabulario: catalogo, libro, titulo, formato, isbn, autor, paginas, editorial, idioma, sinopsis
"catalogo" es la raíz y contiene los elementos libro
Un libro contiene obligatoriamente: titulo, isbn, autor, editorial e idioma.
Los elementos formato, paginas y sinopsis son opcionales

```
<catalogo>
  <libro>
    <titulo>FALCO</titulo>
    <formato>En papel</formato>
    <isbn>9788420419688</isbn>
    <autor>ARTURO PEREZ REVERTE</autor>
    <paginas>296</paginas>
    <editorial>ALFAGUARA</editorial>
    <idioma>CASTELLÀ</idioma>
  </libro>

  <libro>
    <titulo>TODO ALATRISTE</titulo>
    <formato>EBOOK</formato>
    <isbn>9788420425528</isbn>
    <autor>ARTURO PEREZ REVERTE</autor>
    <editorial>ALFAGUARA</editorial>
    <idioma>CASTELLÀ</idioma>
  </libro>

  <libro>
    <titulo>HOMBRES BUENOS</titulo>
    <formato>En papel</formato>
    <isbn>9788466329804</isbn>
    <autor>ARTURO PEREZ REVERTE</autor>
    <editorial>PUNTO DE LECTURA, 2024</editorial>
    <idioma>CASTELLÀ</idioma>
    <sinopsis>La heróica aventura de quienes se atrevieron a cambiar el mundo con libros. En tiempos de oscuridad siempre hubo hombres buenos que lucharon para llevar las luces y el progreso. Y otros que procuraron impedirlo.</sinopsis>
  </libro>
</catalogo>


```
