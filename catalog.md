# Каталог статей

ID сохраняется между редакциями. Оценки редакторские по пяти критериям: глубина 30%, опыт 25%, оригинальность 20%, доказательства 15%, плотность 10%. Минуты рассчитаны на указанное чтение с разбором примеров. Ранее отобранные платные статьи проверялись в авторизованной сессии. Для M67–M88 отсутствующие метаданные и оценки не выдумываются; новые открытые учебные источники проверены по указанным разделам, не по всей публикации. Цифры экспериментов принадлежат авторам.

### M06

[Structured output in small models: I measured it, the measurement was broken, I measured again](https://medium.com/@yusufbender/structured-output-in-small-models-i-measured-it-the-measurement-was-broken-i-measured-again-14a4f5f27e35)

Yusuf Bender · Medium · Aug 9, 2026 · открытый текст · **8.9/10**

> M06 · Неделя 1 · Основная · Выборочно, 15 мин. What was the measurement actually measuring? → Second measurement: a strict schema.

Пустой объект проходил первую схему. На строгой схеме обе группы дали валидный JSON, но пригодными оказались 64% и 100% ответов. Одна локальная 7B-модель, по 25 прогонов. Совпадение цитаты не измеряет значимость вывода.

### M07

[Framing beats masking: what actually moves LLM accuracy on structured outputs](https://medium.com/@mehdi.nemlaghi/framing-beats-masking-what-actually-moves-llm-accuracy-on-structured-outputs-46108dbaee1b)

Mehdi Nemlaghi · Medium · May 13, 2026 · открытый текст · **9.1/10**

> M07 · Неделя 1 · Основная · Целиком, 30 мин. Классификация одних и тех же примеров через свободный ответ, принудительную схему и tool calling разделяет эффект формата и постановки задачи.

Классификация одних и тех же примеров через свободный ответ, принудительную схему и tool calling разделяет эффект формата и постановки задачи. Результат зависит от модели и простой схемы метки; перенос на сложные вложенные объекты требует нового теста.

### M08

[Your Reasoning Model Spent the Token Budget Thinking. The JSON Never Came](https://medium.com/@anhaia.gabriel/your-reasoning-model-spent-the-token-budget-thinking-the-json-never-came-9f31aead28c2)

Gabriel Anhaia · Medium · Oct 19, 2026 · открытый текст · **8.2/10**

> M08 · Неделя 1 · Углубление · Выборочно, 12 мин. Read the envelope first.

Разбери оболочку ответа в TypeScript: приложение должно различать отказ, исчерпанный бюджет и успешную генерацию перед разбором JSON. Поведение API и структура статусов зависят от провайдера.

### M09

[Token efficiency with structured output from language models](https://medium.com/data-science-at-microsoft/token-efficiency-with-structured-output-from-language-models-be2e51d3d9d5)

Bwilliams · data-science-at-microsoft · Jul 30, 2024 · открытый текст · **8.4/10**

> M09 · Неделя 1 · Справочно · Выборочно, 12 мин. Function calling efficiency.

На примере заказа еды сопоставь токены полезных значений и повторяемых элементов структуры. Старые модели и цены; используй способ подсчёта.

### M10

[Part 14: Evals — Knowing Whether Scout Is Any Good](https://medium.com/models-to-systems/part-14-evals-knowing-whether-scout-is-any-good-0155ff1d4723)

Deepak Mishra · models-to-systems · Nov 11, 2026 · Member-only · **9.0/10**

> M10 · Неделя 2 · Основная · Целиком, 48 мин. Сценарии с устаревшими фактами, отсутствующим ответом и плохими цитатами выявляют регрессии, которые скрывает среднее. Отдельный тест проверяет сам оценщик.

Сценарии с устаревшими фактами, отсутствующим ответом и плохими цитатами выявляют регрессии, которые скрывает среднее. Отдельный тест проверяет сам оценщик. Показательные цены агентов в примере заданы автором; на 13 случаях интервал широк.

### M11

[A 91% eval pass rate shipped our worst regression. We gate on the delta now.](https://medium.com/@ethan-writes-AI/a-91-eval-pass-rate-shipped-our-worst-regression-we-gate-on-the-delta-now-ef52d6613f6f)

Ethan Walker · Medium · Jun 22, 2026 · открытый текст · **8.0/10**

> M11 · Неделя 2 · Основная · Целиком, 7 мин. Общий pass rate прошёл порог, хотя конкретные типы запросов сломались. Сравни изменения на тех же примерах.

Общий pass rate прошёл порог, хотя конкретные типы запросов сломались. Сравни изменения на тех же примерах. Один отчёт команды без опубликованной выборки.

### M12

[LLMs as Judges: Measuring Bias, Hinting Effects, and Tier Preferences](https://medium.com/google-developer-experts/llms-as-judges-measuring-bias-hinting-effects-and-tier-preferences-8096a9114433)

Aashi Dutt · google-developer-experts · Jan 1, 2026 · открытый текст · **8.6/10**

> M12 · Неделя 2 · Основная · Выборочно, 25 мин. Problem Setup → Experiment 3 : Hinting Effect.

Проверь, меняется ли предпочтение судьи при подсказке о происхождении ответа. Есть код экспериментов. Предпочтение одной модели не равно экспертной оценке качества.

### M13

[Who Wins — Opening Arguments or Closing Statements? An LLM Judge’s Position Bias](https://medium.com/ai4q/who-wins-opening-arguments-or-closing-statements-an-llm-judges-position-bias-38ab7b313d63)

Ora Nova Fandina · ai4q · Jun 27, 2025 · открытый текст · **8.5/10**

> M13 · Неделя 2 · Альтернатива M12 · Бегло, 20 мин. таблицы результатов для двух положений аргумента.

Выбери вместо опыта с подсказками, если интересует порядок контекста: один и тот же материал COBOL перемещают относительно инструкции. Узкая предметная область; результаты нельзя считать поправочным коэффициентом для других задач.

### M14

[Can LLMs Be Trusted as Annotation Judges? A Look into Document Relevance and Consistency](https://medium.com/ordina-data/can-llms-be-trusted-as-annotation-judges-a-look-into-document-relevance-and-consistency-2877975193a9)

Janneke van der Zwaan · ordina-data · Apr 25, 2025 · открытый текст · **8.5/10**

> M14 · Неделя 2 · Углубление · Выборочно, 15 мин. Calculating agreement → Results.

Пять повторов и Fleiss’ kappa позволяют измерить согласованность судьи при оценке релевантности. Один исходный вопрос; согласованность не устанавливает правильность.

### M15

[The call failed on turn nine. My eval gave me one number for the whole call.](https://medium.com/@marcus.chen_88321/the-call-failed-on-turn-nine-my-eval-gave-me-one-number-for-the-whole-call-04531df3a8bc)

Marcus Chen · Medium · Aug 20, 2026 · открытый текст · **8.2/10**

> M15 · Неделя 2 · Углубление · Выборочно, 18 мин. The trick: score the prefixes, not the call.

Оценка префиксов диалога помогает локализовать первый резкий провал между ходами. Порог изменения пропускает медленную деградацию.

### M16

[AI Skills Need CI/CD Too](https://medium.com/@aradsouza/ai-skills-need-ci-cd-too-c06be3b2c4c9)

Alwyn DSouza · Medium · Jun 6, 2026 · Member-only · **8.1/10**

> M16 · Неделя 2 · Справочно · Выборочно, 12 мин. Why Compare Against a Baseline Agent?.

Открывай при работе с coding-агентами: сравни одного агента со skill и без него на одинаковых задачах. Один навык генерации user stories; бизнес-ценность требует своей оценки.

### M17

[Building RAG from the Corpus Up, Not the Model Down](https://medium.com/@rf26/building-rag-from-the-corpus-up-not-the-model-down-ac7271325cba)

RF · Medium · Aug 27, 2026 · открытый текст · **8.7/10**

> M17 · Неделя 3 · Основная · Целиком, 32 мин. Сопоставь BM25, dense и RRF. Обрезание входа энкодером изменило состав индекса ещё до этапа ранжирования.

Сопоставь BM25, dense и RRF. Обрезание входа энкодером изменило состав индекса ещё до этапа ранжирования. Вопросы из самих документов благоприятны для лексического поиска.

### M18

[Which RAG chunking advice survives error bars? Six rules from a held-out test](https://medium.com/@vaishnavi.sonawane.writes/which-rag-chunking-advice-survives-error-bars-six-rules-from-a-held-out-test-82b3ce2c0dfe)

Vaishnavi Sonawane Writes · Medium · Oct 29, 2026 · открытый текст · **8.9/10**

> M18 · Неделя 3 · Основная · Целиком, 18 мин. Автор разделяет настройку и отложенную проверку. Для промахов различает чужой документ и неподходящий фрагмент правильного документа.

Автор разделяет настройку и отложенную проверку. Для промахов различает чужой документ и неподходящий фрагмент правильного документа. Один корпус Pro Git; выбранный overlap нельзя считать универсальным.

### M19

[There’s no Winning Chunking Strategy, Just a Corpus You Haven’t Measured](https://paradigma-digital.medium.com/theres-no-winning-chunking-strategy-just-a-corpus-you-haven-t-measured-a44512467ce2)

Paradigma Digital · Medium · Oct 29, 2026 · открытый текст · **8.1/10**

> M19 · Неделя 3 · Углубление · Выборочно, 18 мин. Fixed windows: a surprisingly robust strategy.

Выбери для наглядного сравнения границ фрагментов одной страницы. Сопоставь фиксированное окно с тремя другими стратегиями. Демонстрация на одном документе; M18 сильнее как эмпирическое основание.

### M20

[I Added Hybrid Search to My Retrieval Pipeline. It Made Things Worse.](https://medium.com/@aashiesh.siwach/i-added-hybrid-search-to-my-retrieval-pipeline-heres-why-it-backfired-5904a267fb95)

Aashiesh Siwach · Medium · May 3, 2026 · открытый текст · **8.7/10**

> M20 · Неделя 3 · Основная · Целиком, 20 мин. На подмножестве MS MARCO добавление BM25 к dense понизило MAP@5; последующий reranker изменил вывод. Проследи вклад каждого этапа.

На подмножестве MS MARCO добавление BM25 к dense понизило MAP@5; последующий reranker изменил вывод. Проследи вклад каждого этапа. Разреженная разметка и другая метрика дают иную картину; генерация ответа не оценивалась.

### M21

[Pragmatic IR Benchmark on WANDS: From TF-IDF to Hybrid Retrieval and Cross-Encoder Reranking](https://medium.com/@tiagobachiegadealmeida/pragmatic-ir-benchmark-on-wands-from-tf-idf-to-hybrid-retrieval-and-cross-encoder-reranking-28d307185e71)

Tiago Bachiega de Almeida · Medium · Apr 17, 2026 · открытый текст · **8.9/10**

> M21 · Неделя 3 · Углубление · Выборочно, 24 мин. Limitations and next tests; таблица MAP@10 и NDCG@10.

На WANDS частично подходящий товар ценен. Переранжирование улучшило graded nDCG, расширение запроса синонимами добавило время. Результат по ранжированию товаров не измеряет фактичность ответа.

### M22

[RAG evaluation with Ragas](https://medium.com/data-science-lab-amsterdam/rag-evaluation-with-ragas-3a0cd1e34909)

Timwinter · data-science-lab-amsterdam · Nov 8, 2024 · открытый текст · **8.3/10**

> M22 · Неделя 3 · Углубление · Выборочно, 20 мин. Evaluating the RAG model → Key findings.

Сравни похожий на эталон ответ со слабой опорой на извлечённые данные: correctness и faithfulness отвечают на разные вопросы. Синтетические вопросы и автоматические оценки требуют проверки человеком.

### M23

[Evaluation-first RAG: what happened when my own metrics lied to me](https://medium.com/@ing.fernandosanabria/evaluation-first-rag-what-happened-when-my-own-metrics-lied-to-me-6810744f88ec)

Fernando Sanabria · Medium · Jul 14, 2026 · открытый текст · **8.9/10**

> M23 · Неделя 3 · Основная · Выборочно, 25 мин. Read-only rank probes → When the measurement apparatus lied.

Автор нашёл случаи с максимальным context recall при отсутствующем ответном фрагменте. Проверка ранга источника изменила диагноз. Предметная выборка мала; небольшие дельты оценщика ненадёжны.

### M24

[Lessons From Building a RAG System That Admits When It Doesn’t Know](https://medium.com/@anirudhece2020/lessons-from-building-a-rag-system-that-admits-when-it-doesnt-know-71930a117c2b)

Anirudh · Medium · ноябрь 2026 · открытый текст · **8.4/10**

> M24 · Неделя 3 · Углубление · Выборочно, 22 мин. Decisions, costs, and when I would revisit them.

Команда сохранила отказ от ответа как осмысленный результат. Сопоставь задержку и результат vector-only и hybrid с reranking. 39 кейсов; отсутствие выигрыша в этой выборке не исключает его на другой.

### M25

[Building the Ingestion Pipeline for a RAG System](https://medium.com/@mrcrdg/building-the-ingestion-pipeline-for-a-rag-system-c0f7fc0a3859)

Marcia Rodrigues · Medium · Nov 17, 2026 · открытый текст · **8.3/10**

> M25 · Неделя 3 · Основная · Выборочно, 18 мин. Incremental loads and idempotency → Comparing the two versions.

Страница и её версия определяют ключ сырого объекта. Повтор загрузки и перестройка downstream-индекса становятся разными операциями. Сравнение касается ingestion; качество ответов после индексации не измерено.

### M26

[How to Detect RAG Index Drift: Deleted Docs, Stale Chunks, and Duplicate Embeddings](https://medium.com/oracledevs/how-to-detect-rag-index-drift-deleted-docs-stale-chunks-and-duplicate-embeddings-5b5a21cc9244)

Anya Summers · oracledevs · Jul 29, 2026 · открытый текст · **8.2/10**

> M26 · Неделя 7 · Основная · Выборочно, 12 мин. Which regression test catches the most important failure?.

После удаления или замены документа проверь выдачу top-k по старому факту. Успех фоновой задачи не доказывает актуальность поиска. Разбор с примерами Oracle; понадобится своё отображение версий и удаления.

Если документ отозван у конкретного пользователя, продолжи в M53.

После M23 продолжи на неделе 7. Семантический кеш — [M66](#m66); обновление индекса само по себе не инвалидирует ответ. Проверяй версию источника, область доступа и политику кеша.


### M27

[Evolving Pinterest’s Embedding Retrieval Platform](https://medium.com/pinterest-engineering/evolving-pinterests-embedding-retrieval-platform-aede4e831e01)

Pinterest Engineering · pinterest-engineering · Sep 11, 2026 · открытый текст · **9.0/10**

> M27 · Неделя 3 · Углубление · Выборочно, 25 мин. Quantization: Redefining the Footprint of High-Recall Search.

Pinterest сравнивает компрессию онлайн и офлайн, затем переносит часть поиска с RAM на SSD. Экономию оценивают вместе с вовлечённостью. Масштаб платформы и распределение запросов существенно влияют на отдачу.

### M28

[Embedding-based retrieval for Airbnb search](https://medium.com/airbnb-engineering/embedding-based-retrieval-for-airbnb-search-aabebfc85839)

Huiji Gao · airbnb-engineering · Mar 19, 2025 · открытый текст · **8.8/10**

> M28 · Неделя 3 · Углубление · Выборочно, 22 мин. Training data construction → Online serving.

Airbnb меняет построение кандидатов через контекст запроса; обрати внимание на отбор обучающих пар и ограничения выдачи. Аренда жилья имеет свои ограничения доступности и цели ранжирования.

### M29

[Hybrid Search: Building a textual and visual discovery experience at Pinterest](https://medium.com/pinterest-engineering/hybrid-search-building-a-textual-and-visual-discovery-experience-at-pinterest-8527ba9728a9)

Pinterest Engineering · pinterest-engineering · May 6, 2019 · открытый текст · **8.1/10**

> M29 · Неделя 3 · Справочно · Бегло, 12 мин. пример уточнения поиска изображением и сравнение вовлечённости.

Посмотри, что меняется при соединении текстового намерения и визуального сигнала. Это мультимодальный продуктовый поиск; термин hybrid здесь имеет другой смысл, чем BM25+dense.

### M30

[Beyond A/B Test : Speeding up Airbnb Search Ranking Experimentation through Interleaving](https://medium.com/airbnb-engineering/beyond-a-b-test-speeding-up-airbnb-search-ranking-experimentation-through-interleaving-7087afa09c8e)

Qing Zhang · airbnb-engineering · Oct 6, 2022 · открытый текст · **9.0/10**

> M30 · Неделя 8 · После M76 · Углубление · Выборочно, 22 мин. Team Drafting and Competitive Pairs → Alignment with A/B tests.

Interleaving даёт сравнить ранжирования в одном показе. Airbnb проверила, когда вывод согласуется с обычным A/B-тестом. Клики и бронирования различаются; показатель совпадения относится к экспериментам Airbnb.

### M31

[Beyond Traditional Vector DBs: An Empirical Benchmark of In-Warehouse using native Google BigQuery, Local CPU, and Just-In-Time RAG methods](https://medium.com/google-cloud/beyond-traditional-vector-dbs-an-empirical-benchmark-of-in-warehouse-local-cpu-and-just-in-time-e9d14ed5a64a)

Ruban Siva · google-cloud · Sep 20, 2026 · открытый текст · **8.2/10**

> M31 · Неделя 3 · Справочно · Выборочно, 15 мин. The Break-Even Analysis: Economic Crossover Points.

Сопоставь цену подготовки корпуса с ценой запроса к длинному контексту. Частота переиспользования документа меняет выбор. Облачные цены и 25 контрольных случаев ограничивают переносимость порога.

### M32

[LLM System Design Series: 2/12 [Context, Contracts, and Environments]](https://medium.com/models-to-systems/llm-system-design-part-2-context-contracts-and-environments-17c546b123b3)

Deepak Mishra · models-to-systems · Oct 22, 2026 · Member-only · **8.6/10**

> M32 · Неделя 4 · Основная · Выборочно, 35 мин. The problem: three failures a better prompt will not fix → Idea 2: three contracts around every model call.

Разведи ошибки входного контекста, выбора инструмента и среды исполнения. Сравни описания инструментов. Эмуляция выбора через JSON отличается от нативного tool calling.

### M33

[I Built an Agent Loop by Hand. Then I Tried to Migrate It to the OpenAI Agents SDK](https://medium.com/@JohnMandos/i-built-an-agent-loop-by-hand-then-i-tried-to-migrate-it-to-the-openai-agents-sdk-47409209f1e1)

John · Medium · Oct 23, 2026 · открытый текст · **8.7/10**

> M33 · Неделя 4 · Справочно · Целиком, 24 мин. Один набор проверок сопровождает перенос ручного цикла в SDK. Отследи, какие ошибки получает сама модель, а какие завершают вызов исключением.

Один набор проверок сопровождает перенос ручного цикла в SDK. Отследи, какие ошибки получает сама модель, а какие завершают вызов исключением. Один SDK и конкретный набор guardrails.

### M34

[Your MCP Server Works in the Inspector. Now Test it in CI](https://medium.com/@dmatoso/your-mcp-server-works-in-the-inspector-now-test-it-in-ci-d4f02bae6d75)

Douglas Matoso · Medium · Nov 4, 2026 · открытый текст · **8.6/10**

> M34 · Неделя 4 · Основная · Выборочно, 22 мин. Connect a real client in memory → What this doesn’t test.

MCP-клиент в памяти проверяет реальный протокол и снимок видимого модели контракта. Замокан внешний сервис. Такой тест не проверяет выбор инструмента самой моделью.

### M35

[Build the Same MCP Server in TypeScript with the MCP SDK v2 (@modelcontextprotocol/server)](https://medium.com/@nandanpriyadarshi/build-the-same-mcp-server-in-typescript-with-the-mcp-sdk-v2-modelcontextprotocol-server-a8e4c520c965)

Nandan Priyadarshi · Medium · Oct 27, 2026 · открытый текст · **8.2/10**

> M35 · Неделя 4 · Справочно · Выборочно, 12 мин. What failed first → Limits.

Сопоставь TypeScript и Python на одном контракте. Отдельно рассмотри stdout и ошибки транспорта. Сигнатуры и пакет SDK относятся к версии, указанной автором.

### M36

[Are LLM’s Ignoring Half our Context — Experimentations on My Laptop](https://medium.com/@bharani3ran/are-llms-ignoring-half-our-context-experimentations-on-my-laptop-7fd6b33127ce)

Bharanitharan Raghunathan · Medium · Mar 29, 2026 · открытый текст · **8.1/10**

> M36 · Неделя 4 · Основная · Бегло, 12 мин. сравнение попаданий при перестановке факта внутри контекста.

Локальный пример эффекта позиции помогает отделить наличие факта во входе от его использования моделью. Небольшой локальный тест; качество конкретного приложения требует отдельной проверки.

### M37

[I Treated an AI Agent’s Context Window Like a Garbage-Collected Heap. Here’s What Survived.](https://medium.com/@ai.in.cz/i-treated-an-ai-agents-context-window-like-a-garbage-collected-heap-here-s-what-survived-77380afe1439)

Sergiu N · Medium · Nov 19, 2026 · открытый текст · **8.6/10**

> M37 · Неделя 4 · Основная · Выборочно, 20 мин. Finding 1: The stub matters more than the collector → What didn’t work.

В сравнении стратегий очистки меняется и отметка, оставленная на месте удалённого сообщения. Она способна менять дальнейшее поведение агента. Одна модель; измерения включают конкретный набор задач автора.

### M38

[What caching does for an LLM agent ?](https://medium.com/google-cloud/what-caching-does-for-an-llm-agent-f254686e0b14)

EZEKIAS BOKOVE · google-cloud · Oct 28, 2026 · открытый текст · **8.6/10**

> M38 · Неделя 4 · Углубление · Выборочно, 22 мин. The big test: how should an agent remember? → What this does not show.

Сопоставь полную историю с краткой сводкой, отдельно учитывая кеширование провайдером и стоимость поддержки памяти. Небольшое число независимых повторов; в межмодельном сравнении результаты различаются.

### M39

[Reason, Act, Observe — Then Forget: tool_trajectory, a New Context Engineering Method for AI Agents](https://michalnasternak.medium.com/reason-act-observe-then-forget-tool-trajectory-a-new-context-engineering-method-for-ai-agents-500fc28b82ab)

Michał Nasternak · Medium · Sep 25, 2026 · открытый текст · **8.1/10**

> M39 · Неделя 4 · Углубление · Выборочно, 14 мин. Evaluation → Limitations.

На данных вызовов отдельно посчитаны токены содержимого инструмента и оболочки сообщения. Оценена верхняя граница экономии; часть наборов данных не содержит диалога.

### M40

[MemEval: Benchmarking Memory for AI Agents](https://medium.com/prosus-ai-tech-blog/memeval-benchmarking-memory-for-ai-agents-932d3fd9f3b4)

Asad Ismail · prosus-ai-tech-blog · Mar 9, 2026 · открытый текст · **8.3/10**

> M40 · Неделя 4 · Углубление · Выборочно, 18 мин. Benchmark Results → What We Chose Not to Build.

Удержание временных фактов и выбор правильного ответа проверяются при сопоставимых бюджетах. Смотри ошибки, по которым выбирали компоненты памяти. Измерения сделаны авторами одной из сравниваемых систем.

### M41

[Building the Harness Around AI Coding Tools](https://medium.com/data-science-collective/a-blueprint-for-agentic-coding-tools-c1e0e2ed797b)

Ida Silfverskiöld · data-science-collective · Oct 29, 2026 · Member-only · **8.2/10**

> M41 · Неделя 4 · Справочно · Выборочно, 15 мин. Level 5.1: Evaluating Skills (Claude Code).

Справочник по среде coding-агента. Имеет смысл, когда сравниваешь изменения правил и инструментов репозитория. Инструменты и версии быстро меняются; примеры касаются разработки кода.

### M42

[Five agents talking lost to five answers and a vote](https://medium.com/@karthickrajam18/five-agents-talking-lost-to-five-answers-and-a-vote-d15690013740)

Karthick Raja Mohan · Medium · Nov 19, 2026 · открытый текст · **8.5/10**

> M42 · Неделя 5 · Основная · Выборочно, 15 мин. The trick hiding in most comparisons → One study shows the whole story.

Сравни обсуждение пяти агентов с пятью независимыми ответами и голосованием. Так отделяется эффект общения от повторных попыток. Обзор препринта; отдельные наборы малы. Равное число проб ещё не означает одинаковую цену.

### M43

[Structuring multi-agent systems around irreversible actions: lessons from tau-bench](https://medium.com/@duttasaswata7/structuring-multi-agent-systems-around-irreversible-actions-lessons-from-tau-bench-defe0f139eda)

SD · Medium · Mar 30, 2026 · открытый текст · **9.0/10**

> M43 · Неделя 5 · Основная · Целиком, 36 мин. На tau-airline сравниваются один агент и planner/executor с проверкой записи. Посмотри траектории и разницу между единичным успехом и повторяемостью.

На tau-airline сравниваются один агент и planner/executor с проверкой записи. Посмотри траектории и разницу между единичным успехом и повторяемостью. Одинаковая модель, но число вызовов за ход различается; эффект архитектуры не изолирован от бюджета.

### M44

[Single Agent vs Multi-Agent Coding: A Controlled Experiment with Real Metrics](https://medium.com/@jainashish.079/single-agent-vs-multi-agent-coding-a-controlled-experiment-with-real-metrics-b8c4027e410f)

Ashish Kumar Jain · Medium · Feb 27, 2026 · открытый текст · **8.0/10**

> M44 · Неделя 5 · Углубление · Целиком, 8 мин. Одинаковая спецификация и 18 тестов: команда потратила около 118k токенов против 41k. Сопоставь активное время с паузой из-за rate limit.

Одинаковая спецификация и 18 тестов: команда потратила около 118k токенов против 41k. Сопоставь активное время с паузой из-за rate limit. Всего по одному прогону; одинаковые тесты не доказывают равенство качества кода.

### M45

[Planning and Search for LLM Agents: From DAG Execution to Tree-of-Thoughts](https://medium.com/@chierhu/planning-and-search-for-llm-agents-from-dag-execution-to-tree-of-thoughts-01436d8179cd)

Chier Hu · Medium · Oct 5, 2026 · открытый текст · **8.0/10**

> M45 · Неделя 5 · Справочно · Выборочно, 12 мин. Tree search → Reductions among architectures.

Сравни задачи с заранее известными зависимостями и задачи, где надо пересматривать частичные решения. Алгоритмический разбор; нет сопоставимого бенчмарка стоимости в продакшене.

### M02

[Building Self-Improving AI Applications with Harness²: From Agent Execution to Recursive Harness Optimization](https://medium.com/@danushidk507/building-self-improving-ai-applications-with-harness%C2%B2-from-agent-execution-to-recursive-harness-9657306a8086)

DhanushKumar · Medium · Nov 3, 2026 · открытый текст · **8.0/10**

> M02 · Неделя 5 · Углубление · Выборочно, 20 мин. Eight harness components: Which should be optimized, and when?.

Разложи изменения среды на компоненты и проверь, чем измеряют выигрыш петли обратной связи. Обзор метода; цифры исследования нельзя переносить на другую среду как собственное измерение автора.

### M46

[Every Harness Component Is a Bet: How to Prove Yours Still Pays Off](https://medium.com/@sajeevkr1/every-harness-component-is-a-bet-how-to-prove-yours-still-pays-off-bcef960b2c5d)

Sajeev KR · Medium · Nov 12, 2026 · открытый текст · **8.1/10**

> M46 · Неделя 5 · Основная · Выборочно, 12 мин. Testing a component → Components that cover for each other.

Абляции по одной компоненте дополни проверкой взаимодействий, иначе две подменяющие друг друга функции выглядят бесполезными. Числовой пример автор явно называет иллюстрацией.

### M47

[From Prompt to Production: How Prompt, Context, Loop, Graph, and Harness Engineering Fit Together](https://medium.com/google-cloud/from-prompt-to-production-how-prompt-context-loop-graph-and-harness-engineering-fit-together-76c5e748a1e7)

Shuva Jyoti Kar · google-cloud · Aug 28, 2026 · открытый текст · **8.2/10**

> M47 · Неделя 5 · Углубление · Выборочно, 20 мин. The end-to-end execution → Reliability and correctness are separate problems.

Дойди от одного вызова до обработки инцидента. Заметь, какие инварианты сохраняет рантайм при ошибке вывода. Демонстрационная архитектура; сравнительного замера выгод всех слоёв нет.

### M48

[Saved to Postgres, never queued: the transactional outbox for Node](https://medium.com/@krrishkumardev/saved-to-postgres-never-queued-the-transactional-outbox-for-node-1355dbafd5d3)

Krrish Kumar · Medium · Nov 1, 2026 · открытый текст · **8.7/10**

> M48 · Неделя 6 · Основная · Целиком, 18 мин. Окно между записью транзакции и постановкой задачи сохраняется при ретрае HTTP. Проследи путь одной записи outbox и её повторной доставки.

Окно между записью транзакции и постановкой задачи сохраняется при ретрае HTTP. Проследи путь одной записи outbox и её повторной доставки. Outbox решает атомарность записи намерения; потребителю всё ещё нужна идемпотентность.

### M49

[Background Jobs in Node.js with BullMQ: Retries, Idempotency and the Failure Modes](https://medium.com/@manisuec/background-jobs-in-node-js-with-bullmq-retries-idempotency-and-the-failure-modes-963b1dd24ad2)

Manish Prasad · Medium · Oct 29, 2026 · Member-only · **8.5/10**

> M49 · Неделя 6 · Основная · Выборочно, 32 мин. 6. Deduplication → 8. Idempotency, особенно Patterns B–D. 15. Incident playbook — справочно.

Проследи, как различаются повтор исполнения, дедупликация задания и защита внешнего эффекта. Используй разделы сбоев как справочник для Node. Конкретные гарантии зависят от конфигурации Redis и устройства потребителя.

### M50

[Deploying new Temporal workflow code while workflows are running](https://medium.com/@kalin.dimitrov93/deploying-new-temporal-workflow-code-while-workflows-are-running-a9ff9a62cfbd)

Kalin Dimitrov · Medium · Nov 16, 2026 · открытый текст · **8.8/10**

> M50 · Неделя 6 · Справочно · Целиком, 20 мин. Посмотри, как несовместимое изменение workflow ведёт себя после рестарта и при rolling deploy. История событий объясняет разницу.

Посмотри, как несовместимое изменение workflow ведёт себя после рестарта и при rolling deploy. История событий объясняет разницу. Один сценарий версионирования; устойчивость внешней операции проверяется отдельно.

### M51

[Durable Workflows at Angel One: Running Temporal as an Managed Platform](https://medium.com/angel-tech/durable-workflows-at-angel-one-running-temporal-as-an-managed-platform-d4f9acdfd9ee)

Prateek Garg · angel-tech · Nov 18, 2026 · открытый текст · **8.7/10**

> M51 · Неделя 6 · Углубление · Выборочно, 25 мин. Three ways to solve it → What we learned.

Angel One сопоставляет варианты управления длительными операциями и объясняет расходы на свою платформу Temporal. Организационные затраты и масштаб компании могут не соответствовать небольшой команде.

### M52

[Propagating User Identity Through an Agentic Workflow](https://medium.com/mongodb/propagating-user-identity-through-an-agentic-workflow-d19dff24e54c)

MongoDB · mongodb · May 15, 2026 · открытый текст · **8.6/10**

> M52 · Неделя 7 · Основная · Целиком, 28 мин. Сравни учётную запись агента, передачу токена пользователя и делегирование. Проследи, какую личность видит downstream-сервис при отложенном действии.

Сравни учётную запись агента, передачу токена пользователя и делегирование. Проследи, какую личность видит downstream-сервис при отложенном действии. Конкретные механизмы зависят от поддержки провайдером обмена токенов.

### M53

[How do you make an AI assistant respect document permissions on Databricks?](https://medium.com/@raghavmatta/how-do-you-make-an-ai-assistant-respect-document-permissions-f4a18336cc3a)

Raghav Matta · Medium · Oct 12, 2026 · открытый текст · **8.4/10**

> M53 · Неделя 7 · Основная · Выборочно, 16 мин. Does a live permission change actually flow through?.

Проследи изменение права на исходный документ до выдачи поисковой системы и проверь, когда отозванный доступ вступает в силу. Реализация зависит от Databricks и синхронизации групп.

### M54

[Building a Permission Gateway for MCP Agents:](https://medium.com/venkataprakhya7/building-a-permission-gateway-for-mcp-agents-what-i-learned-after-letting-ai-run-local-tools-b340c0c91d57)

Sri Ram Prakhya · venkataprakhya7 · May 26, 2026 · открытый текст · **8.1/10**

> M54 · Неделя 7 · Углубление · Выборочно, 12 мин. Building Approval Workflows → Open Questions.

Шлюз проверяет действие инструмента перед исполнением. Особый случай — подтверждение действия без интерактивного терминала. Опыт прототипа, а не формальная проверка всех путей доступа.

### M55

[OpenTelemetry for LLM Agents: Building Secure, Scalable AI Observability](https://medium.com/beyond-the-algorithm/secure-ai-observability-building-a-production-ready-opentelemetry-stack-for-llm-agents-8476031f7a3e)

Adam · beyond-the-algorithm · Aug 31, 2026 · открытый текст · **8.0/10**

> M55 · Неделя 8 · Справочно · Выборочно, 12 мин. Designing the Trace Model for AI Agents.

Разложи запрос пользователя на вызовы модели и инструментов. Сопоставь полезность трассы с риском сохранять сырой контент. Референсная архитектура без количественного сравнения платформ.

### M56

[LLM Observability: Traces, Tokens and Costs of Agentic App](https://medium.com/@khwajakhan/llm-observability-traces-tokens-and-cost-on-a-frozen-agentic-app-e0a3b9e2c790)

Khwaja Khan · Medium · Jun 25, 2026 · открытый текст · **8.4/10**

> M56 · Неделя 8 · Основная · Выборочно, 28 мин. Datasets & experiments — eval runs with observability context.

При сбое сразу по всем строкам trace помогает обнаружить ошибку оценщика. Разбери, как эксперимент связан с конкретным запуском. Пример на LangSmith; алерты и конфигурация зависят от продукта.

### M57

[Building Pinterest’s VLM Serving Stack on NVIDIA Dynamo](https://medium.com/pinterest-engineering/building-pinterests-vlm-serving-stack-on-nvidia-dynamo-0dce6e93d0f3)

Pinterest Engineering · pinterest-engineering · Sep 10, 2026 · открытый текст · **9.0/10**

> M57 · Неделя 8 · Углубление · Выборочно, 32 мин. Benchmarking Real Multimodal Workloads with AIPerf → Lessons Learned and What’s Next.

Pinterest разделяет работу энкодера, prefill и decode, затем проверяет latency и throughput под настоящим профилем мультимодальных запросов. Стек для VLM и крупные GPU; проценты нельзя переносить на небольшого текстового бота.

### M58

[Inference Basics: KV Cache, Batching & Parallelism](https://medium.com/@s09g/inference-basics-kv-cache-batching-parallelism-0c04378d4067)

s09g · Medium · Jun 17, 2026 · открытый текст · **8.3/10**

> M58 · Неделя 8 · Справочно · Выборочно, 15 мин. Why KV Cache is needed → How to estimate KV Cache memory.

При медленном первом токене разбери prefill, при медленной генерации — decode. Оцени память при росте batch. Описаны механизмы, стоимость своего трафика надо измерять.

### M59

[Inference Routing on Kubernetes: Six Options Benchmarked](https://medium.com/todea-engineering/inference-routing-on-kubernetes-six-options-benchmarked-c9ad6ac4f3b4)

Ivan Porta · todea-engineering · Nov 25, 2026 · открытый текст · **8.8/10**

> M59 · Неделя 8 · Углубление · Выборочно, 22 мин. How we tested → Routing configurations.

Сравни медиану и p95 у коротких запросов рядом с длинным prefill. Высокая доля попаданий в кеш может сочетаться с длинной очередью. Конкретная топология реплик и смесь запросов задают результат.

### M60

[What Really Limits LLM Inference Performance?](https://medium.com/data-science-collective/what-really-limits-llm-inference-performance-3d04ae41fe3e)

Buse Dinçer · data-science-collective · Oct 30, 2026 · открытый текст · **8.6/10**

> M60 · Неделя 8 · Углубление · Выборочно, 25 мин. What I would use in each scenario.

Сравни режим с одним пользователем и работу под нагрузкой. Смотри, какой ресурс ограничивает производительность и как измерено качество после квантизации. Одна A40; часть тестов выполнена один раз.

### M61

[›Benchmarking Semantic Caching with Oracle AI Database 26ai and Oracle True Cache](https://medium.com/oracledevs/benchmarking-semantic-caching-with-oracle-ai-database-26ai-and-oracle-true-cache-2403dd6c04d0)

Mark Nelson · oracledevs · Jul 1, 2026 · открытый текст · **8.4/10**

> M61 · Неделя 8 · Углубление · Выборочно, 18 мин. Decision Counts → Interpreting the Results.

Раздели точные совпадения, похожие запросы и промахи. Высокий hit rate может скрыть опасное повторное использование ответа. Стоимость рассчитана по токенам и выбранным тарифам; не счёт провайдера.

### M62

[Fine-Tuning or RAG? Classifying 77 Banking Intents with a LoRA](https://medium.com/@griffinjsisk/fine-tuning-or-rag-classifying-77-banking-intents-with-a-lora-6e06591d66af)

Griffin Sisk · Medium · Oct 19, 2026 · открытый текст · **8.7/10**

> M62 · Неделя 8 · Углубление · Выборочно, 20 мин. The Baseline → Cost.

На 77 банковских намерениях сравни классификацию с retrieved-примерами и LoRA при доступе к тем же данным. Точка окупаемости зависит от загрузки GPU и объёма трафика.

### M63

[Teaching a Small Model to Check a Big Model’s Work](https://medium.com/tr-labs-ml-engineering-blog/teaching-a-small-model-to-check-a-big-models-work-a9ab7523df10)

Marcos Esteve · tr-labs-ml-engineering-blog · Sep 11, 2026 · открытый текст · **8.7/10**

> M63 · Неделя 8 · Углубление · Выборочно, 20 мин. 5. Is the small model competitive?.

После дистилляции маленький судья использует короткий промпт. Отдельно оцени редкий класс галлюцинаций и стоимость инференса. Данные поддержки и используемая разметка ограничивают обобщение.

### M64

[Fine-tuning and serving an 11.5B SLM on one H100: how it compares with 11 Foundry models](https://medium.com/@wingnut0310/fine-tuning-and-serving-an-11-5b-slm-on-one-h100-how-it-compares-with-11-foundry-models-ac2d32c3a5e0)

Hyeonsang Jeon · Medium · ноябрь 2026 · открытый текст · **8.4/10**

> M64 · Неделя 8 · Углубление · Выборочно, 18 мин. 4. Cost vs. Foundry → Limits.

Сопоставь стоимость 1000 запросов при разных сочетаниях batching, кеширования и конкурентности на одной H100. Публичный тест допускает загрязнение обучающими данными; входы и параметры генерации у API отличаются.

### M65

[An LLM judge is a biased instrument, not a measurement](https://medium.com/@maya.andersson/an-llm-judge-is-a-biased-instrument-not-a-measurement-42f0ca7d304f)

mayaandersson-writes · Medium · 20 июля 2026 · открытый текст · **8.4/10**

> M65 · Неделя 2 · После M12 · Углубление · Целиком, 7 мин. Сверь оценки судьи с ручной разметкой и поменяй местами ответы в каждой паре.

В отличие от эксперимента M12 здесь есть процедура калибровки. Отчёт о смене победителя при перестановке ответов иллюстрирует смещение. Порог согласия и размер выборки для решения о релизе придётся обосновать отдельно.

### M66

[Semantic Cache: The Math of ‘Close Enough’](https://medium.com/towards-artificial-intelligence/semantic-cache-the-math-of-close-enough-c7dda07dcdc4)

Vatsala Singh · Towards AI · 11 мая 2026 · открытый текст · **7.7/10**

> M66 · Неделя 8 · После M56 · Справочно · Выборочно, 6 мин. Посмотри формулу свежести и ограничения кеша.

Косинусное сходство уменьшается с возрастом записи вплоть до истечения TTL. Это дополняет трассировку M56 механизмом экономии вызовов. У автора нет измерения доли ложных попаданий, которое подтвердило бы выигрыш на вашем трафике.

### M67

[Rules of Machine Learning](https://developers.google.com/machine-learning/guides/rules-of-ml)

Martin Zinkevich · Google · обновляемый документ · открытый доступ · оценка не присвоена

> M67 · Неделя 1 · Основная · Выборочно, 10 мин.

Правила 1–4. Выбери простую эвристику и показатель, по которому усложнение оправдает себя. Это метод выбора baseline. Для численного примера на Medium выбери M68.

Перед M68 — обязательный старт.

### M68

[Why Using GPT May Not Be the Best Option for Customer Feedback Classification](https://medium.com/picnic-engineering/why-using-gpt-may-not-be-the-best-option-for-customer-feedback-classification-12e9c36cd4a7)

Maarten Sukel · Picnic Engineering · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 1 · Основная · 15 мин.

Picnic сравнивает TF-IDF, DistilBERT и дообученный GPT-3 на маршрутизации отзывов. Двухдневный эксперимент 2023 года показывает дизайн сравнения. Рейтинг современных моделей требует новых измерений. [Версия команды](https://jobs.picnic.app/en/blogs/why-using-gpt-may-not-be-the-best-option-for-customer-feedback-classification).

Старт недели 1. Сравни weighted Fβ с ценой редкой ошибки. Объём обучения у вариантов различался.

### M69

[Cross-validation: evaluating estimator performance](https://scikit-learn.org/stable/modules/cross_validation.html)

scikit-learn · User Guide · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 2 · Основная · 15 мин.

Прочитай подразделы про GroupKFold и TimeSeriesSplit. Выбери единицу проверки по тому, что встретится после релиза: новый документ, клиент или будущий период. Если нужны и новые группы, и будущие даты, проверь оба ограничения отдельно. Пример группового разбиения на Medium — M70.

Перед M10. Заранее определи, появятся ли новые клиенты, будущие даты или оба условия сразу.

### M70

[Your Cross-Validation Score Is a Lie, and Here Are the Five Reasons Why](https://medium.com/data-and-beyond/your-cross-validation-score-is-a-lie-and-here-are-the-five-reasons-why-b464239338d6)

Dima Iakubovskyi · Data And Beyond · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 2 · Углубление · 10 мин.

В разделе Leak 2 автор сравнивает случайное и групповое разбиение повторных наблюдений. Синтетические идентификаторы показывают механизм утечки. За временным разбиением вернись к M69.

После M69 как пример утечки по группам.

### M71

[Heterogeneous Treatment Effects at Netflix](https://netflixtechblog.medium.com/heterogeneous-treatment-effects-at-netflix-da5c3dd58833)

Scott Seyfarth и соавторы · Netflix · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 2 · Основная · 15 мин.

После M11. Discovery и Deciding Experiments. Разбери, почему число просмотренных сегментов меняет интерпретацию выброса. Масштаб онлайн-тестов Netflix ограничивает перенос на малый eval.

Малый срез может выявить критический дефект. Отсутствие сигнала оставляет неопределённость.

### M72

[Three mistakes when introducing embeddings and vector search](https://bergum.medium.com/four-mistakes-when-introducing-embeddings-and-vector-search-d39478a568c5)

Jo Kristian Bergum · Medium · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 3 · Основная · 15 мин.

Перед M17. Отдели релевантность для пользователя от близости векторов и от того, насколько точно индекс нашёл соседей. Описанные модели относятся к 2023 году.

Сравни overlap@k между ANN и точным поиском на одинаковых векторах. Для пользовательской релевантности используй Recall@k или nDCG@k по разметке.

### M73

[RAG retrieval accuracy depends on chunking. I measured how much](https://medium.com/@sankeerthan.kasilingam/rag-retrieval-accuracy-depends-on-chunking-i-measured-how-much-1414cb5ae829)

Sankeerthan · Medium · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 3 · Углубление · 20 мин.

После M18. От The experiment до What it doesn’t fix (yet). На двух документах и 80 вопросах видно, когда найденная строка бесполезна без заголовка колонки. Сравни с причинами промахов на книжном корпусе M18.

### M74

[The first step of a multimodal pipeline: which PDF parser keeps the structure?](https://medium.com/@oliver-mlops/the-first-step-of-a-multimodal-pipeline-which-pdf-parser-keeps-the-structure-303a9968e39f)

Oliver Faraday · Medium · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 3 · Справочно · 10 мин.

Results и Limits, stated plainly. Сравнение на 16 синтетических PDF измеряет сохранение структуры. Для оценки ответов потребуются поисковые вопросы.

При расследовании PDF сначала проверь структуру, затем открой M73.

### M75

[Measure LLM Cost Savings: Log Routes, Replay, Catch Drift](https://medium.com/towards-data-engineering/measure-llm-cost-savings-log-routes-replay-catch-drift-a3b15d51d1c7)

Sunny Sharma · Towards Data Engineering · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 8 · Основная · 20 мин.

После M56. The scoreboard и Drift. На 32 вопросах с тремя повторами сравни цену, качество и задержку роутера с одной моделью. Автор подбирал настройки на этих же вопросах. [Открытая версия автора](https://devsdaily.com/measure-llm-cost-savings/).

Для продуктовой проверки зафиксируй когорту и окно наблюдения. Раздели расходы всех попыток, включая неудачи и ручную обработку, на число подтверждённых пользовательских успехов. Отдельно покажи незавершённые задачи и повторные обращения. Офлайн-метрика $ per correct использует другой критерий успеха.

### M76

[Modernizing the Netflix TV UI Deployment Process](https://netflixtechblog.medium.com/modernizing-the-netflix-tv-ui-deployment-process-28e022edaaef)

Ashley Yung · Netflix · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 8 · Основная · 15 мин.

После M75. What about A/B-test-based canaries? Проследи решения об остановке раскатки по ошибкам JavaScript и росту памяти. Для LLM дополнительно нужен сигнал качества пользовательской задачи.

### M77

[Return-Aware Experimentation](https://netflixtechblog.medium.com/return-aware-experimentation-3dd93c94b67a)

Simon Ejdemyr и Winston Chou · Netflix · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 8 · Углубление · 10 мин.

После M76 для углубления в эксперименты. Evaluating Decision Rules Across Many Weak Experiments. Раздели данные, на которых выбран победитель, и данные для оценки выгоды этого выбора. Метод опирается на историю экспериментов.

### M78

[Troubleshooting: Abort breaks resumable streams](https://ai-sdk.dev/docs/troubleshooting/abort-breaks-resumable-streams)

AI SDK · Vercel · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 6 · Основная · 5 мин.

После M81. Разбери конфликт отмены и возобновления в useChat. Различай разрыв соединения, остановку генерации и исход внешнего действия. Ограничение относится к этому SDK. Связанный пример на Medium — M79.

### M79

[Why your AI response restarts on page refresh (and what it takes to prevent it)](https://medium.com/@ably_realtime/why-your-ai-response-restarts-on-page-refresh-and-what-it-takes-to-prevent-it-007789615992)

Ably Team · Medium · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 6 · Основная · 8 мин.

После M78. How resumable streaming actually works объясняет идентификатор ответа, позицию и повторную доставку. Пример иллюстративный, публикация поставщика. Подтверждение внешнего действия см. M49.

Сообщение об отмене внешнего действия требует подтверждения бизнес-системы. При неизвестном исходе покажи, что статус уточняется.

### M80

[Accelerating Transformer-based Embedding Retrieval with Vespa](https://blog.vespa.ai/accelerating-transformer-based-embedding-retrieval-with-vespa/)

Jo Kristian Bergum · Vespa Blog · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 3 · Углубление · 15 мин.

После M17. Прочитай два раздела Putting it all together про точный поиск и HNSW. На одном корпусе MIRACL сопоставь nDCG@10 и p95 при одинаковом числе клиентов. Совпадение качества по разметке ещё допускает различия в найденных соседях. M72 на Medium объясняет механизм. Числа привязаны к конфигурации стенда.

### M81

[Making agent retries safe across timeouts and restarts](https://dev.to/deavgprime/making-agent-retries-safe-across-timeouts-and-restarts-448b)

deavgprime · DEV Community · дата: уточнить · доступ: уточнить · оценка не присвоена

> Неделя 6 · Основная · 15 мин.

После M49, перед M78. От A key did not fix the split transaction до How long does the protection last? В локальном стенде с двумя SQLite-базами автор считал созданные заказы при потерянных ответах и рестартах. Проверь, когда вместе фиксируются действие и квитанция, сколько хранится ключ и какой исход может подтвердить клиент. Близкий материал на Medium — раздел 8 в M49. Затем M78 и M79 показывают последствия для интерфейса.


### M82

[Deep dive into Text Generation Inference with LLMs](https://huggingface.co/docs/course/chapter1/8)

Hugging Face · LLM Course · обновляемый курс · открытый текст · оценка не присвоена (новый учебный источник)

> M82 · Неделя 1 · Основная · Выборочно, 20 мин. Prefill, Decode, Sampling Strategies. Токенизация, autoregressive decoding, logits, temperature, top-p/top-k. Logits — ненормированные оценки, а не вероятности; greedy и temperature=0 не гарантируют идентичность между версиями API. Перед M06.


### M83

[Reasoning best practices](https://developers.openai.com/api/docs/guides/reasoning-best-practices)

OpenAI · документация · обновляемая · открытый текст · оценка не присвоена (новый учебный источник)

> M83 · Неделя 1 · Основная · Выборочно, 15 мин. Разделы о выборе reasoning-моделей и сочетании моделей. Сравни обычную и reasoning-модель на одинаковых задачах с фиксированными бюджетами и измерением качества, цены, p95. Примеры поставщика не являются независимым сравнением. После M07; M08 и M75 — продолжение.


### M84

[Post-tuning the decision threshold for cost-sensitive learning](https://scikit-learn.org/stable/auto_examples/model_selection/plot_cost_sensitive_learning.html)

scikit-learn · документация · обновляемая · открытый текст · оценка не присвоена (новый учебный источник)

> M84 · Неделя 1 · Основная · Выборочно, 15 мин. Cost-sensitive learning with constant gains and costs. Сопоставь FP/FN с потерями бизнеса, подбирай порог на validation, проверяй на held-out данных. Для вероятностного порога нужна калибровка; самооценка уверенности LLM не является калиброванной вероятностью. После M68.


### M85

[Evaluation of LLM systems — статистика сравнения](https://mseyfi.github.io/llm-vlm/applications/evaluation-of-llm-systems.html)

LLM and VLM course · учебная глава · дата не установлена · открытый текст · оценка не присвоена (новый учебный источник)

> M85 · Неделя 2 · Основная · Выборочно, 25 мин. Small test sets, paired comparisons, How many items do you need? Wilson для отдельной доли, exact McNemar для парного бинарного сравнения, paired bootstrap для разницы метрик; ресэмплируй независимые группы. Заранее задай допустимую регрессию и критические дефекты; незначимый результат не доказывает эквивалентность. После M71. [Первоисточник по error bars](https://arxiv.org/abs/2411.00640).


### M86

[The lethal trifecta for AI agents: private data, untrusted content, and external communication](https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/)

Simon Willison · блог · 16 июня 2025 · открытый текст · оценка не присвоена (новый учебный источник)

> M86 · Неделя 7 · Основная · Целиком, 15 мин. Прочитай целиком. Различай prompt injection и jailbreak; внешние документы — недоверенные данные. Ограничивай чтение и отправку данных, полномочия инструментов и сетевые назначения вне модели. Подтверждение опасного действия дополняет, но не заменяет ограничения. После M53.


### M87

[Optimizing Customer Support Agents for Cost and Quality](https://developers.openai.com/cookbook/examples/agent_optimization/optimizing_agents_for_cost_and_quality)

OpenAI Cookbook · дата не установлена · открытый текст · оценка не присвоена (новый учебный источник)

> M87 · Неделя 8 · Основная · Выборочно, 25 мин. Выборочно: blended cost per verified resolution, Define success before optimizing, Track the complete support workflow, Demo limitation. Разделяй автономное решение, помощь человека, открытый тикет и повторное обращение; учитывай расходы неуспешных попыток, ретраи, fallback, ручную работу и p95. Это учебная симуляция, не production-инцидент. После M75.


### M88

[AI Evals FAQ — production monitoring → CI dataset](https://hamel.dev/blog/posts/evals-faq/how-are-evaluations-used-differently-in-cicd-vs-monitoring-production.html)

Hamel Husain / Shreya Shankar · AI Evals FAQ · обновляемая · открытый текст · оценка не присвоена (новый учебный источник)

> M88 · Неделя 8 · Основная · Выборочно, 15 мин. Прочитай FAQ о CI vs production и [sampling production traces](https://hamel.dev/blog/posts/evals-faq/how-can-i-efficiently-sample-production-traces-for-review.html). Сочетай случайную и целевую выборки, размечай причины сбоев, добавляй репрезентативные случаи в регрессионный набор, версионируй golden set и оставляй независимый holdout. После M76.
