# heurema

> Craft, not conjuring. Ремесло, а не магия.

**heurema** — open-source инструменты и методология для безопасной AI-native разработки: от бизнес-намерения до проверенного изменения кода.

Мы не делаем ставку на “ещё один AI coding tool”. Мы строим слой, который делает работу AI-агентов ограниченной, проверяемой, аудируемой и переносимой между вендорами.

## Что мы строим

| Направление | Зачем |
|---|---|
| **Goalrail** | Contract-first операционный слой для AI-assisted delivery: intent -> contract -> work item -> evidence. |
| **Signum** | Risk-adaptive pipeline для ограниченных AI-assisted изменений и adversarial review. |
| **Proofpack** | CI-gate, где изменение несёт proof: тесты, проверки, review evidence. |
| **Arbiter** | Multi-model review/orchestration: спросить, реализовать, проверить, сравнить. |
| **Nex / Emporium** | Local-first распространение agent tools между developer runtimes. |
| **Field guides** | Практические playbooks для внедрения AI-агентов без потери контроля. |

## Принципы

1. **Discovery before automation.** Сначала понять работу, потом автоматизировать.
2. **Accountability is not delegatable.** Агент исполняет, человек отвечает.
3. **Context is a product.** Контекст нужно проектировать, версионировать и ограничивать.
4. **Boundaries beat prompts.** Ограничения важнее красивых промптов.
5. **Tests are contracts.** Без проверок нет доверия.
6. **Silent autonomy is a defect.** Нет audit trail — нет надёжной работы.
7. **Security gates before scale.** Нельзя ускорять то, что небезопасно.
8. **Vendor-neutral by design.** Процесс не должен зависеть от одного LLM/IDE/cloud.
9. **Local-first where it matters.** Чувствительный код и данные должны оставаться в контролируемой границе.
10. **No magic claims.** Меряем proof, rework, defects, cost и delivery impact.

## Для команд разработки

Если команда уже использует Cursor, Copilot, Claude Code, Codex или локальные модели, но delivery всё ещё хаотичный — обычно не хватает не модели, а системы:

- понятный intake;
- delivery contracts;
- agent-ready context packages;
- human approval gates;
- security/dependency checks;
- test evidence;
- review evidence;
- rollback и learning loop.

Первый workflow должен быть узким: агент может подготовить план, PR, тесты или review, но не должен сам merge’ить, деплоить или трогать production secrets.
