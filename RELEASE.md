# Релизы Tolfin

## Текущая версия: v1.0.0

## Как создать новый релиз

### 1. Внесите изменения
Сделайте все необходимые изменения в коде и отправьте их на Gitea:
```powershell
git add .
git commit -m "Описание изменений"
git push origin main
```

### 2. Создайте тег версии
```powershell
git tag -a v1.0.1 -m "Release v1.0.1 - Описание изменений"
git push origin v1.0.1
```

### 3. Создайте релиз на Gitea
1. Зайдите на https://git.tolchin.pro/Oleg/Tolfin/releases
2. Нажмите "New Release"
3. Выберите созданный тег (например, v1.0.1)
4. Заполните описание релиза
5. Нажмите "Publish Release"

## CDN URL

### Последняя версия (рекомендуется):
```css
@import url("https://git.tolchin.pro/Oleg/Tolfin/raw/branch/main/theme/tolfin.css");
```

### Конкретная версия:
```css
@import url("https://git.tolchin.pro/Oleg/Tolfin/raw/tag/v1.0.0/theme/tolfin.css");
```

## История релизов

### v1.0.0 (Текущая)
- Первая официальная версия
- Полная тема с баннером
- Все модули включены
- Удалена поддержка логотипов (только баннер)
- Перенос на Gitea
