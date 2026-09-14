# Hugo Valer

**Arquitecto de software · IA agéntica gobernada para entornos on-premise y regulados**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hugo%20Valer-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hugovaler/)
[![Documentación de Ovillo](https://img.shields.io/badge/Ovillo-documentaci%C3%B3n-2E7D32?style=flat-square&logo=readthedocs&logoColor=white)](https://hvaler.github.io/ovillo-docs/)

---

## A qué me dedico

Diseño y sostengo plataformas de desarrollo asistido por IA en organizaciones donde el código no puede salir de casa.

En la Universidad Pontificia Comillas soy el arquitecto principal del ecosistema de IA de desarrollo: agentes que se ejecutan on-premise sobre Azure DevOps Server, con un modelo de gobernanza estricto. Los asesores son de solo lectura, los comandos son la única vía de escritura y cada decisión queda sellada como ADR con hash de contenido. No es asistencia al programador: es una plataforma con invariantes.

- **Gobernanza de agentes.** Tríada comando / skill / agente, sellado por hash de contenido, decisiones respaldadas por ADR.
- **On-premise por requisito.** Azure DevOps Server 2020, sin que el código salga del perímetro.
- **MCP.** Servidores hub que centralizan registros de arquitectura y evidencias de calidad.
- **Calidad medida.** Gates que rompen la build, no cuadros de mando decorativos.

---

## Pruebas, no adjetivos

Última campaña de remediación de calidad sobre el código de la plataforma:

| Métrica | Antes | Después |
|---|---|---|
| CRAPmax | 272 | 26 |
| Cobertura de línea | 61,4 % | 87,9 % |
| Cobertura de rama | 65,8 % | 91,7 % |
| Gate de calidad | FAIL | PASS |

---

## Ovillo

[**Ovillo**](https://hvaler.github.io/ovillo-docs/) es mi propio ecosistema Claude Code para .NET, distribuido como plugin `hv@ovillo`. Lleva el modelo de gobernanza anterior a cualquier base de código .NET: asesores de solo lectura, comandos como única vía de escritura y una traza documentada de decisiones.

Portal de documentación: **hvaler.github.io/ovillo-docs**

---

## Trabajo seleccionado

| Proyecto | Qué es |
|---|---|
| [**ovillo-docs**](https://github.com/hvaler/ovillo-docs) | Portal de documentación de Ovillo, generado desde el código en cada versión. |
| [**stripboard-dev**](https://github.com/hvaler/stripboard-dev) | Productor de línea autónomo para rodajes. El LLM formula, CP-SAT decide, un humano aprueba. Gemini + Grafana MCP. |
| [**atelier**](https://github.com/hvaler/atelier) | Verificador de geometría descriptiva. OpenCV mide el dibujo; el modelo enseña y no puede inventarse un número. Python, Vertex AI. |
| [**cursus**](https://github.com/hvaler/cursus) | Planificador de itinerarios académicos cuyas herramientas pueden negarse, explicar qué cierra una decisión dos años antes de que duela, y rebobinar. Construido con WebMCP. |

Desarrollados en OpenAI Build Week, Agentic Cinema y All Things Agentic (2026).

---

## Stack

**Lenguajes** C# · Python · Rust
**Frameworks** .NET · ASP.NET Core · Blazor
**Datos** SQL Server · PostgreSQL
**Plataforma** Azure · Docker · Azure DevOps Server
**IA** Claude Code · MCP · orquestación y gobernanza de agentes

Treinta años construyendo software; los últimos dedicados a que la IA agéntica funcione en producción y no solo en demos.

---

## Contacto

Madrid, España. Abierto a conversaciones sobre arquitectura .NET, MCP y adopción de IA en organizaciones con restricciones de residencia del dato.

[LinkedIn](https://www.linkedin.com/in/hugovaler/) · [Ovillo](https://hvaler.github.io/ovillo-docs/)
