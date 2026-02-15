# Tolfin Modules

Модули темы Tolfin для Jellyfin. Каждый модуль может использоваться отдельно или в сочетании с другими.

## Доступные модули

### static-sidebar.css
Делает боковую панель статичной (не прокручивается вместе со страницей) на десктопе.

**Использование:**
```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/modules/static-sidebar.css");
```

---

### central-libraries-small.css
Центрирует секцию "Мои медиа (small)" на главной странице.

**Использование:**
```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/modules/central-libraries-small.css");
```

---

### change-logo.css
Заменяет логотип Jellyfin на кастомный.

**Использование:**
```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/modules/change-logo.css");
```

---

### count-indicators.css
Изменяет цвет индикаторов счётчиков (количество эпизодов, и т.д.).

**Использование:**
```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/modules/count-indicators.css");
```

---

### forgot-password.css
Убирает кнопку "Забыли пароль" со страницы входа.

**Использование:**
```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/modules/forgot-password.css");
```

---

### hide-my-media.css
Скрывает секцию "Мои медиа" с главной страницы Jellyfin.

**Использование:**
```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/modules/hide-my-media.css");
```

---

### moving-cards.css
Делает карточки Jellyfin немного приподнимающимися при наведении.

**Использование:**
```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/modules/moving-cards.css");
```

---

### smaller-cast.css
Делает карточки актёров меньше при просмотре деталей контента.

**Использование:**
```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/modules/smaller-cast.css");
```

---

### floating-progress.css
Делает прогресс-бары плавающими от низа карточки.

**Использование:**
```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/modules/floating-progress.css");
```

---

## Использование модулей

### С базовой темой:
```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/base.css");
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/modules/static-sidebar.css");
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/modules/change-logo.css");
```

### Полная тема (все модули):
```css
@import url("https://cdn.jsdelivr.net/gh/OlegTolchin/Tolfin@latest/theme/complete.css");
```
