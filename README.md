# mccp-sales-deck · redirección

Cascarón. El repositorio real es **[woztell-sanuker/mccp-sales-deck](https://github.com/woztell-sanuker/mccp-sales-deck)**
y se publica en <https://woztell-sanuker.github.io/mccp-sales-deck/>.

Existe solo para que no mueran los enlaces `ebarcos.github.io/mccp-sales-deck/...` que ya circulan.
`index.html` reenvía la raíz. `404.html` captura cualquier otra ruta y la manda a la **raíz
del repo** en el host nuevo, conservando query y hash: así un enlace antiguo a un fichero
versionado aterriza en la versión vigente —con barra de navegación— y no en el artefacto
sellado, que ya no la lleva. Los `#N` siguen funcionando porque los dos decks los leen.
