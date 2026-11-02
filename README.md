# Keepsake landing

Адаптивний односторінковий лендінг дизайн-агенції Keepsake (Lab 07, Task 4).

**Demo:** https://<your-username>.github.io/landing-keepsake/

## Технології та рішення
- Семантичний HTML5, один `h1`, інлайн-SVG спрайт іконок.
- CSS reset + CSS-змінні в `:root` (кольори, шрифти, відступи, розміри за брейкпоінтами).
- Mobile first: базові стилі для 375, `min-width: 768px`, `min-width: 1280px`; контейнер max 1100px.
- Flexbox для розкладки, CSS Grid для сітки робіт; `aspect-ratio` для карточок.
- Мобільне меню та фільтр портфоліо — без JS (`:checked ~`), ховер/фокус карточок, форма підписки через `:user-invalid` та `:target`.
- Шрифти: Oswald, Open Sans, Dancing Script (Google Fonts, `display=swap`).
