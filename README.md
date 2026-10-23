# Сергей

Бэкенд-разработчик из Петербурга. Больше 3,5 лет в коммерческой разработке, работал в СберТехе и Т-Банке, в основном над бэкендом финансовых систем: расчёты, платежи, учёт, интеграции. Там привык, что цифры должны сходиться до копейки, а любое изменение проверяется до выкладки.

Основной стек — Java, Spring и PostgreSQL. Ещё пишу на Python, Go, C++ и TypeScript, работаю с 1С:Предприятием.

Веду небольшую студию **Flovant**: сайты, Telegram-боты, парсеры и сервисы для малого бизнеса.

## Деньги и учёт

- [LedgerCore](https://github.com/sunix2131/ledgercore) — учёт по двойной записи: сбалансированные проводки, сторнирование, защита от повторной записи. Java, PostgreSQL.
- [EventRelay](https://github.com/sunix2131/eventrelay) — доставка изменений из базы в Kafka через transactional outbox, с повторными попытками и защитой от дублей у получателя. Java.
- [PayMatch](https://github.com/sunix2131/paymatch) — сверка платежей с банковской выпиской: что совпало, что нет, что нужно проверить руками. Python.
- [LoanPlan](https://github.com/sunix2131/loanplan) — графики кредита и досрочные погашения в целых копейках, без ошибок округления. Библиотека и консольная утилита на C++.

## Обмен с 1С

Проверяют файлы до загрузки, работающая 1С не нужна.

- [BankGuard](https://github.com/sunix2131/bankguard) — банковская выписка: дубли документов, даты проводок вне периода, сходятся ли остатки и обороты. Python.
- [CatalogLint](https://github.com/sunix2131/cataloglint) — выгрузка CommerceML: товары без цен, битые ссылки, отрицательные остатки, внезапно пропавшие из каталога позиции. Python.

## Утилиты

- [DropOnce](https://github.com/sunix2131/droponce) — передача файлов по ссылкам с ограниченным сроком жизни: по локальной сети, через промежуточный сервер или зашифрованным соединением. Go, React.
- [FileSweep](https://github.com/sunix2131/filesweep) — поиск дублей и больших файлов, план перемещения до того, как что-то тронуть, и откат уже сделанного. Go, React.
- [ArxivDesk](https://github.com/sunix2131/arxivdesk) — читалка arXiv с поиском, заметками и историей. TypeScript.
- [LinkLater](https://github.com/sunix2131/linklater) — сохранённые ссылки с заметками и напоминаниями. Python, SQLite.
- [LeadMap](https://github.com/sunix2131/leadmap) — сбор открытых карточек компаний и небольшая CRM для работы с ними. Python, FastAPI, React.

## Код закрыт, но проекты есть

- **Tetrat** — сервис для рукописного плоттера на ESP32 с GRBL: текст превращается в почерк, плоттер пишет ручкой по тетрадному листу. Управление станком прямо из Chrome через Web Serial, подписка с пробным периодом.
- **netbank** — реестр операций, в котором оператор не может провести платёж без подписи клиента: подписи Ed25519, Merkle-доказательства, узлы-свидетели перепроверяют каждый блок. C++, Docker Compose.
- **Расчётный модуль по кредитным договорам** — перенос начислений из хранимой процедуры MSSQL в Python, со сверкой со старым расчётом по каждому договору.
- **Ironworks** — заводская стратегия для iPhone и iPad на Swift и SpriteKit.
- **Парсер малого бизнеса** — открытые реестры, карты и сайты компаний, склейка дублей, оценка карточек по полноте контактов.

К прежнему аккаунту на GitHub я потерял доступ, поэтому завёл этот и восстанавливаю здесь личные проекты. Код работодателей в эти репозитории не входит.

Заказы принимаю на [Kwork](https://kwork.ru/user/skydipper2708).

---

## In English

Backend developer based in Saint Petersburg with 3.5+ years of commercial experience, including SberTech and T-Bank, mostly on the backend of financial systems. Main stack: Java, Spring, PostgreSQL. I also write Python, Go, C++ and TypeScript and work with 1C:Enterprise. I run Flovant, a small studio building websites, bots and services for small businesses.

The repositories above are personal projects, not employer code.
