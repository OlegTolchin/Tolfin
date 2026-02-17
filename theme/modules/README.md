# Tolfin Modules

Модули темы Tolfin для Jellyfin. Каждый модуль может использоваться отдельно или в сочетании с другими.

## Доступные модули

### static-sidebar.css
Делает боковую панель статичной (не прокручивается вместе со страницей) на десктопе.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/theme/modules/static-sidebar.css?ref=main");
```

---

### central-libraries-small.css
Центрирует секцию "Мои медиа (small)" на главной странице.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/theme/modules/central-libraries-small.css?ref=main");
```

---

### change-banner.css
Заменяет баннер Jellyfin на кастомный.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/theme/modules/change-banner.css?ref=main");
```

---

### count-indicators.css
Изменяет цвет индикаторов счётчиков (количество эпизодов, и т.д.).

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/theme/modules/count-indicators.css?ref=main");
```

---

### forgot-password.css
Убирает кнопку "Забыли пароль" со страницы входа.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/theme/modules/forgot-password.css?ref=main");
```

---

### hide-my-media.css
Скрывает секцию "Мои медиа" с главной страницы Jellyfin.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/theme/modules/hide-my-media.css?ref=main");
```

---

### moving-cards.css
Делает карточки Jellyfin немного приподнимающимися при наведении.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/theme/modules/moving-cards.css?ref=main");
```

---

### smaller-cast.css
Делает карточки актёров меньше при просмотре деталей контента.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/theme/modules/smaller-cast.css?ref=main");
```

---

### floating-progress.css
Делает прогресс-бары плавающими от низа карточки.

**Использование:**
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/theme/modules/floating-progress.css?ref=main");
```

---

## Использование модулей

### Полная тема (все модули):
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/theme/complete.css?ref=main");
```

### Индивидуальные модули:
```css
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/theme/modules/static-sidebar.css?ref=main");
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/theme/modules/central-libraries-small.css?ref=main");
@import url("https://git.tolchin.pro/api/v1/repos/Oleg/Tolfin/raw/theme/modules/change-banner.css?ref=main");
/* Добавляйте нужные модули */
```
