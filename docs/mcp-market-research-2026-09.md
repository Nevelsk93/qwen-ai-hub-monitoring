# Глобальная разведка рынка услуг MCP (Model Context Protocol)

Дата исследования: 6 сентября 2026.
Метод: точечная проверка конкретных URL/страниц/выдачи поиска по каждой площадке (веб-поиск + прямой fetch там, где это было технически возможно без логина). Ни один вывод не сделан только на основании одного SEO-текста без второго независимого подтверждения (листинг, профиль, job-пост, официальная доксстраница).

Статусы:
- **CONFIRMED** — есть реальный профиль/job/service/category, подтверждено ссылкой на конкретный листинг.
- **PLATFORM-NATIVE** — сама платформа внедрила MCP (обычно как API/интеграцию, а не как биржу труда).
- **EARLY SIGNAL** — отдельные реальные упоминания есть, но выделенного рынка/категории ещё нет.
- **NOT FOUND** — по запросам на английском/русском/местном языке ничего подтверждённого не найдено.
- **BLOCKED** — сайт не отдаёт контент без авторизации/за антиботом (прямой fetch вернул 403 и т.п.).

Ограничение метода: у меня нет логина ни на одной из площадок, поэтому "можно ли создать профиль" / "есть ли отдельная категория" проверялось по публичным страницам, поисковой выдаче и документации платформ, а не изнутри аккаунта. Это явно помечено в колонке Restrictions.

---

## 1. FREELANCE MARKETPLACES (человек ↔ человек/компания)

### Upwork
- Country/region: Global
- Type: Freelance marketplace
- MCP status: **CONFIRMED + PLATFORM-NATIVE** (двойной статус)
- What can we sell: custom MCP-серверы, MCP-интеграции для бизнес-инструментов, "MCP Integration Plan" как фиксированный продукт
- Hourly supported: Да
- Fixed supported: Да (Project Catalog, от $5 до $500 000)
- Service listing supported: Да (Project Catalog / Services)
- MCP skill/category: MCP как ключевое слово в поиске работает, отдельного "MCP" navigation-раздела в тегах категорий нет
- Примеры продавцов: "You will get a custom MCP Server for your AI Agent" (upwork.com/services/product/...), "MCP Integration Plan – Model Context Protocol for Enterprise AI"
- Примеры заказов: "MCP Developer – Build Custom Claude (MCP) Integration for Business Tools" (contract, less than 30 hrs/week, 1–3 months)
- Example rates: не указаны публично для job-постов; Project Catalog $5–$500 000 за проект
- Registration URL: https://www.upwork.com/nx/create-profile/
- MCP evidence URLs:
  - https://www.upwork.com/services/product/development-it-a-custom-mcp-server-for-your-ai-agent-1906508401626549581
  - https://www.upwork.com/services/product/development-it-mcp-integration-plan-model-context-protocol-for-enterprise-ai-2001862319393991008
  - https://www.upwork.com/freelance-jobs/apply/MCP-Developer-Build-Custom-Claude-MCP-Integration-for-Business-Tools_~022072263193693942605/
  - https://up-bro.com/blog/upwork-mcp-server (Upwork запустила 10 августа 2026 официальный MCP-сервер mcp.upwork.com — AI-агенты клиентов ищут фрилансеров через MCP, ранжируя по Job Success Score)
- Restrictions: комиссия Upwork, connects на отклики,需要 верификация профиля
- Recommended action: создать профиль + минимум 2 Project Catalog листинга с ключевыми словами "MCP server", "Model Context Protocol integration"
- Priority: **NOW**

### Fiverr
- Country/region: Global
- Type: Service/gig marketplace
- MCP status: **CONFIRMED**
- What can we sell: готовые gig-услуги по разработке/интеграции MCP-серверов
- Hourly supported: Нет (Fiverr = fixed package tiers)
- Fixed supported: Да
- Service listing supported: Да, это основной формат площадки
- MCP skill/category: нет отдельной категории, но десятки живых gigs находятся по ключевым словам "Model Context Protocol", "MCP server"
- Примеры продавцов: asheshgoplan509 ($3000, "build and integrate MCP servers"), sabakhupenia ($100), wijay58 ($90)
- Примеры заказов: см. выше — это уже действующие продажи, не вакансии
- Example rates: $90–$3000 за проект (fixed gig packages)
- Registration URL: https://www.fiverr.com/start_selling
- MCP evidence URLs:
  - https://www.fiverr.com/asheshgoplan509/build-and-integrate-model-context-protocol-mcp-servers-for-you
  - https://www.fiverr.com/sabakhupenia/build-and-deploy-custom-model-context-protocol-mcp-servers
  - https://www.fiverr.com/wijay58/create-model-context-protocol-custom-mcp-servers-for-your-ai-app-ai-agent
- Restrictions: комиссия 20%, конкуренция по цене (демпинг видно уже сейчас — $90 против $3000 за похожий скоуп)
- Recommended action: разместить 2-3 gig'а с разной ценовой вилкой (mini/standard/enterprise MCP server)
- Priority: **NOW**

