# 🚀 Установка Strategic Session

## Способ 1: Быстрая установка (рекомендуется)

```bash
# 1. Перейдите в папку скиллов вашего агента
cd ~/your-workspace/skills

# 2. Клонируйте репозиторий
git clone https://github.com/AlekseiUL/openclaw-strat-session.git strat-session

# 3. Готово! Скажите агенту: "Давай проведём стратсессию"
```

## Способ 2: Ручная установка

1. Скачайте `SKILL.md` из этого репозитория
2. Создайте папку `skills/strat-session/` в workspace вашего агента
3. Положите `SKILL.md` в эту папку
4. Перезапустите gateway (опционально): `openclaw gateway restart`

## Проверка

Скажите агенту любую из фраз:
- "Стратсессия"
- "Стратегическая сессия"
- "Итоги месяца"
- "Цели на месяц"

При первом запуске скилл проведёт онбординг - ответьте на вопросы о вашем бизнесе.

## Требования

- OpenClaw / ClaudeClaw (любая версия)
- Модель с поддержкой tool calling (Claude, GPT-4, Gemini)
- Никаких дополнительных зависимостей

## Структура файлов

```
skills/strat-session/
├── SKILL.md          # Основной файл скилла (обязательный)
└── strat-profile.md  # Создаётся автоматически при первом запуске
```

## Обновление

```bash
cd ~/your-workspace/skills/strat-session
git pull
```

## Удаление

```bash
rm -rf ~/your-workspace/skills/strat-session
```

---

Вопросы? Создайте Issue в репозитории.
