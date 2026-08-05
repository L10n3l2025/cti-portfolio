# 🔍 Metodología de análisis

Este documento describe el framework que aplico en cada análisis de amenazas publicado en este repositorio.

## Framework general

1. **Recolección** — identificación de la amenaza/campaña a partir de fuentes OSINT, CERT/CSIRT, y comunidad (ver [recursos](./resources.md)).
2. **Diamond Model** — caracterización de la amenaza en sus 4 ejes: Adversario, Infraestructura, Capacidad, Víctima.
3. **Mapeo MITRE ATT&CK** — identificación de tácticas y técnicas observadas o reportadas, con matriz de cobertura.
4. **Kill Chain narrativo** — reconstrucción de la secuencia de ataque de forma descriptiva.
5. **Reglas de detección (Sigma)** — cuando aplique, generación de reglas Sigma basadas en los IOCs/TTPs identificados.
6. **Reporte final** — documento consolidado en Markdown, con diagramas de apoyo (SVG) cuando sea necesario.

## Por qué este enfoque

Este framework combina estándares reconocidos en la industria (Diamond Model, MITRE ATT&CK, Sigma) para asegurar que cada análisis sea:
- Comparable con reportes de la industria (Mandiant, CronUp, Group-IB, The DFIR Report)
- Accionable (las reglas Sigma permiten detección práctica)
- Reproducible (metodología consistente entre análisis)

## Estado actual

Este repositorio está en construcción activa. Los primeros análisis siguiendo esta metodología se irán publicando progresivamente conforme avance en mi formación en CTI.