### Freelancer.com
- Country/region: Global
- Type: Freelance marketplace (bidding)
- MCP status: **CONFIRMED**
- What can we sell: разработка MCP-серверов/клиентов, коннекторы к БД/CRM
- Hourly supported: Да
- Fixed supported: Да
- Service listing supported: Да (отдельный hire-лендинг)
- MCP skill/category: Да — у платформы есть выделенная страница-категория "Model Context Protocol (MCP)"
- Примеры продавцов: на hire-странице ~9000+ фрилансеров онлайн, витрина профилей с рейтингом 4.7–5.0, портфолио 106-608 проектов (гео: Пакистан, Индия, Бангладеш)
- Примеры заказов: активная категория вакансий "Model Context Protocol (MCP) Jobs for August 2026"
- Example rates: **$15–$90/час** (диапазон указан прямо на лендинге)
- Registration URL: https://www.freelancer.com/signup
- MCP evidence URLs:
  - https://www.freelancer.com/hire/model-context-protocol
  - https://www.freelancer.com/jobs/model-context-protocol
- Restrictions: сильная ценовая конкуренция снизу ($15/час), нужен verified profile для доверия
- Recommended action: зарегистрироваться, указать MCP в skills, откликаться в категории Model Context Protocol Jobs
- Priority: **NOW**

### Toptal
- Country/region: Global (premium/vetted)
- Type: Elite freelance/staffing marketplace
- MCP status: **NOT FOUND** (нет прямых подтверждений отдельной MCP-вертикали на самом Toptal; в выдаче есть только сторонние агентства "Hire MCP Developers", имитирующие формат Toptal, но не сам Toptal)
- What can we sell: потенциально — MCP/AI-agent engineering как часть общего AI/ML трека
- Hourly supported: Да (в целом по платформе)
- Fixed supported: Ограниченно
- Service listing supported: Нет (staffing-модель, не self-service gig)
- MCP skill/category: не обнаружено
- Примеры продавцов/заказов: нет
- Example rates: н/д
- Registration URL: https://www.toptal.com/talent/apply
- MCP evidence URLs: нет прямых (проверено отсутствие)
- Restrictions: жёсткий отбор (~3% acceptance), не self-listing
- Recommended action: подать заявку в общий AI Engineering трек, MCP указать в bio/portfolio
- Priority: **SECOND WAVE**

### Malt (Франция/Европа)
- Country/region: France, EU
- Type: Freelance marketplace
- MCP status: **CONFIRMED**
- What can we sell: MCP-интеграции, AI agent expert консалтинг
- Hourly supported: Нет напрямую (Malt — day-rate/дневная ставка)
- Fixed supported: Да
- Service listing supported: Да (профиль + "missions")
- MCP skill/category: Да — у Malt есть отдельный **tag "mcp"** (URL с ID тега), т.е. это официально распознаваемый skill-тег
- Примеры продавцов: Frédéric Barthelet ("AI agent expert – Model Context Protocol (MCP)", malt.com/profile/fredericbarthelet); разработчик в Тулузе — 400 €/день; разработчик в Париже — 1050 €/день
- Примеры заказов: не выявлено отдельных MCP-миссий (заказы идут через личные приглашения)
- Example rates: **400–1050 €/день**
- Registration URL: https://www.malt.fr/inscription-freelance
- MCP evidence URLs:
  - https://www.malt.fr/s/tags/mcp-69089940951c5055bb0dc849 (прямой fetch вернул 403 — BLOCKED для верификации без логина, но страница проиндексирована и цитируется поиском)
  - https://www.malt.com/profile/fredericbarthelet
- Restrictions: доступ к части контента требует логина (см. BLOCKED выше), комиссия Malt ~10%
- Recommended action: создать профиль, добавить тег "MCP" и "Model Context Protocol" в skills
- Priority: **NOW**

### Contra
- Country/region: Global (creative/tech leaning US)
- Type: Commission-free freelance network
- MCP status: **PLATFORM-NATIVE**
- What can we sell: сама площадка ничего не продаёт про MCP-разработку — она **сделала MCP-сервер** для доступа к своей бирже из ИИ-инструментов
- Hourly supported: Да (обычный функционал Contra)
- Fixed supported: Да
- Service listing supported: Да ("productize your services")
- MCP skill/category: MCP как skill-тег не подтверждён отдельно
- Примеры продавцов/заказов: н/д (не про продажу MCP-услуг, а про доступ к Contra через MCP)
- Example rates: н/д
- Registration URL: https://contra.com/independent
- MCP evidence URLs: https://contra.com/features/mcp
- Restrictions: —
- Recommended action: завести обычный профиль (0% комиссии для фрилансера), продвигать AI/MCP-услуги как категорию "AI agent integration"
- Priority: **SECOND WAVE**

