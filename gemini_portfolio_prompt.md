# Промпт для Gemini: Оновлення портфоліо n1xyydev.site

## Контекст

Ти — веб-розробник, якому потрібно оновити секцію проектів у існуючому портфоліо на сайті `n1xyydev.site`.

Сайт написаний на **vanilla HTML/CSS/JS**, розміщений на Vercel. Зовнішній вигляд: термінальна естетика, темна тема, мінімалізм, монопросторовий шрифт. Стиль зберегти повністю — змінювати дозволено тільки секцію проектів `/* Active_Projects */`.

---

## Завдання

Замінити поточні 6 заглушок-проектів на **7 реальних проектів** з живими посиланнями, скріншотами і описами. Додати placeholder для скрінкасту до кожного проекту.

---

## Нові проекти (у цьому порядку)

### 1. МПМЕК — Розклад студента
- **Тип:** PWA + Telegram Bot
- **URL:** https://mpmek.site/
- **Бот:** https://t.me/mpmek_bot
- **Стек:** `PWA` `Vanilla JS` `Python` `PostgreSQL` `Redis` `Push Notifications`
- **Опис:** Безкоштовний PWA-додаток для студентів Могилів-Подільського коледжу. Розклад пар, заміни, домашні завдання, push-сповіщення щоранку. Синхронізація між пристроями. Telegram-бот як альтернатива. PBKDF2 + AES-256 шифрування.
- **Категорія:** EdTech / Real Product / Active Users

### 2. NexLearn — LMS платформа
- **Тип:** Fullstack Web App
- **URL:** https://nexlearn.space/
- **Стек:** `Next.js` `Node.js` `PostgreSQL` `REST API`
- **Опис:** Веб-орієнтована LMS для центрів підвищення кваліфікації. Управління курсами, автоматичне тестування і оцінювання, генерація сертифікатів. Комерційний продукт, переговори з університетами щодо впровадження.
- **Категорія:** EdTech / SaaS / B2B

### 3. CheckIt — AI валідатор бізнес-ідей
- **Тип:** AI SaaS / Fullstack
- **URL:** https://checkit-rho.vercel.app/
- **Стек:** `Next.js` `TypeScript` `TailwindCSS` `Framer Motion` `Mistral AI`
- **Опис:** AI-платформа для первинної оцінки стартап-ідей. Аналізує ринок, конкурентів, ризики і бізнес-модель за секунди. PDF-звіти, збереження проектів, публічні посилання. Пітч подавався на стартап-конкурс.
- **Категорія:** AI / SaaS / Startup Competition

### 4. ResumeAI — AI конструктор резюме
- **Тип:** AI SaaS / Fullstack
- **URL:** https://resume-ai-two-sigma.vercel.app/
- **Стек:** `Next.js` `TypeScript` `AI Integration` `PDF Export`
- **Опис:** AI-конструктор резюме з оптимізацією під ATS-системи. Адаптація під конкретну вакансію, генерація супровідних листів, 10+ мов. Freemium модель ($12/міс Pro, $25/міс Premium).
- **Категорія:** AI / SaaS / HR Tech

### 5. DevToolKit — Інструменти розробника
- **Тип:** PWA + Telegram Mini App
- **URL:** https://dev-tool-kit-seven.vercel.app/
- **Бот/МА:** https://t.me/DevToolsKit_Bot
- **Стек:** `PWA` `Vanilla JS` `Telegram Mini App API`
- **Опис:** Набір утиліт для розробників: Color Picker, CSS Generator, JSON Formatter, Pomodoro таймер. Працює як PWA у браузері і як Telegram Mini App. Оффлайн режим.
- **Категорія:** Developer Tools / PWA / Telegram Mini App

### 6. GreeceTravel — Лендинг для паломницьких поїздок
- **Тип:** Landing Page
- **URL:** https://greecetravel.vercel.app/
- **Стек:** `HTML` `CSS` `JavaScript` `Vercel`
- **Опис:** Лендинг під ключ для організатора паломницьких поїздок Україна→Греція. Маршрут, FAQ, форма бронювання, підрахунок вільних місць. SEO-оптимізований. Реальний клієнт, реальні поїздки.
- **Категорія:** Landing Page / Client Work

### 7. Libify — Читалка книг
- **Тип:** PWA
- **URL:** https://libify.store/
- **Стек:** `PWA` `Vanilla JS` `FB2` `PDF` `Flibusta API`
- **Опис:** PWA-читалка книг з доступом до тисяч творів. Підтримка FB2 і PDF форматів, офлайн режим, нічна тема, особиста бібліотека. Встановлюється на екран як нативний застосунок.
- **Категорія:** PWA / Consumer App

---

## Структура картки кожного проекту (HTML)

Кожна картка повинна містити:

