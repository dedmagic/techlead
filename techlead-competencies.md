# Карта компетенций техлида

Перечень технических компетенций (технологии/инструменты/библиотеки/языки/т.п.), которыми обязан владеть фронтовой техлид. Подразделяется на две категории: те, которые в любом случае будут использованы на проекте, и те, которые могут использоваться, а могут не использоваться, и решение по этому поводу тоже ложится на техлида.

Компентенции, в описании которых присутствует слово "выбор", подразумевают, что техлид ориентируется во всех перечисленных вариантах и может выбрать релевантный проекту/команде.

### Технологии/инструменты, обязательные к применению на проекте

* Prettier
* ESLint
* инструмент CI: Jenkins или Azure DevOps, выбор находится вне зоны ответственности техлида (или нет?)
* выбор языка:
    * JavaScript
    * TypeScript
* выбор менеджера состояния:
    * Redux
    * MobX
    * Effector
* выбор сборщика:
    * Webpack
    * Vite
    * Rollup
    * ...

### Опциональные технологии/инструменты

* выбор способа организации CSS:
    * методология BEM
    * CSS modules
    * styled components
    * CSS-in-JS
    * ...
* выбор CSS-фреймворка:
    * Tailwind
    * Bootstrap
    * Ant Design
    * ...
* выбор архитектуры:
    * FSD
    * Atomic Design
    * ...
* Swagger
* выбор тестового фреймворка (юнит-тестирование):
    * Jest
    * Jasmine
    * Vitest
    * ...
* выбор инструмента UI-тестирования:
    * Cypress
    * Playwright
    * Puppeteer
    * ...
* использование контейнеризации для деплоя приложения (Docker)
* выбор инструмента мониторинга:
    * Sentry
    * BugSnag
    * ...
* БЕЗОПАСНОСТЬ (тут бы расписать: CORS, XSS и прочие страшные буквы...)