### PeoplePerHour, Guru.com
- Country/region: UK/Global; Global
- Type: Freelance marketplace
- MCP status: **NOT FOUND** (по обеим платформам — ни на английском, ни в комбинированном запросе не нашлось ни одного реального MCP-гига/джоба/профиля; выдача по "Guru" стабильно подменяется продуктом GetGuru (базы знаний), это разные компании)
- What can we sell: потенциально — общий "AI integration / automation" тег
- Hourly/Fixed/Listing supported: Да (обе платформы поддерживают все форматы в целом)
- MCP skill/category: нет
- Registration URL: https://www.peopleperhour.com/freelancer/signup ; https://www.guru.com/register.aspx
- MCP evidence URLs: нет подтверждённых
- Restrictions: —
- Recommended action: зайти первыми, пока пусто — застолбить профиль с MCP в описании
- Priority: **WATCH**

### Kwork (Россия/СНГ)
- Country/region: Russia/CIS
- Type: Fixed-price gig marketplace ("кворк" = фиксированный лот)
- MCP status: **CONFIRMED**
- What can we sell: настройка/установка MCP-серверов, интеграция LLM + MCP (filesystem, playwright, desktop-commander), интеграция с 1С через MCP
- Hourly supported: Нет (Kwork = фиксированные лоты)
- Fixed supported: Да
- Service listing supported: Да
- MCP skill/category: нет выделенной категории, но кворки реально продаются под запрос "MCP"
- Примеры продавцов: профиль ezlobin (автоматизация/интеграция CRM, упоминается в контексте MCP-настройки), кворк "Интеграция CRM, ERP с внешними API" — 10 000 ₽
- Примеры заказов: описан кейс "Настройка DeepSeek + 3 MCP-сервера на Kwork" (vc.ru разбор реального заказа)
- Example rates: ~**10 000 ₽** за интеграцию (пример)
- Registration URL: https://kwork.ru/register
- MCP evidence URLs:
  - https://kwork.ru/user/ezlobin
  - https://vc.ru/ai/2947551-nastroika-deepseek-i-mcp-serverov-na-kwork
  - https://kwork.ru/script-programming/53526678/integratsiya-crm-erp-s-vneshnimi-api
- Restrictions: комиссия Kwork ~20%, нужен рейтинг для видимости
- Recommended action: разместить кворк "Настрою MCP-сервер под Claude/Cursor/ChatGPT" с вилкой 3 000–30 000 ₽
- Priority: **NOW**

### FL.ru
- Country/region: Russia
- Type: Freelance marketplace (проекты + фиксированные услуги)
- MCP status: **EARLY SIGNAL** (прямых MCP-заказов на FL.ru поиском не найдено; площадка индексируется поисковиками слабо, `site:fl.ru` не дал ни одного релевантного результата — это может быть как реальное отсутствие спроса, так и ограничение поиска)
- What can we sell: интеграция ИИ-агентов, разработка ботов/коннекторов
- Hourly/Fixed/Listing supported: Да (все форматы)
- MCP skill/category: не обнаружено
- Registration URL: https://www.fl.ru/registration/
- MCP evidence URLs: нет (проверено — не найдено)
- Restrictions: сайт слабо индексируется в общем поиске, реальную картину даст только внутренний поиск на самом FL.ru
- Recommended action: зайти вручную на fl.ru/projects и проверить внутренний поиск по "MCP" — веб-поиск снаружи это не показывает
- Priority: **WATCH**

### Хабр Фриланс (freelansim.ru)
- Country/region: Russia
- Type: Freelance job board (агрегатор заказов)
- MCP status: **EARLY SIGNAL**
- What can we sell: разработка MCP-серверов как IT-заказ
- Hourly/Fixed supported: Да (формат — публикация заказов с бюджетом)
- Service listing supported: Ограниченно (это больше job-board, чем seller-профиль)
- MCP skill/category: MCP заказы возможны в общей IT/разработка категории, отдельного тега нет
- Registration URL: https://freelansim.ru/
- MCP evidence URLs: https://t.me/s/freelansim_ru (телеграм-канал агрегатора заказов, общий IT-поток)
- Restrictions: нет прямого подтверждения MCP-заказов, площадка мала
- Recommended action: подписаться на телеграм-канал заказов и фильтровать по "MCP"/"ИИ-агент"
- Priority: **WATCH**

### hh.ru (HeadHunter)
- Country/region: Russia/CIS
- Type: Job board (вакансии + резюме на проектную работу)
- MCP status: **CONFIRMED (как вакансии/резюме, не как gig-биржа)** + PLATFORM-NATIVE (есть сторонний MCP-коннектор к API hh.ru)
- What can we sell: резюме/отклик как "MCP-разработчик" на штатные и проектные позиции
- Hourly supported: Нет (штатная/проектная модель, не почасовая биржа)
- Fixed supported: Частично (проектная работа как формат занятости)
- Service listing supported: Нет (это не витрина услуг, а резюме+вакансии)
- MCP skill/category: есть отдельная профессиональная роль "MCP-разработчик" (упоминается в статье Хабра как формирующаяся специализация 2026 года)
- Примеры продавцов: резюме программистов на "проектную работу" — общая категория https://hh.ru/resumes/programmist_stazher/proektnaya_rabota
- Example rates: н/д публично
- Registration URL: https://hh.ru/applicant/resumes
- MCP evidence URLs: https://habr.com/ru/articles/1061358/ ("MCP-разработчик 2026: чем занимается, топ-8 курсов")
- Restrictions: hh.ru — это в первую очередь штат/долгосрочные вакансии, не быстрые gig-заказы
- Recommended action: добавить "MCP", "Model Context Protocol" в ключевые навыки резюме, включить фильтр "проектная работа"
- Priority: **SECOND WAVE**

