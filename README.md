# Applied AI Engineering · карта чтения

**[Начать здесь · M42 · 10–15 минут](https://medium.com/@karthickrajam18/five-agents-talking-lost-to-five-answers-and-a-vote-d15690013740)**. После знакомства с оркестрацией прочитай *The trick hiding in most comparisons* и *One study shows the whole story*. Сначала сравни команду с одним ответом, затем с пятью независимыми ответами той же модели. Сверь также стоимость вызовов и задержку: одинаковое число ответов может обойтись командам по-разному. Следом — [M43: сравнение на tau-airline](https://medium.com/@duttasaswata7/structuring-multi-agent-systems-around-irreversible-actions-lessons-from-tau-bench-defe0f139eda).

[Коллекция Medium](https://medium.com/@jklooop/list/job-radar-llm-engineering-8-52ab9546e729) · [Каталог — 77 материалов](catalog.md) · [Прочитано](read.md) · [История отбора](selection.md)

```mermaid
flowchart TD
F["1 · Структура и факты"] --> E["2 · Как измерять качество"]
E --> R["3 · Поиск и знания"]
E --> T["4 · Контекст и инструменты"]
T --> A["5 · Цена оркестрации"]
A --> W["6 · Повтор и восстановление"]
R --> P["7 · Права и источники"]
W --> P
P --> O["8 · Трассы, стоимость, задержка"]
```

## Выбери путь

- **Frontend/Fullstack → Applied AI.** Начни с [M68](catalog.md#m68), затем [M06](catalog.md#m06) и [M07](catalog.md#m07). Если уже прочитаны обе статьи первого вечера, на неделе 5 открывай [M46](catalog.md#m46).
- **RAG, когда основы уже знакомы.** Диагностика измерения [M23](catalog.md#m23) → гибридный поиск [M20](catalog.md#m20) → градации релевантности [M21](catalog.md#m21). Для обновляемых документов прочитай [M25](catalog.md#m25) перед M17 и [M26](catalog.md#m26) после M23.
- **Агенты после вводной серии.** [Независимые попытки M42](https://medium.com/@karthickrajam18/five-agents-talking-lost-to-five-answers-and-a-vote-d15690013740) → [запись и согласование M43](https://medium.com/@duttasaswata7/structuring-multi-agent-systems-around-irreversible-actions-lessons-from-tau-bench-defe0f139eda) → [вклад компонентов M46](catalog.md#m46) → [одинаковая спецификация и разные расходы M44](https://medium.com/@jainashish.079/single-agent-vs-multi-agent-coding-a-controlled-experiment-with-real-metrics-b8c4027e410f). [Карта агентов](agents.md).
- **Evals и эксплуатация.** [Golden set и CI M10](https://medium.com/models-to-systems/part-14-evals-knowing-whether-scout-is-any-good-0155ff1d4723) → [диагностика сбоя диалога M15](https://medium.com/@marcus.chen_88321/the-call-failed-on-turn-nine-my-eval-gave-me-one-number-for-the-whole-call-04531df3a8bc) → [привязка к trace M56](https://medium.com/@khwajakhan/llm-observability-traces-tokens-and-cost-on-a-frozen-agentic-app-e0a3b9e2c790) → [M75](catalog.md#m75) → [M76](catalog.md#m76). Для своего inference — [нагрузка M57](https://medium.com/pinterest-engineering/building-pinterests-vlm-serving-stack-on-nvidia-dynamo-0dce6e93d0f3). [Карта evals](foundation.md) · [Карта эксплуатации](production.md).

## Основная линия на восемь недель

30 основных материалов, **10 ч 15 мин** при базовом выборе. Минуты включают выборочное чтение и разбор примеров. Из бюджета 2–3 часа в неделю оставь запас на сложные разборы. Каждый ID открывает карточку с оригинальной статьёй и указаниями по чтению.

| Неделя | Читать слева направо | Что даст чтение | По интересу или вместо основного текста | Минуты |
|---|---|---|---|---:|
| [1. Вывод модели](foundation.md)  | [M68](catalog.md#m68) → [M06](catalog.md#m06) → [M07](catalog.md#m07) | Выбрать простой baseline, проверить формат ответа и правильность метки. | [M67](catalog.md#m67) перед [M68](catalog.md#m68), если решаешь, хватит ли правил. | 60 |
| [2. Оценка качества](foundation.md)  | [M69](catalog.md#m69) → [M10](catalog.md#m10) → [M11](catalog.md#m11) → [M71](catalog.md#m71) → [M12](catalog.md#m12) | Выбрать независимую единицу наблюдения, проверить срезы и смещение судьи. | [M70](catalog.md#m70) для примера групповой утечки. [M13](catalog.md#m13) можно выбрать вместо [M12](catalog.md#m12). После [M12](catalog.md#m12) открой [M65](catalog.md#m65) для ручной калибровки или [M14](catalog.md#m14) для оценки повторяемости. | 110 |
| [3. Поиск и базы знаний](retrieval.md)  | [M72](catalog.md#m72) → [M25](catalog.md#m25) → [M17](catalog.md#m17) → [M18](catalog.md#m18) → [M20](catalog.md#m20) → [M23](catalog.md#m23) → [M26](catalog.md#m26) | Отследить документ от версии источника до выдачи и проверить исчезновение старого факта. | [M80](catalog.md#m80) после [M17](catalog.md#m17) для сравнения exact и ANN. При проблеме PDF после [M18](catalog.md#m18) читай [M74](catalog.md#m74) → [M73](catalog.md#m73). Если выход парсера проверен, достаточно [M73](catalog.md#m73). | 140 |
| [4. Контекст и инструменты](agents.md)  | [M32](catalog.md#m32) → [M34](catalog.md#m34) | Различить ошибку выбора инструмента, нарушение контракта и сбой протокола. | [M33](catalog.md#m33) при миграции SDK. [M36](catalog.md#m36) → [M38](catalog.md#m38) для длинной истории. | 57 |
| [5. Агент или команда](agents.md)  | [M42](catalog.md#m42) → [M43](catalog.md#m43) → [M46](catalog.md#m46) | Отделить вклад координации от бюджета попыток и проверить взаимодействие компонентов. | Если первым вечером прочитаны [M42](catalog.md#m42) и [M43](catalog.md#m43), начни с [M46](catalog.md#m46). Если только [M42](catalog.md#m42), продолжи с [M43](catalog.md#m43). [M44](catalog.md#m44) по интересу. | 63 |
| [6. Состояние и повторы](production.md)  | [M48](catalog.md#m48) → [M49](catalog.md#m49) → [M81](catalog.md#m81) → [M78](catalog.md#m78) → [M79](catalog.md#m79) | Различить повтор доставки, исполнение и бизнес-эффект. Показать пользователю подтверждённый статус при обрыве. | [M50](catalog.md#m50) для replay и выкладки новой версии длительного workflow. | 78 |
| [7. Полномочия](production.md)  | [M52](catalog.md#m52) → [M53](catalog.md#m53) | Проверить полномочия во время исполнения и видимость документа после отзыва доступа. | Вернись к [M26](catalog.md#m26) при отзыве источника. [M54](catalog.md#m54) для подтверждения действий. | 44 |
| [8. Эксплуатация](production.md)  | [M56](catalog.md#m56) → [M75](catalog.md#m75) → [M76](catalog.md#m76) | Связать трассу с качеством, затратами и задержкой. Определить условия паузы и отката. | После [M76](catalog.md#m76) выбери [M30](catalog.md#m30) для ранжирования или [M77](catalog.md#m77) для анализа правил выпуска. [M58](catalog.md#m58) → [M57](catalog.md#m57) для собственного inference. | 63 |

**Как читать метки.** «Основная» ведёт к следующему шагу, «альтернатива» заменяет указанный ID, «углубление» продолжает тему, «справочно» пригодится под конкретный вопрос. Способ чтения указан отдельно: целиком, выборочно по заголовкам или бегло по таблице или примеру.

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
