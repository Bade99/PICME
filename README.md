# PICME

## GO (D decidió no funcionar así q abandonamos el bote)

### Lenguaje del Server: D
## Instalación de D
1. [Descargar](https://dlang.org/download.html) e instalar el compilador DMD
2. [Descargar](https://github.com/dlang/dub/releases) el Package Manager de D, DUB, no se instala, meté el exe en alguna carpeta que quieras
3. Agregar DUB al PATH: Equipo -> Click derecho -> Propiedades -> Configuración Avanzada del Sistema -> Variables de Entorno -> En "Variables del sistema" ó "Variables de usuario" seleccionar la que diga "Path" -> Editar -> Examinar -> Buscá la carpeta donde hayas puesto DUB -> Aceptar x2
4. En Visual Studio ir a "Extenssions"->"Manage Extensions"->Buscar->visuald->Descargar/Instalar

## Creacion de proyecto desde 0
1. En cmd: dub init <nombre>
2. En dub.sdl o .json (dependiendo el q elijas) agregar dependencias de paquetes de dub: dependency "vibe-d" version="~>0.8.0"
3. En cmd: dub add vibe-d
4. Creas la solución de visual studio con: dub generate visuald

### Diseño de UI/UX: Figma (nooooooooooooooooooo) o Adobe XD (si)

### Posibles Lenguajes
- Go
- D 
- PHP
- WebAssembly
- Javascript
- Rust?
### Lenguajes Expulsados (para el server)
- Ruby
- Scala
- C
- C++
- Python
### Para la próxima:
- D (euge le da una chance)
- C# (euge investiga)

### Recursos Lenguajes
- [Server en D con MongoDB](https://d.readthedocs.io/en/latest/examples.html#web-application)
- [D Programming Basics](https://www.youtube.com/watch?v=rwZFTnf9bDU)
- [D Documantation](https://dlang.org/documentation.html)
- [Embedding Python in D programming language](https://www.youtube.com/watch?v=v2oM5Wli2Bw)
- [Allocating Memory with D](https://www.youtube.com/watch?v=_PB6Hdi4R7M)
- [curso GO](https://www.youtube.com/watch?v=G3PvTWRIhZA&list=PLQVvvaa0QuDeF3hP0wQoSxpkqgRcgxMqXScanner)
- [GO Web App](https://golang.org/doc/articles/wiki/)
- [Resumen GO](https://golangbot.com/learn-golang-series/)

### Recursos Scanner
- [Finviz](https://finviz.com/)
- [Trade Ideas](https://www.trade-ideas.com/products/)
- [Benzinga](https://pro.benzinga.com/screener/)
- [APIs de información financiera](https://towardsdatascience.com/best-5-free-stock-market-apis-in-2019-ad91dddec984)
- [Stock Rober](https://www.stockrover.com/plans/)
- [Hammerstone](https://www.hammerstonemarkets.com/)

### Recursos Picme
- [Pagina para vender Fotos y Diseños](https://www.patreon.com/)

### [Encuesta PICME](https://docs.google.com/forms/d/17f9voyBNncbG_35r3f-m2RkBAduS2ZRfFol630MFhDY/edit?ts=5f0394be)
[Formulario PICME](https://forms.gle/FwJPuzNHHgCMuV5p8)

### [Encuesta Scanner / Screener](https://docs.google.com/forms/d/1dox4yqVDsdFaTCt_beUm6hk9xl0pVeIvzqzqci-aWPc/edit?ts=5f03971e)
[Formulario Scanner](https://forms.gle/SMdYpjBgeRpHPagV9)

### Estructura del Scanner
- Corre en la Web, y es gratuito
- Hay usuarios, te podés registrar, guardás filtros, datos de búsqueda, alertas por mail/cel/etc
- Tabla con los stocks
- Gráfico de los stocks (extra: interactivo, podés marcar datos y cosas)