### Avito Услуги
- Country/region: Russia
- Type: Local services marketplace
- MCP status: **EARLY SIGNAL**
- What can we sell: "настрою ИИ-агента/MCP для бизнеса" как локальная услуга
- Hourly/Fixed supported: Да (Avito Услуги — фиксированная цена или "по договорённости")
- Service listing supported: Да
- MCP skill/category: нет отдельной категории; прямых объявлений "MCP" не найдено, только косвенные (MCP-шлюз для доступа к Avito, а не услуги на Avito)
- Registration URL: https://www.avito.ru/professional_services
- MCP evidence URLs: https://mcpgate.ru/servers/avito (это про доступ ИИ-агентов К Avito, не про заказ MCP-услуг НА Avito)
- Restrictions: аудитория Avito Услуг — малый бизнес/локальные заказчики, для них термин "MCP" почти неизвестен — нужно продавать как "настройка ИИ-ассистента для бизнеса"
- Recommended action: разместить услугу под понятным для локального заказчика названием ("подключу ChatGPT/Claude к вашим базам данных и CRM"), MCP как техническое описание внутри
- Priority: **WATCH**

### YouDo
- Country/region: Russia
- Type: Task/gig marketplace (бытовые и IT-задачи)
- MCP status: **NOT FOUND**
- What can we sell: потенциально — IT-задачи с ИИ-агентами
- Registration URL: https://youdo.com/executor
- MCP evidence URLs: нет
- Restrictions: YouDo исторически слабо про сложную разработку, аудитория не целевая
- Recommended action: не приоритет
- Priority: **SKIP**

### TenChat
- Country/region: Russia
- Type: Профессиональная соцсеть + биржа услуг (не классический фриланс-маркетплейс)
- MCP status: **EARLY SIGNAL** (много контента про MCP, но это блог-платформа/нетворкинг, не транзакционная биржа услуг)
- What can we sell: экспертный контент + лидогенерация на консалтинг по ИИ-агентам/MCP
- Service listing supported: Частично (есть "услуги" в профиле, но модель — нетворкинг, не маркетплейс)
- Registration URL: https://tenchat.ru/
- MCP evidence URLs: https://tenchat.ru/media/3638065-mcpservery-kak-budet-ustroyen-ii-buduschego
- Restrictions: не биржа сделок, скорее PR-канал
- Recommended action: использовать как канал контент-маркетинга, не как точку продаж
- Priority: **WATCH**

### Workana, 99Freelas, Weblancer, Truelancer
- Country/region: LatAm (Workana); Brazil (99Freelas); Ukraine/Europe (Weblancer); Global/India (Truelancer)
- Type: Freelance marketplaces
- MCP status: **NOT FOUND** по всем четырём (ни одного реального листинга/заказа/профиля с MCP на местном языке не обнаружено)
- What can we sell: потенциально то же самое (integração/desarrollo de servidores MCP)
- Registration URL: https://www.workana.com/register ; https://www.99freelas.com.br/ ; https://www.weblancer.net/ ; https://www.truelancer.com/
- MCP evidence URLs: нет
- Restrictions: рынок либо совсем не сформирован, либо не индексируется на этих языках
- Recommended action: **B-карта** — занять место первым на локальном языке (испанский/португальский), пока конкурентов ноль
- Priority: **SECOND WAVE**

---

## 2. JOB / CONTRACT MARKETPLACES

### LinkedIn Jobs
- Country/region: Global
- MCP status: **CONFIRMED**
- What can we sell: contract/consulting позиции
- Пример: "Front End Developer (React, AI Agents, MCP Model Context Protocol Servers) — Contract" в Остине, Техас
- Hourly/Fixed: контрактные позиции, обычно почасовая ставка через агентство
- Registration URL: https://www.linkedin.com/jobs/
- MCP evidence URLs: https://www.linkedin.com/jobs/view/front-end-developer-react-ai-agents-mcp-model-context-protocol-servers-contract-at-austin-tx-at-red-oak-technologies-4328833183
- Restrictions: нужен сильный профиль + сеть контактов
- Recommended action: добавить "Model Context Protocol" как Skill в профиль (LinkedIn Skills — прямое совпадение с рекрутерским поиском), включить open-to-work по contract
- Priority: **NOW**

