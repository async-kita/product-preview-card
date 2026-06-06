# Frontend Mentor - Product preview card component solution

Это решение для [челленджа Product preview card component на Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Задачи Frontend Mentor помогают улучшать навыки вёрстки через реалистичные проекты.

## Обзор

### Задача

Пользователи должны уметь:

- Видеть оптимальный макет в зависимости от размера экрана устройства
- Видеть состояния hover и focus для интерактивных элементов

### Скриншот

![](./screenshot.png)

### Ссылки

- Репозиторий: [GitHub репозиторий](https://github.com/async-kita/product-preview-card)
- Живой сайт: [GitHub Pages](https://async-kita.github.io/product-preview-card/)

## Мои наработки

### Использованные технологии

- Семантическая HTML5 разметка
- CSS-переменные (`custom properties`)
- Flexbox
- CSS Grid
- Адаптивный дизайн (mobile-first подход)
- Технология `picture` с разными изображениями для десктопа и мобильных
- БЭМ-именование классов

### Чему я научился

Работая над этим проектом, я:

- Улучшил понимание работы `clamp()` для резиновой ширины карточки.
- Научился использовать `object-fit: cover` для адаптивных изображений.
- Закрепил навык работы с псевдоклассами `:hover`, `:focus-visible`, `:active`.
- Познакомился с системой типографики через утилитарные классы (`.text-1` … `.text-5`).

Пример кода, которым горжусь (адаптивная сетка карточки):

```css
.product-card {
  display: grid;
  width: clamp(21.875rem, 6.966rem + 63.613vw, 37.5rem);
  background-color: var(--white);
  border-radius: var(--radius);
}

@media (min-width: 768px) {
  .product-card {
    grid-template-columns: repeat(2, 1fr);
  }
}

###Планынадальнейшееразвитие

В следующих проектах хочу: - Глубже изучить доступность (ARIA, семантику, навигацию с клавиатуры).
- Освоить препроцессоры (SCSS) для более удобной работы со стилями.
- Добавлять плавные анимации не только на кнопку, но и на карточку целиком.

## Автор

- Frontend Mentor - [@async-kita](https://www.frontendmentor.io/profile/async-kita)

## Благоданости

Спасибо сообществу Frontend Mentor за вдохновение и примеры решений. Отдельное спасибо разработчикам, которые делятся своими подходами к БЭМ и адаптивной вёрстке.;
```
