---
title: LegasVex | проектный кейс
---

# LegasVex

**Проект:** система для работы с документами и источниками.  
**Статус:** в рабочем дереве есть API, локальный LLM client, Agent Council, workflow, audit и approval-компоненты. Дерево содержит локальные изменения и не является чистым release snapshot.

## Подтверждённые части проекта

- FastAPI routes и PostgreSQL storage code; SQLite применяется для локальной очереди/аудита.
- Ollama chat client и embedding helper.
- Agent Council с policy/orchestration и human approval компонентами.
- Workflow обработки обращений и audit.

## Моя функция

Я формулирую задачи и продуктовую логику, задаю направление AI-assisted delivery, веду итерации coding agents и проверяю результат. Наличие реализации в репозитории не означает, что я вручную написал код.

## Ограничения

Полный end-to-end RAG, MCP и отдельный исполняемый генератор Evidence Pack не подтверждены. Production deployment не подтверждён; в проектных материалах остаются человеческие release gates. Это отдельный продуктовый домен и не медицинская система, интеграция с МЕДСИ/МИС/ЭМК не обнаружена.