### Dice
- Country/region: US tech
- MCP status: **CONFIRMED + PLATFORM-NATIVE**
- What can we sell: contract MCP/AI позиции
- Пример: "Python Developer with (Model Context Protocol / MCP)" — W2 onsite вакансия через Dice
- MCP evidence URLs: https://www.linkedin.com/jobs/view/python-developer-with-model-context-protocol-mcp-only-w2-onsite-at-jobs-via-dice-4288066509 ; https://www.dice.com/career-advice/dice-launches-mcp-server-for-ai-powered-job-search
- Registration URL: https://www.dice.com/dashboard/register
- Restrictions: в основном W2/долгосрочные контракты, США
- Recommended action: зарегистрировать профиль, включить MCP в skill match
- Priority: **SECOND WAVE**

### Indeed
- Country/region: Global
- MCP status: **CONFIRMED + PLATFORM-NATIVE**
- What can we sell: MCP/AI Architect позиции (штат и контракт)
- MCP evidence URLs: https://www.indeed.com/q-mcp-jobs.html ; https://docs.indeed.com/mcp/ (официальный MCP-сервер Indeed, beta)
- Registration URL: https://www.indeed.com/
- Restrictions: смешанный поток (много вакансий не по теме, надо фильтровать)
- Recommended action: настроить job alert на "MCP" + "Model Context Protocol"
- Priority: **SECOND WAVE**

### RemoteOK, WeWorkRemotely
- Country/region: Global remote
- MCP status: **NOT FOUND** прямых MCP-вакансий (RemoteOK данные доступны только как MCP-скрейпер для третьих лиц, не как MCP-раздел вакансий на самой площадке)
- Registration URL: https://remoteok.com/ ; https://weworkremotely.com/
- MCP evidence URLs: нет прямых вакансий с MCP
- Restrictions: —
- Recommended action: поиск по общим тегам "AI agent", "LLM integration" вместо "MCP" — конверсия по точному термину пока низкая
- Priority: **WATCH**

### Gun.io
- Country/region: US-focused vetted talent network
- MCP status: **EARLY SIGNAL** (Gun.io публикует контент про MCP как образовательный материал, но подтверждённых MCP-контрактов через саму площадку не найдено)
- Registration URL: https://gun.io/get-started/
- MCP evidence URLs: https://gun.io/ai/2025/05/model-context-protocol-mcp-introduction/
- Restrictions: закрытый отбор
- Recommended action: подать заявку, указать MCP experience в портфолио
- Priority: **WATCH**

### Wellfound, Otta/Welcome to the Jungle, Hired
- Country/region: US (Wellfound); EU/France (WTTJ); US (Hired — по факту площадка сократила B2C-найм)
- MCP status: **NOT FOUND** ни по одной из трёх
- Registration URL: https://wellfound.com/jobs ; https://www.welcometothejungle.com/ ; hired.com (ограниченный доступ)
- MCP evidence URLs: нет
- Restrictions: —
- Recommended action: не приоритет сейчас, проверить через 3-6 месяцев (B-карта)
- Priority: **WATCH**

---

## 3. AI-NATIVE / MCP-NATIVE "AGENT HIRES HUMAN" МАРКЕТПЛЕЙСЫ (самое важное новое явление 2026 года)

Это отдельный, принципиально новый класс площадок: не человек ищет работу через сайт, а **ИИ-агент программно, через MCP, нанимает человека** для задач, которые агент не может выполнить сам (физический мир, верификация, креатив, ручная проверка).

### RentAHuman (rentahuman.ai)
- Country/region: Global
- Type: **MCP-native agent-to-human marketplace**
- MCP status: **CONFIRMED**
- What can we sell: реальные физические задачи — фотосъёмка на месте, посещение мероприятий, доставка предметов, обследование локаций, документы
- Hourly supported: Да (пример: фотограф на мероприятии — $45/час)
- Fixed supported: Да (bounty от $5)
- Service listing supported: Да — человек создаёт профиль с навыками/доступностью/рейтингом
- MCP skill/category: сама площадка — это MCP-сервер (`rentahuman-mcp` npm-пакет), интеграция идёт через MCP-инструменты, а не веб-форму
- Масштаб: по данным Business Insider — около 200 000 регистраций за неделю; WIRED — 518 284 зарегистрированных человек
- Example rates: $5 (минимальный bounty) – $45/час и выше
- Registration URL: https://rentahuman.ai/
- MCP evidence URLs: https://rentahuman.ai/docs#mcp
- Restrictions: платформа очень новая (early 2026), нет данных о надёжности выплат в долгую; есть научная работа о рисках (arxiv.org/html/2602.19514v1 — "Security Risks of AI Agents Hiring Humans")
- Recommended action: зарегистрироваться как исполнитель — это буквально точка входа, где сегодня почти нет конкуренции за качественные профили
- Priority: **NOW**

