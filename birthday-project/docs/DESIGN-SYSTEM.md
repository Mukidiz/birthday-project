# 🎨 Design System

> **Last Updated:** 2026-01-16  
> **Primary Style:** Classic Watercolor (Option 1)

---

## 🎨 Color Palettes

### Option 1: Classic Watercolor (PRIMARY - Planning Skeleton)

```css
:root {
  /* Primary Colors */
  --color-cream: #FDF6E3;           /* רקע חמים - קרם */
  --color-sky-blue: #87CEEB;        /* כחול שמיים עדין */
  --color-butter-yellow: #F5E6A3;   /* צהוב חמאה רך */
  --color-sandy-beige: #D4C4A8;     /* בז' חולי */
  
  /* Accent Colors */
  --color-rose-red: #C94C4C;        /* אדום ורד - הדגשה */
  --color-deep-green: #2E5A4C;      /* ירוק עמוק - באובבים */
  --color-soft-brown: #8B7355;      /* חום רך */
  
  /* Text Colors */
  --color-text-dark: #3D3D3D;       /* טקסט ראשי */
  --color-text-light: #6B6B6B;      /* טקסט משני */
  
  /* Special */
  --color-star-gold: #FFD700;       /* זהב כוכבים */
}
```

### Option 2: Starry Night

```css
:root {
  --color-midnight: #0D1B2A;
  --color-deep-blue: #1B263B;
  --color-twilight: #415A77;
  --color-silver: #C0C0C0;
  --color-star-gold: #FFD700;
  --color-soft-white: #E8E8E8;
}
```

### Option 3: Desert Sunset

```css
:root {
  --color-warm-orange: #E07A5F;
  --color-sunset-pink: #D4A5A5;
  --color-twilight-purple: #9B72AA;
  --color-night-blue: #3D405B;
  --color-sand: #F2CC8F;
  --color-cream: #F4F1DE;
}
```

### Option 4: Soft Pastel

```css
:root {
  --color-baby-blue: #A8D5E5;
  --color-soft-pink: #F4B9B2;
  --color-mint: #B5EAD7;
  --color-lavender: #C7CEEA;
  --color-cream: #FFEFD5;
  --color-soft-yellow: #FFF5BA;
}
```

### Option 5: Modern Minimal

```css
:root {
  --color-white: #FFFFFF;
  --color-off-white: #FAFAFA;
  --color-black: #1A1A1A;
  --color-gray: #6B6B6B;
  --color-accent-gold: #C9A227;
  /* OR */
  --color-accent-rose: #E8A0BF;
}
```

---

## 🔤 Typography

### Font Choices (TBD - to explore)

**For Hebrew:**
- **Headings:** [להחליט - אולי פונט מעוצב]
- **Body:** [להחליט - קריא ונעים]

**Inspiration fonts:**
- Secular One (Hebrew display)
- Heebo (Hebrew body)
- Assistant (Hebrew clean)
- Karantina (Hebrew decorative)

### Font Scales

```css
--font-size-xs: 0.75rem;    /* 12px */
--font-size-sm: 0.875rem;   /* 14px */
--font-size-base: 1rem;     /* 16px */
--font-size-lg: 1.25rem;    /* 20px */
--font-size-xl: 1.5rem;     /* 24px */
--font-size-2xl: 2rem;      /* 32px */
--font-size-3xl: 2.5rem;    /* 40px */
--font-size-4xl: 3rem;      /* 48px */
```

---

## 📐 Spacing

```css
--space-1: 0.25rem;   /* 4px */
--space-2: 0.5rem;    /* 8px */
--space-3: 0.75rem;   /* 12px */
--space-4: 1rem;      /* 16px */
--space-5: 1.5rem;    /* 24px */
--space-6: 2rem;      /* 32px */
--space-8: 3rem;      /* 48px */
--space-10: 4rem;     /* 64px */
--space-12: 6rem;     /* 96px */
```

---

## 🧩 Components

### Page Structure
- **Header:** מינימלי, עם ניווט עדין
- **Content Area:** מרכזי, עם איורים משולבים
- **Navigation:** חיצים או כפתורים לעבור בין פרקים
- **Journey Map:** מפת מסע קבועה (אולי בצד או למטה)

### Animation Types (Planned)
- **Page Transitions:** מעבר עדין בין פרקים
- **Element Reveals:** אלמנטים מתגלים בהדרגה
- **Hover Effects:** תגובה עדינה לאינטראקציה
- **Decorative:** כוכבים מנצנצים, חללית נעה

---

## 🖼️ Illustration Style

### Guidelines
- **קו:** דק ורך, לא מושלם (hand-drawn feel)
- **מילוי:** צבעי מים עדינים, עם texture
- **סגנון:** ילדותי-מתוחכם כמו הנסיך הקטן המקורי
- **דמויות:** סטיליזציה של שני בני הזוג + חללית

### Required Illustrations (TBD)
- [ ] דמות 1 (המספר)
- [ ] דמות 2 (בן הזוג)
- [ ] חללית
- [ ] כוכבים/פלנטות לכל פרק
- [ ] איורים ספציפיים לאירועים

---

## 📱 Responsive Breakpoints

```css
--breakpoint-sm: 640px;
--breakpoint-md: 768px;
--breakpoint-lg: 1024px;
--breakpoint-xl: 1280px;
```

---

## 🎭 Mood & Tone

- **Feeling:** חם, נוסטלגי, משעשע, רומנטי
- **Atmosphere:** חלומי, כמו קריאת סיפור לפני השינה
- **Energy:** רגוע אך מעניין, עם רגעי הפתעה

