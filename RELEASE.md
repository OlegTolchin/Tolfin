# Релизы Tolfin

## Текущая версия: v1.0.0

## Как создать новый релиз

### 1. Внесите изменения
Сделайте все необходимые изменения в коде и отправьте их на GitHub:
```powershell
git add .
git commit -m "Описание изменений"
git push
```

### 2. Создайте тег версии
```powershell
git tag -a v1.0.1 -m "Release v1.0.1 - Описание изменений"
git push origin v1.0.1
```

### 3. Создайте релиз на GitHub
1. Зайдите на https://github.com/OlegTolchin/Tolfin/releases
2. Нажмите "Draft a new release"
3. Выберите созданный тег (например, v1.0.1)
4. Заполните описание релиза
5. Нажмите "Publish release"

## CDN URL

### Последняя версия (рекомендуется):
```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/tolfin.css");
```

### Конкретная версия:
```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@v1.0.0/theme/tolfin.css");
```

## История релизов

### v1.0.0 (Текущая)
- Первая официальная версия
- Полная тема с баннером
- Все модули включены
- Удалена поддержка логотипов (только баннер)