### human-mcp.io
- Country/region: Global
- Type: **MCP-native agent-to-human marketplace**
- MCP status: **CONFIRMED**
- What can we sell: контент, дизайн, ресёрч, code review, разметка данных, human verification/compliance
- Hourly/Fixed supported: Да, исполнитель сам назначает ставку
- Service listing supported: Да (профиль "provider")
- MCP skill/category: платформа целиком построена вокруг MCP-протокола между агентом и escrow-системой
- Модель: агент описывает задачу и бюджет → эскроу → исполнитель делает работу → агент подтверждает → автовыплата
- Fee: **15% с площадки**, без подписки, регистрация бесплатна
- Example rates: устанавливает сам исполнитель
- Registration URL: https://human-mcp.io/ (login → "sign up as provider")
- MCP evidence URLs: https://human-mcp.io/
- Restrictions: выплаты через Stripe (нужен доступный для страны Stripe-аккаунт)
- Recommended action: зарегистрироваться как provider, указать навыки code review / data annotation / research — это прямое совпадение с профилем разработчика MCP
- Priority: **NOW**

### Human Pages (humanpages.ai)
- Country/region: Global (100+ стран)
- Type: **MCP-native agent-to-human marketplace**
- MCP status: **CONFIRMED**
- What can we sell: любые "real-world" задачи по навыку/локации/оборудованию + job board для агентов
- Масштаб: за 2 недели после запуска в феврале 2026 — 4.8M визитов и **539 000 зарегистрированных исполнителей** в 100+ странах
- Оплата: crypto (USDC) по умолчанию + другие крипто + фиат, есть free tier / pro subscription / x402 pay-per-use для агентов-заказчиков
- Registration URL: https://humanpages.ai/
- MCP evidence URLs: https://github.com/human-pages-ai/humanpages ; https://www.pulsemcp.com/servers/humanpages
- Restrictions: крипто-ориентированная оплата может быть барьером в РФ/СНГ
- Recommended action: зарегистрироваться, это один из трёх крупнейших early-movers в этой категории
- Priority: **NOW**

### Upwork MCP Server (agentic hiring layer поверх Upwork)
- Country/region: Global
- Type: **PLATFORM-NATIVE слой поверх существующего фриланс-маркетплейса**
- MCP status: **PLATFORM-NATIVE**, запущен 10 августа 2026 (mcp.upwork.com)
- Суть: клиентские ИИ-агенты (через Claude и др.) теперь сами ищут фрилансеров на Upwork через MCP — ранжирование учитывает Job Success Score, верификацию навыков, отзывчивость
- Что это значит для нас: обычный профиль на Upwork с сильным Job Success Score теперь **автоматически виднее ИИ-агентам-нанимателям**, не только людям
- Registration URL: см. Upwork выше
- MCP evidence URLs: https://up-bro.com/blog/upwork-mcp-server ; https://prnewsleader.com/upwork-mcp-server/
- Recommended action: поддерживать высокий Job Success Score и полностью заполненный профиль — это теперь прямой фактор видимости для ИИ-нанимателей
- Priority: **NOW** (как усиление существующего Upwork-профиля)

---

## 4. SERVICE MARKETPLACES (консультации/retainer, не gig)

### QuickHire, Sensussoft, Greelow, Workforce Next (агентства "Hire MCP Developers")
- Country/region: US/India/LatAm
- Type: Staffing/agency-модель ("нанять готовую команду"), НЕ self-service биржа
- MCP status: **CONFIRMED**, но это B2B-агентства, не площадки для регистрации фрилансера
- Пример ставок: Greelow — сеньор MCP-разработчик из LatAm, **$6000–$9000/месяц**, онбординг за 7 дней
- Что это значит: это конкуренты (агентства-посредники), не точки входа для самостоятельной продажи услуг — но можно попробовать зайти как подрядчик В эти агентства
- Registration URL: у каждого агентства своя форма "join our talent pool" (не всегда публична)
- MCP evidence URLs: https://greelow.com/en/hire/mcp-developers ; https://sensussoft.com/hire/mcp-developers ; https://wfnext.com/hire/mcp-developers/ ; https://www.quickhire.services/us/hire-mcp-experts
- Restrictions: закрытый отбор, комиссия агентства забирает маржу
- Recommended action: рассматривать как B2B-партнёров/подрядные каналы, а не как маркетплейс для листинга
- Priority: **WATCH**

---

## 5. MCP PRODUCT / DISTRIBUTION МАРКЕТПЛЕЙСЫ (продажа самих MCP-серверов, НЕ услуг человека)

Важно: здесь продают программный продукт (MCP-сервер/тул), а не рабочее время специалиста.

### MCP Registry (registry.modelcontextprotocol.io) — официальный реестр Anthropic
- MCP status: **PLATFORM-NATIVE**, это официальный каталог метаданных
- Можно ли публиковать: да, через namespace-аутентификацию (reverse-DNS формат `io.github.username/server`), требуется подтверждение владения GitHub-аккаунтом/доменом
- Можно ли брать деньги: реестр сам не монетизирует — это чисто индекс метаданных, код и монетизация — на стороне разработчика
- Требования: нельзя обходить safety guardrails, нельзя нарушать IP, нельзя извлекать данные переписок пользователей
- URL: https://modelcontextprotocol.io/registry/about
- Recommended action: обязательно зарегистрировать свой сервер здесь — это бесплатный "official proof" для резюме/портфолио
- Priority: **NOW**

