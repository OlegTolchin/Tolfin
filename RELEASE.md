# Релизы Tolfin

## Текущая версия: v1.0.1

**Важно:** Ссылка `@latest` всегда указывает на **последний релиз**, а не на последний коммит. Все изменения оформляются как релизы.

## Как создать новый релиз

### 1. Внесите изменения
Сделайте все необходимые изменения в коде и отправьте их:
```powershell
git add .
git commit -m "Описание изменений"
git push
```

Это отправит изменения на GitHub и на Gitea одновременно.

### 2. Создайте тег версии
```powershell
git tag -a v1.0.1 -m "Release v1.0.1 - Описание изменений"
git push origin v1.0.1
git push gitea v1.0.1
```

### 3. Обновите тег latest
После создания релиза обновите тег `latest` чтобы он указывал на новый релиз:
```powershell
# Получите хеш нового релиза
git rev-list -n 1 v1.0.1

# Обновите тег latest (замените ХЕШ на полученный хеш)
git tag -f latest ХЕШ
git push origin latest --force
git push gitea latest --force
```

### 4. Создайте релиз на Gitea
1. Зайдите на https://gitea.tolchin.pro/Oleg/Tolfin/releases
2. Нажмите "New Release"
3. Выберите созданный тег (например, v1.0.1)
4. Заполните описание релиза
5. Нажмите "Publish Release"

## CDN URL

### Последняя версия (рекомендуется):
```css
@import url("https://gitea.tolchin.pro/Oleg/Tolfin/raw/branch/latest/theme/tolfin.css");
```

### Конкретная версия:
```css
@import url("https://gitea.tolchin.pro/Oleg/Tolfin/raw/tag/v1.0.0/theme/tolfin.css");
```

## История релизов

### v1.0.1 (Текущая)
- Обновлена тема tolfin.css
- Исправлена система релизов
- Ссылка @latest теперь указывает на последний релиз

### v1.0.0
- Первая официальная версия
- Полная тема с баннером
- Все модули включены
- Удалена поддержка логотипов (только баннер)
