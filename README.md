# Applied AI Engineering · маршрут чтения

Восемь недель для разработчика на React, TypeScript и NestJS. Цель — научиться выбирать архитектуру LLM-приложения и объяснять её качество, стоимость и ограничения. Первый этап состоит из статей Medium. Ниже — порядок тем и стартовые ссылки для редакторского отбора.

## Порядок чтения

| Неделя | Тема | Вопрос для чтения |
| --- | --- | --- |
| 1 | LLM и Structured Outputs | Как обнаружить ошибку в ответе, который прошёл проверку схемы? |
| 2 | Evals | Какие примеры отличают удачное изменение промпта от случайного выигрыша? |
| 3 | RAG и базы знаний | Как отделить ошибку поиска от ошибки генерации? |
| 4 | Инструменты, контекст и MCP | Какие данные получает модель и кто исполняет выбранное действие? |
| 5 | Агентный цикл и оркестрация | Когда второй агент оправдывает затраты по сравнению с одним? |
| 6 | Интеграция в бизнес-процесс | Что произойдёт при повторе операции после частичного сбоя? |
| 7 | Права и надёжность | Кто проверяет полномочия перед внешним действием? |
| 8 | Эксплуатация | Сколько стоит один успешно завершённый сценарий с учётом повторов? |

## Каталог Medium

Идентификаторы M01–M05 постоянные. Это исходные ссылки из обсуждения. Место в обязательной программе и оценка определяются после проверки полного текста. Цель итогового отбора — 30–40 уникальных статей.

| ID | Публикация или коллекция | Что проверить при отборе |
| --- | --- | --- |
| M01 | [Agentic Architecture & Orchestration Ground Up · David Oluyale, части 1–7](https://medium.com/@oluyaled/list/agentic-architecture-orchestration-ground-up-part-17-55a17c4bd71d) | Какие части можно читать отдельно? В каталоге пока одна ссылка на коллекцию. |
| M02 | [AI System Design: A Practical Guide to Production AI](https://medium.com/@piyushkashyap045/ai-system-design-a-practical-guide-to-production-ai-4ce5e473a1b7) | Какие решения автор обосновывает эксплуатационными данными? |
| M03 | [Agent Harness: A No-BS Guide](https://levelup.gitconnected.com/agent-harness-a-no-bs-guide-8f69e3c0a3da) | Как распределена ответственность между моделью и средой исполнения? |
| M04 | [Building Self-Improving AI Applications with Harness²](https://medium.com/@danushidk507/building-self-improving-ai-applications-with-harness²-from-agent-execution-to-recursive-harness-9657306a8086) | С чем сравнивали результат и как обнаруживали регрессии? |
| M05 | [I Tried Building With WebMCP Before Gemini in Chrome Could Even Call It](https://topuzas.medium.com/i-tried-building-with-webmcp-before-gemini-in-chrome-could-even-call-it-16b0d93f42f1) | Дополнение к неделе 4 из подборки PiterJS. Когда результат инструмента согласован с состоянием интерфейса? |

## Дополнительные материалы

Справочные ссылки из исходного плана. К ним удобно возвращаться при чтении статей.

| Тема | Материал |
| --- | --- |
| Структурированные ответы | [OpenAI · Structured Outputs](https://platform.openai.com/docs/guides/structured-outputs) |
| Оценка качества | [Hamel Husain · AI Evals FAQ](https://hamel.dev/blog/posts/evals-faq/) |
| Выбор между workflow и агентом | [Anthropic · Building effective agents](https://www.anthropic.com/engineering/building-effective-agents) |
| Контракты инструментов | [Anthropic · Writing effective tools for AI agents](https://www.anthropic.com/engineering/writing-tools-for-agents) |
| MCP на TypeScript | [Model Context Protocol · TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) |
| Наблюдаемость | [OpenTelemetry · GenAI semantic conventions](https://opentelemetry.io/docs/specs/semconv/gen-ai/) |

Бесплатные курсы — следующий этап. Темы для них определятся после чтения основной подборки.