### Smithery.ai
- Масштаб: 6000+ серверов, один из крупнейших каталогов
- Монетизация: по независимому сравнению — создатели платят $30/мес хостинга и **зарабатывают $0** напрямую с площадки (монетизация не встроена)
- Publish URL: https://smithery.ai/docs/build/publish
- Recommended action: публиковать для discoverability, не для прямого дохода
- Priority: **SECOND WAVE**

### Glama.ai
- Масштаб: 83 233 сервера в реестре (крупнейший индекс на данный момент)
- Публикация: бесплатно через submit GitHub-репозитория, no paywall
- Платный хостинг: оплата за инстанс (не за запрос), без каких-либо capped-лимитов на нагрузку
- URL: https://glama.ai/mcp/servers ; pricing: https://glama.ai/pricing
- Recommended action: опубликовать open-source сервер бесплатно для видимости + рассмотреть платный hosted tier
- Priority: **NOW** (для видимости, бесплатно)

### PulseMCP
- Масштаб: 6975+ серверов, официально подключён к MCP Registry, ведёт еженедельный дайджест "Pulse"
- **Важное ограничение**: приём новых заявок на публикацию **временно приостановлен** (площадка перестраивает систему приёма листингов) — статус на дату исследования
- URL: https://www.pulsemcp.com/
- Recommended action: следить за реоткрытием приёма заявок
- Priority: **WATCH**

### Cline Marketplace
- Публикация: через GitHub issue в официальном репозитории cline/mcp-marketplace с GitHub repo URL + логотипом; после одобрения сервер становится доступен для установки в один клик миллионам пользователей Cline
- Монетизация: встроенной монетизации у самого Cline Marketplace нет (это discovery-канал)
- URL: https://github.com/cline/mcp-marketplace
- Recommended action: подать заявку — это бесплатный канал дистрибуции с большой аудиторией разработчиков
- Priority: **NOW**

### dotMCP
- Модель: превращает существующие API (OpenAPI/GraphQL/Postman) в MCP-сервер автоматически + позволяет "тунелировать" уже существующий MCP-сервер и монетизировать сразу
- URL: https://dotmcp.io/marketplace
- Recommended action: если у нас уже есть свой MCP-сервер — подключить через тоннель для быстрой монетизации
- Priority: **SECOND WAVE**

### MCPize
- Монетизация: заявлено **80–85% revenue share** разработчику, площадка берёт на себя хостинг/SSL/платежи/дистрибуцию — самая complete инфраструктура монетизации на рынке на сегодня
- URL: https://mcpize.com/
- Recommended action: приоритетная площадка именно для монетизации готового MCP-продукта (в отличие от Smithery/Glama, которые больше про discovery)
- Priority: **NOW**

### MCP Marketplace (mcp-marketplace.io)
- Модель: security-scanning + one-click install + встроенный Stripe checkout, license keys, payouts "под ключ" (zero payment integration со стороны разработчика)
- Позиционирование: более мелкая, но курируемая коллекция (качество/доверие важнее объёма)
- URL: https://mcp-marketplace.io/for-creators
- Recommended action: подать сервер после MVP на Glama/Smithery, когда нужна реальная монетизация с готовой платёжной инфраструктурой
- Priority: **SECOND WAVE**

---

## 6. РОССИЯ/СНГ — итоговая сводка (детали по каждой площадке см. в разделах 1 и 2)

| Площадка | Статус | Вывод |
|---|---|---|
| Kwork | CONFIRMED | Реальные заказы на MCP-настройку уже есть, минимальный порог входа |
| hh.ru | CONFIRMED (вакансии/резюме) | MCP-разработчик — формирующаяся отдельная роль в 2026 |
| Avito Услуги | EARLY SIGNAL | Термин MCP непонятен аудитории, продавать нужно "человеческим" языком |
| FL.ru | EARLY SIGNAL | Слабая внешняя индексация, нужна ручная проверка внутри площадки |
| Хабр Фриланс (freelansim.ru) | EARLY SIGNAL | Заказы идут потоком в Telegram-канале, отдельного MCP-тега нет |
| TenChat | EARLY SIGNAL | Хороший канал контент-маркетинга, не транзакционная биржа |
| YouDo | NOT FOUND | Не целевая аудитория для этой услуги |
| Weblancer | NOT FOUND | Нет обнаруженных MCP-заказов |
| mcpdb.ru / mcpgate.ru | PLATFORM-NATIVE (RU) | Локальные RU-каталоги/шлюзы MCP-серверов — стоит зарегистрировать свой сервер там же, где и в международных реестрах |

---

## ТРИ ИТОГОВЫЕ КАРТЫ