```html
<div class="project-card" id="project-mpmek">
  <!-- 1. Заголовок і тип -->
  <div class="project-header">
    <span class="project-number">// 01</span>
    <h3 class="project-title">МПМЕК — Розклад студента</h3>
    <span class="project-type">PWA + Telegram Bot</span>
  </div>

  <!-- 2. PLACEHOLDER ДЛЯ СКРІНКАСТУ/СКРІНШОТУ -->
  <!-- ВАЖЛИВО: залишити як є, власник сайту сам вставить медіа -->
  <div class="project-media">
    <div class="media-placeholder" data-project="mpmek">
      <span class="placeholder-icon">[▶]</span>
      <span class="placeholder-text">// screencast_placeholder</span>
      <!-- Replace this div with <video> or <img> tag -->
    </div>
  </div>

  <!-- 3. Опис -->
  <p class="project-desc">
    Безкоштовний PWA-додаток для студентів коледжу. Розклад, заміни, домашні завдання, push-сповіщення. Синхронізація між пристроями. Реальні користувачі.
  </p>

  <!-- 4. Стек теги -->
  <div class="project-stack">
    <span>PWA</span>
    <span>Vanilla JS</span>
    <span>Python</span>
    <span>PostgreSQL</span>
  </div>

  <!-- 5. Посилання -->
  <div class="project-links">
    <a href="https://mpmek.site/" target="_blank" class="link-live">[ Live ]</a>
    <a href="https://t.me/mpmek_bot" target="_blank" class="link-bot">[ Bot ]</a>
    <a href="https://github.com/nazarn1xyy/mpmek" target="_blank" class="link-github">[ GitHub ]</a>
  </div>
</div>
```

---

## CSS для нових елементів

Додай до існуючого CSS (не ламаючи поточні стилі):

```css
/* Project Cards */
.project-card {
  border: 1px solid #333;
  padding: 24px;
  margin-bottom: 24px;
  position: relative;
  transition: border-color 0.2s;
}

.project-card:hover {
  border-color: #00ff41; /* зелений термінальний */
}

.project-number {
  font-size: 11px;
  color: #555;
  font-family: monospace;
  display: block;
  margin-bottom: 4px;
}

.project-type {
  font-size: 11px;
  color: #00ff41;
  border: 1px solid #00ff41;
  padding: 2px 8px;
  font-family: monospace;
  margin-left: 12px;
}

/* Media placeholder */
.media-placeholder {
  background: #0a0a0a;
  border: 1px dashed #333;
  height: 200px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin: 16px 0;
  cursor: pointer;
  font-family: monospace;
  color: #444;
}

.media-placeholder:hover {
  border-color: #555;
  color: #666;
}

.placeholder-icon {
  font-size: 24px;
  margin-bottom: 8px;
}

.placeholder-text {
  font-size: 12px;
}

/* Stack tags */
.project-stack {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 12px 0;
}

.project-stack span {
  font-size: 11px;
  font-family: monospace;
  color: #888;
  border: 1px solid #333;
  padding: 2px 8px;
}

/* Links */
.project-links {
  display: flex;
  gap: 12px;
  margin-top: 16px;
}

.project-links a {
  font-family: monospace;
  font-size: 12px;
  text-decoration: none;
  padding: 4px 0;
}

.link-live { color: #00ff41; }
.link-bot { color: #4af; }
.link-github { color: #888; }

.project-links a:hover {
  text-decoration: underline;
}
```

---

## Що НЕ чіпати

- Навбар (About, Tech Stack, Projects, Contact)
- Секцію `/* Tech_Stack */`
- Секцію `/* Initialize_Connection */` (контакти)
- Загальний кольоровий стиль сайту
- Шрифти
- Hero секцію з кодовим блоком

---

## Додаткові виправлення (обов'язково!)

1. **Змінити CTA кнопку** в секції `Initialize_Connection`:
   - ❌ Було: `[ Send Protocol ]`
   - ✅ Стало: `[ Написати в Telegram ]` → посилання: `https://t.me/sadbillionaire`

2. **Додати ім'я в hero-секцію** (замість "Software Engineer"):
   - У об'єкті `developer` замінити `name: "Software Engineer"` на `name: "Nazar / n1xyy"`

3. **Упорядкувати проекти за категоріями** з коментарями:
   ```html
   <!-- // EdTech -->
   <!-- // AI SaaS -->
   <!-- // Tools & PWA -->
   <!-- // Client Work -->
   ```

---

## Порядок проектів у сетці

1. МПМЕК (EdTech, реальні юзери — найсильніший кейс)
2. NexLearn (EdTech, B2B)
3. CheckIt (AI SaaS)
4. ResumeAI (AI SaaS)
5. DevToolKit (Tools)
6. GreeceTravel (Client Work)
7. Libify (PWA Consumer)

---

## Placeholder для скрінкасту — інструкція власнику

Після того як Gemini зробить зміни, щоб замінити placeholder на реальний скрінкаст:

```html
<!-- Замінити .media-placeholder на: -->
<video autoplay muted loop playsinline class="project-video">
  <source src="/assets/screencast-mpmek.mp4" type="video/mp4">
</video>

<!-- АБО для статичного скріншоту: -->
<img src="/assets/screenshot-mpmek.png" alt="МПМЕК скріншот" class="project-screenshot">
```

CSS для відео/скріншота:
```css
.project-video,
.project-screenshot {
  width: 100%;
  height: 200px;
  object-fit: cover;
  display: block;
  margin: 16px 0;
}
```

---

## Фінальна перевірка (Gemini, зроби сам)

Після всіх змін перевір:
- [ ] Всі 7 проектів є в HTML
- [ ] Кожен проект має `media-placeholder` з коментарем
- [ ] Кожен проект має живе посилання `[ Live ]`
- [ ] Боти (МПМЕК, DevToolKit) мають посилання `[ Bot ]`
- [ ] Стек теги у кожній картці
- [ ] CTA кнопка змінена на "Написати в Telegram"
- [ ] Ім'я в hero змінене
- [ ] Мобільна адаптація не зламана
