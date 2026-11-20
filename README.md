# Mini Proyecto 02 — Control de producción y distribución de paquetes en MIPS

**Asignatura:** UCOM250 — Organización y Arquitectura de Computadores  
**Integrantes:** Ricardo Perez, Eduardo Nogales  
**Año:** 2026  
**Fecha:** 19/11/2026

---

## Descripción

### Escenario

Este mini proyecto desarrolla dos programas independientes en lenguaje ensamblador MIPS para simular el procesamiento de datos operativos. El objetivo es aplicar la carga y almacenamiento en memoria, las operaciones aritméticas, la reutilización de registros y las bifurcaciones condicionales en situaciones prácticas.

**Escenario 1 — Control de producción de una fábrica:** Una planta de componentes electrónicos parte de registros de 24 y 40 unidades. El programa realiza sumas y restas sucesivas, actualiza registros temporales y comprueba una suma de control. Si el resultado es distinto de cero, guarda **303** en la variable `estado`; de lo contrario, guarda **0**. Con los datos iniciales documentados, la suma de control es **96** y se almacena **303**.

**Escenario 2 — Control de distribución de paquetes:** Una empresa de logística parte de registros de 45 y 60 paquetes. El programa calcula acumulados y diferencias, reutiliza registros y verifica el resultado de una operación final. Si la suma de control es distinta de cero, almacena **505** en `estado`; en caso contrario, almacena **0**. Con los datos iniciales documentados, la suma de control es **180** y se almacena **505**.

**Uso:** Abrir [Mipsy Web](https://cgi.cse.unsw.edu.au/~cs1521/mipsy/), cargar o pegar el código MIPS de uno de los escenarios y ejecutarlo. Revisar los registros y la memoria para comprobar las operaciones y el valor final de `estado`. Cada programa se ejecuta por separado.
En la segunda parte del proyecto se analizan las instrucciones MIPS de formatos R, I y J utilizadas en ambos escenarios, identificando sus campos, registros, operaciones y efectos sobre el procesador. También se documenta el funcionamiento de los componentes principales del datapath, incluyendo el PC, las memorias, el banco de registros, la ALU, los multiplexores y la unidad de control.

---

### Referencias utilizadas

1. University of New South Wales (UNSW). (s. f.). *Mipsy Web - MIPS Simulator*. https://cgi.cse.unsw.edu.au/~cs1521/mipsy/

2. Citas APA – Normas APA. (s. f.). *Citas APA*. https://normas-apa.org/citas/

3. Patterson, D. A., & Hennessy, J. L. (2020). *Computer Organization and Design MIPS Edition: The Hardware/Software Interface* (6th ed.). Morgan Kaufmann.

4. CiteMaker CiteWeb. (s. f.). *CiteMaker CiteWeb | APA 7th Edn.*. https://chromewebstore.google.com/detail/citemaker-citeweb-apa-7th/naankklphfojljboaokgfbheobbgenka