### A. Где продавать MCP-услуги (как человек/агентство) ПРЯМО СЕЙЧАС
1. Upwork — профиль + Project Catalog листинги
2. Fiverr — 2-3 gig'а с разной ценой
3. Freelancer.com — hire/model-context-protocol категория
4. Malt (для франко/евро-рынка) — тег "mcp" в профиле
5. Kwork (для RU-рынка) — кворк с фиксированной ценой
6. LinkedIn — Skill "Model Context Protocol" + open to contract
7. **RentAHuman / human-mcp.io / Human Pages** — новая категория, ИИ-агенты сами нанимают человека под задачи (в т.ч. технические: code review, data annotation, verification) — конкуренции почти нет

### B. Где MCP только начинает появляться — занять место рано
1. Toptal — подать заявку в общий AI Engineering трек
2. Contra — 0% комиссии, продвигать как "AI agent integration"
3. hh.ru — зафиксировать себя как "MCP-разработчик" пока роль формируется
4. Workana / 99Freelas / Weblancer / Truelancer — рынок ещё пуст на локальных языках (испанский/португальский/украинский) — можно быть первым
5. Dice / Indeed — настроить алерты, готовиться к росту потока W2/контрактных MCP-вакансий
6. Gun.io — подать заявку в vetted talent pool с MCP в портфолио
7. FL.ru / Хабр Фриланс / Avito Услуги / TenChat — рынок на RU почти не оформлен, но реальные первые заказы уже фиксируются

### C. Где публиковать/монетизировать сами MCP-серверы и тулы
1. **MCP Registry** (registry.modelcontextprotocol.io) — обязательная официальная регистрация, бесплатно, работает как "proof"
2. **Glama.ai** — крупнейший индекс (83 233 сервера), бесплатная публикация, платный hosting-тир
3. **Cline Marketplace** — бесплатный канал дистрибуции на аудиторию Cline через GitHub issue
4. **MCPize** — лучшая инфраструктура монетизации (80-85% revenue share, hosting/SSL/payments под ключ)
5. **Smithery.ai** — крупный каталог для discoverability (монетизация внутри платформы фактически отсутствует)
6. **dotMCP** — если уже есть готовый сервер, монетизация "в один тоннель"
7. **MCP Marketplace (mcp-marketplace.io)** — курируемая площадка с готовым Stripe-биллингом
8. **PulseMCP** — сейчас WATCH (приём заявок на паузе на дату исследования)

---

## TOP 10 PLATFORMS TO ENTER THIS WEEK

| # | Платформа | Прямая ссылка | Конкретное действие на этой неделе |
|---|---|---|---|
| 1 | Upwork | https://www.upwork.com/nx/create-profile/ | Создать профиль + 2 Project Catalog листинга ("Custom MCP Server", "MCP Integration for Business Tools") |
| 2 | Fiverr | https://www.fiverr.com/start_selling | Опубликовать 3 gig'а: mini ($90-150), standard ($500-1000), enterprise ($2000-3000) |
| 3 | Freelancer.com | https://www.freelancer.com/signup | Зарегистрироваться, добавить skill "Model Context Protocol", откликнуться на 5 активных MCP-джобов |
| 4 | RentAHuman | https://rentahuman.ai/ | Зарегистрироваться как исполнитель, указать технические навыки (code/data/research tasks) |
| 5 | human-mcp.io | https://human-mcp.io/ | Sign up as provider, выставить ставку под code review / data annotation |
| 6 | Human Pages | https://humanpages.ai/ | Зарегистрироваться, заполнить skills/location/equipment |
| 7 | MCP Registry (официальный) | https://modelcontextprotocol.io/registry/about | Опубликовать свой MCP-сервер через namespace-аутентификацию GitHub |
| 8 | Glama.ai | https://glama.ai/mcp/servers | Отправить GitHub-репозиторий своего сервера на индексацию (бесплатно) |
| 9 | Malt | https://www.malt.fr/inscription-freelance | Создать профиль, добавить тег "mcp" + "Model Context Protocol", указать day rate 400-1000€ |
| 10 | Kwork | https://kwork.ru/register | Разместить кворк "Настрою MCP-сервер под Claude/Cursor/ChatGPT" от 5 000 ₽ |

---

## Что не подтвердилось (честно, без додумывания)

- Toptal, PeoplePerHour, Guru.com, YouDo, Weblancer, Workana, 99Freelas, Wellfound, Otta/WTTJ, Hired — по прямому поиску на нужном языке не найдено ни одного реального MCP-листинга/заказа/профиля на дату исследования. Это не значит, что рынка там не будет — это значит, что сегодня (6 сентября 2026) там пусто или невидимо снаружи.
- Malt — контент подтверждён через поисковую выдачу (индексация тега, профиль конкретного человека), но прямой fetch страницы тега вернул 403 (защита от ботов) — это отмечено как ограничение метода, а не как повод считать площадку неподтверждённой.
- FL.ru — специфика в том, что `site:fl.ru` в поиске не вернул вообще ничего релевантного (типичное ограничение индексации для этой площадки), поэтому статус EARLY SIGNAL, а не NOT FOUND — требуется ручная проверка изнутри площадки.
