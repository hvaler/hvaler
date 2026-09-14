# Hugo Valer

**Español** · [English](https://github.com/hvaler/hvaler/blob/main/README.en.md)

**Arquitecto de software · IA agéntica gobernada · entornos on-prem y regulados**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hugo%20Valer-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hugovaler/)
[![Documentación de Ovillo](https://img.shields.io/badge/Ovillo-documentaci%C3%B3n-2E7D32?style=flat-square&logo=readthedocs&logoColor=white)](https://hvaler.github.io/ovillo-docs/)
[![Agenda 30 min](https://img.shields.io/badge/Agenda-30%20min-000000?style=flat-square&logo=caldotcom&logoColor=white)](https://cal.com/hugovaler/30min)

---

## A qué me dedico

Diseño, construyo y pongo en producción plataformas de desarrollo asistido por IA en entornos donde el código no puede salir de casa.

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

## Actualmente

- Diseñando plataformas de agentes con trazabilidad fuerte (ADR + hash de contenido).
- Endureciendo gates de calidad para que bloqueen riesgo real en CI.
- Productivizando MCP para equipos .NET en entornos con residencia del dato.

---

## Ovillo

[**Ovillo**](https://hvaler.github.io/ovillo-docs/) es mi propio ecosistema Claude Code para .NET, distribuido como plugin `hv@ovillo`. Lleva el modelo de gobernanza anterior a cualquier base de código .NET: asesores de solo lectura, comandos como única vía de escritura y una traza documentada de decisiones.

Portal de documentación: **hvaler.github.io/ovillo-docs**
---
## Presura

[**Presura**](https://presura.net/) is a CRM and quoting tool for renovation companies.
The AI drafts each quote from the company's own price book — their cost, their margin,
their wording for each line item — and the client signs from their phone. Multi-company,
multi-currency, six languages.

My own product, live. Source is private.
---

## Trabajo seleccionado

| Proyecto | Qué es |
|---|---|
| [**ArenaPay**](https://github.com/hvaler/ArenaPay) | Competiciones verificables sobre Stellar. El juego ocurre fuera de cadena; Soroban registra solo lo incontestable: escrow, hash del resultado y firma del árbitro. Contrato en Rust, web en React, backend en Cloudflare Workers. Evidencia contrastable en cadena. |
| [**ovillo-docs**](https://github.com/hvaler/ovillo-docs) | Portal de documentación de Ovillo, generado desde el código en cada versión. |
| [**stripboard-dev**](https://github.com/hvaler/stripboard-dev) | Productor de línea autónomo para rodajes. El LLM formula, CP-SAT decide, un humano aprueba. Gemini + Grafana MCP. |
| [**atelier**](https://github.com/hvaler/atelier) | Verificador de geometría descriptiva. OpenCV mide el dibujo; el modelo enseña y no puede inventarse un número. Python, Vertex AI. |
| [**cursus**](https://github.com/hvaler/cursus) | Planificador de itinerarios académicos cuyas herramientas pueden negarse, explicar qué cierra una decisión dos años antes de que duela, y rebobinar. Construido con WebMCP. |

Desarrollados en OpenAI Build Week, Agentic Cinema, All Things Agentic y Stellar Odyssey Perú (2026). Documentados en inglés cuando esa era la lengua de trabajo del hackathon.

---

## Stack

| Área | Tecnologías |
|---|---|
| Lenguajes | C# · Python · TypeScript · Rust |
| Frameworks | .NET · ASP.NET Core · Blazor |
| Web | React · Node · Cloudflare Workers |
| Datos | SQL Server · PostgreSQL |
| Plataforma | Azure · Docker · Azure DevOps Server |
| IA | Claude Code · MCP · orquestación y gobernanza de agentes |

Más de treinta años construyendo software; los últimos dedicados a que la IA agéntica funcione en producción y no solo en demos.

---

## Contacto

Madrid, España. Disponible para conversaciones sobre arquitectura .NET, MCP y despliegue de IA agéntica en organizaciones reguladas. También desarrollo aplicaciones de gestión a medida, de la toma de requisitos a la puesta en producción. Respondo en 48 h.

| | |
|---|---|
| Correo | [hugo@tudominio.com](mailto:hugo@tudominio.com) |
| LinkedIn | [linkedin.com/in/hugovaler](https://www.linkedin.com/in/hugovaler/) |
| Agenda 30 min | [cal.com/hugovaler/30min](https://cal.com/hugovaler/30min) |
| Ovillo | [Documentación](https://hvaler.github.io/ovillo-docs/) · [Discussions](https://github.com/hvaler/ovillo-docs/discussions) |
