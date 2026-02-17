# Tolfin Modules

Модули темы Tolfin для Jellyfin. Каждый модуль может использоваться отдельно или в сочетании с другими.

## Доступные модули

### static-sidebar.css
Делает боковую панель статичной (не прокручивается вместе со страницей) на десктопе.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/branch/main?ref=main/theme/modules/static-sidebar.css");
```

---

### central-libraries-small.css
Центрирует секцию "Мои медиа (small)" на главной странице.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/branch/main?ref=main/theme/modules/central-libraries-small.css");
```

---

### change-banner.css
Заменяет баннер Jellyfin на кастомный.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/branch/main?ref=main/theme/modules/change-banner.css");
```

---

### count-indicators.css
Изменяет цвет индикаторов счётчиков (количество эпизодов, и т.д.).

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/branch/main?ref=main/theme/modules/count-indicators.css");
```

---

### forgot-password.css
Убирает кнопку "Забыли пароль" со страницы входа.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/branch/main?ref=main/theme/modules/forgot-password.css");
```

---

### hide-my-media.css
Скрывает секцию "Мои медиа" с главной страницы Jellyfin.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/branch/main?ref=main/theme/modules/hide-my-media.css");
```

---

### moving-cards.css
Делает карточки Jellyfin немного приподнимающимися при наведении.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/branch/main?ref=main/theme/modules/moving-cards.css");
```

---

### smaller-cast.css
Делает карточки актёров меньше при просмотре деталей контента.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/branch/main?ref=main/theme/modules/smaller-cast.css");
```

---

### floating-progress.css
Делает прогресс-бары плавающими от низа карточки.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/branch/main?ref=main/theme/modules/floating-progress.css");
```

---

## Использование модулей

### Полная тема (все модули):
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/branch/main?ref=main/theme/complete.css");
```

### Индивидуальные модули:
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/branch/main?ref=main/theme/modules/static-sidebar.css");
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/branch/main?ref=main/theme/modules/central-libraries-small.css");
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/branch/main?ref=main/theme/modules/change-banner.css");
/* Добавляйте нужные модули */
```
