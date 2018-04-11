# Firmador PDF

Este es un pequeño firmador PDF creado para firmar documentos cumpliendo con la
[Política de Formatos Oficiales de los
Documentos Electrónicos Firmados Digitalmente](
https://www.mifirmadigital.go.cr/wp-content/uploads/2016/03/DCFD-Política-de-Formato-Oficial-v1.0.pdf
) de Costa Rica.

Se creó a partir de los ejemplos de la documentación de la [librería DSS](
https://ec.europa.eu/cefdigital/DSS/webapp-demo/doc/dss-documentation.html),
para uso personal del autor, pero aquí está el código fuente para quien quiera
un ejemplo de uso práctico bajo una licencia de software libre.

El ejemplo es mínimo, diseñado para funcionar con Java 8 y funciona en
GNU/Linux, macOS y Windows. Para instalar Firma Digital de forma adecuada en
GNU/Linux existen un par de artículos sobre cómo realizarlo en
[Fedora](https://fran.cr/instalar-firma-digital-costa-rica-linux-fedora/) y
[Ubuntu](https://fran.cr/instalar-firma-digital-costa-rica-gnu-linux-ubuntu-16-04/).

Para compilar el ejemplo se requiere Maven.

Para generar el JAR:

`mvn clean package`

Para ejecutar el JAR y firmar un documento PDF:

`java -jar target/firmador.jar`
