# InnovaTech Lab 2.0
Aplicación web React sin registro para proyectos de Tecnologías Digitales para la Innovación (UABC).

## Publicación
1. Crea un repositorio de GitHub.
2. Sube `index.html` y `vercel.json` a la raíz.
3. En Vercel elige **Add New → Project**, importa el repositorio, selecciona **Other** como framework y deja vacío el comando de build.
4. Haz clic en **Deploy**.

## Uso
Los proyectos se guardan automáticamente en localStorage del navegador. **No hay sincronización entre dispositivos**. Utiliza «Guardar proyecto» para exportar JSON y «Recuperar» para continuar en otro equipo. En Reporte técnico selecciona imprimir / guardar como PDF.

## Dependencias
React, ReactDOM y htm se cargan desde esm.sh; requiere conexión a internet. No se necesita npm ni proceso de compilación.

## Alcance
Las fuentes estadísticas se consultan mediante enlaces externos; no existe integración API ni datos precargados. Los diagramas son flujos secuenciales y no BPMN completo. No se recopilan datos en servidores de la aplicación.

## Editor visual de procesos
El módulo Diagnóstico de procesos incluye un editor React Flow con nodos arrastrables, conexiones y decisiones. Doble clic en un nodo para renombrarlo. Se guarda en el proyecto local y en la exportación JSON. El reporte incluye una representación SVG imprimible de los nodos y sus conexiones.