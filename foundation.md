# Основы и evals

[Обзорная карта](README.md) · [Подробные карточки](catalog.md)

```mermaid
flowchart TD
P["M67 или M68 · Baseline"] --> A
A["M06 · Схема"] --> B["M07 · Фактическая точность"]
B --> C["M10 · Evals"]
C --> S["M69 или M70 · Разбиение"] --> X["M11 · Регрессии по срезам"]
X --> H["M71 · Срезы"] --> D["M12 · Подсказка судье"]
H --> E["M13 · Позиция аргумента"]
D --> F["M17 · Поиск"]
E --> F
```

## Неделя 1. Вывод модели

**Порядок:** [M67](catalog.md#m67) → [M06](catalog.md#m06) → [M07](catalog.md#m07). Выбрать эвристику или классификатор для сравнения с LLM, затем отдельно проверить схему ответа и правильность значений. Medium-вариант [M67](catalog.md#m67) — [M68](catalog.md#m68).

- [M67](catalog.md#m67) · Основа · 10 мин. [Rules of Machine Learning](https://developers.google.com/machine-learning/guides/rules-of-ml). Правила 1–4. Выбери простую эвристику и показатель, по которому усложнение оправдает себя. Это метод выбора baseline. Для численного примера на Medium выбери M68.
- [M68](catalog.md#m68) · Альтернатива · 15 мин. [Why Using GPT May Not Be the Best Option for Customer Feedback Classification](https://medium.com/picnic-engineering/why-using-gpt-may-not-be-the-best-option-for-customer-feedback-classification-12e9c36cd4a7). Вместо M67 или следом для конкретного примера. Picnic сравнивает TF-IDF, DistilBERT и дообученный GPT-3 на маршрутизации отзывов. Двухдневный эксперимент 2023 года показывает дизайн сравнения. Рейтинг современных моделей требует новых измерений. [Версия команды](https://jobs.picnic.app/en/blogs/why-using-gpt-may-not-be-the-best-option-for-customer-feedback-classification).

- **[M06](catalog.md#m06) · Основная · 15 мин.** [Structured output in small models: I measured it, the measurement was broken, I measured again](https://medium.com/@yusufbender/structured-output-in-small-models-i-measured-it-the-measurement-was-broken-i-measured-again-14a4f5f27e35). Читать: What was the measurement actually measuring? → Second measurement: a strict schema.
- **[M07](catalog.md#m07) · Основная · 30 мин.** [Framing beats masking: what actually moves LLM accuracy on structured outputs](https://medium.com/@mehdi.nemlaghi/framing-beats-masking-what-actually-moves-llm-accuracy-on-structured-outputs-46108dbaee1b). Классификация одних и тех же примеров через свободный ответ, принудительную схему и tool calling разделяет эффект формата и постановки задачи.
- **[M08](catalog.md#m08) · Углубление · 12 мин.** [Your Reasoning Model Spent the Token Budget Thinking. The JSON Never Came](https://medium.com/@anhaia.gabriel/your-reasoning-model-spent-the-token-budget-thinking-the-json-never-came-9f31aead28c2). Читать: Read the envelope first.
- **[M09](catalog.md#m09) · Справочно · 12 мин.** [Token efficiency with structured output from language models](https://medium.com/data-science-at-microsoft/token-efficiency-with-structured-output-from-language-models-be2e51d3d9d5). Читать: Function calling efficiency.

## Неделя 2. Оценка качества

**Порядок:** [M10](catalog.md#m10) → [M69](catalog.md#m69) → [M11](catalog.md#m11) → [M71](catalog.md#m71) → [M12](catalog.md#m12). Выбрать независимую единицу проверки, увидеть провал редкого сегмента и проверить, заслуживает ли доверия оценщик. [M70](catalog.md#m70) заменяет [M69](catalog.md#m69) для группового разбиения. Для судьи выбери [M12](catalog.md#m12) или [M13](catalog.md#m13).

- [M69](catalog.md#m69) · Основа · 15 мин. [Cross-validation: evaluating estimator performance](https://scikit-learn.org/stable/modules/cross_validation.html). После M10. Прочитай подразделы про GroupKFold и TimeSeriesSplit. Выбери единицу проверки по тому, что встретится после релиза: новый документ, клиент или будущий период. Если нужны и новые группы, и будущие даты, проверь оба ограничения отдельно. Альтернатива на Medium — M70.
- [M70](catalog.md#m70) · Альтернатива · 10 мин. [Your Cross-Validation Score Is a Lie, and Here Are the Five Reasons Why](https://medium.com/data-and-beyond/your-cross-validation-score-is-a-lie-and-here-are-the-five-reasons-why-b464239338d6). Вместо M69 для начала с примера. В разделе Leak 2 автор сравнивает случайное и групповое разбиение повторных наблюдений. Синтетические идентификаторы показывают механизм утечки. За временным разбиением вернись к M69.
- [M71](catalog.md#m71) · Основа · 15 мин. [Heterogeneous Treatment Effects at Netflix](https://netflixtechblog.medium.com/heterogeneous-treatment-effects-at-netflix-da5c3dd58833). После M11. Discovery и Deciding Experiments. Разбери, почему число просмотренных сегментов меняет интерпретацию выброса. Масштаб онлайн-тестов Netflix ограничивает перенос на малый eval.

- **[M10](catalog.md#m10) · Основная · 48 мин.** [Part 14: Evals — Knowing Whether Scout Is Any Good](https://medium.com/models-to-systems/part-14-evals-knowing-whether-scout-is-any-good-0155ff1d4723). Сценарии с устаревшими фактами, отсутствующим ответом и плохими цитатами выявляют регрессии, которые скрывает среднее. Отдельный тест проверяет сам оценщик.
- **[M11](catalog.md#m11) · Основная · 7 мин.** [A 91% eval pass rate shipped our worst regression. We gate on the delta now.](https://medium.com/@ethan-writes-AI/a-91-eval-pass-rate-shipped-our-worst-regression-we-gate-on-the-delta-now-ef52d6613f6f). Общий pass rate прошёл порог, хотя конкретные типы запросов сломались. Сравни изменения на тех же примерах.
- **[M12](catalog.md#m12) · Основная · 25 мин.** [LLMs as Judges: Measuring Bias, Hinting Effects, and Tier Preferences](https://medium.com/google-developer-experts/llms-as-judges-measuring-bias-hinting-effects-and-tier-preferences-8096a9114433). Читать: Problem Setup → Experiment 3 : Hinting Effect.
- **[M13](catalog.md#m13) · Альтернатива M12 · 20 мин.** [Who Wins — Opening Arguments or Closing Statements? An LLM Judge’s Position Bias](https://medium.com/ai4q/who-wins-opening-arguments-or-closing-statements-an-llm-judges-position-bias-38ab7b313d63). Читать: Бегло: таблицы результатов для двух положений аргумента.
- **[M14](catalog.md#m14) · Углубление · 15 мин.** [Can LLMs Be Trusted as Annotation Judges? A Look into Document Relevance and Consistency](https://medium.com/ordina-data/can-llms-be-trusted-as-annotation-judges-a-look-into-document-relevance-and-consistency-2877975193a9). Читать: Calculating agreement → Results.
- **[M15](catalog.md#m15) · Углубление · 18 мин.** [The call failed on turn nine. My eval gave me one number for the whole call.](https://medium.com/@marcus.chen_88321/the-call-failed-on-turn-nine-my-eval-gave-me-one-number-for-the-whole-call-04531df3a8bc). Читать: The trick: score the prefixes, not the call.
- **[M16](catalog.md#m16) · Справочно · 12 мин.** [AI Skills Need CI/CD Too](https://medium.com/@aradsouza/ai-skills-need-ci-cd-too-c06be3b2c4c9). Читать: Why Compare Against a Baseline Agent?.

Следующая ветка — [Поиск и базы знаний](retrieval.md).

- **[M65](catalog.md#m65) · Углубление · 7 мин.** [An LLM judge is a biased instrument, not a measurement](https://medium.com/@maya.andersson/an-llm-judge-is-a-biased-instrument-not-a-measurement-42f0ca7d304f). Сверь оценки судьи с ручной разметкой и поменяй местами ответы в каждой паре.
