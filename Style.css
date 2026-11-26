
:root {
  --ink: #242126;
  --muted: #777078;
  --pink: #c62e59;
  --pink-dark: #a91f49;
  --pink-soft: #fff2f5;
  --pink-mid: #f8dfe6;
  --line: #f0e5e8;
  --white: #ffffff;
  --surface: #fffafb;
  --shadow: 0 18px 50px rgba(72, 30, 44, .07);
  --radius: 18px;
  --page: 1120px;
}

* { box-sizing: border-box; }
html { scroll-behavior: smooth; }

body {
  margin: 0;
  color: var(--ink);
  background: var(--white);
  font-family: "DM Sans", Arial, sans-serif;
  line-height: 1.6;
}

img { display: block; width: 100%; }
a { color: inherit; text-decoration: none; }
button { font: inherit; }

.page-wrap {
  width: min(var(--page), calc(100% - 64px));
  margin-inline: auto;
}

.skip-link {
  position: absolute;
  left: -9999px;
  top: 8px;
  z-index: 20;
  padding: 10px 14px;
  background: var(--ink);
  color: white;
  border-radius: 8px;
}

.skip-link:focus { left: 12px; }

.site-header {
  position: sticky;
  top: 0;
  z-index: 10;
  background: rgba(255,255,255,.94);
  border-bottom: 1px solid rgba(240,229,232,.85);
  backdrop-filter: blur(14px);
}

.header-inner {
  width: min(var(--page), calc(100% - 64px));
  min-height: 78px;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 24px;
}

.brand {
  font-family: Manrope, sans-serif;
  font-size: 27px;
  line-height: 1;
  font-weight: 800;
  letter-spacing: -1.8px;
}

.brand span { color: var(--pink); }

.primary-nav {
  display: flex;
  align-items: center;
  gap: 34px;
}

.nav-link {
  color: #5d565d;
  font-size: 13px;
  font-weight: 700;
  transition: color .2s ease;
}

.nav-link:hover,
.nav-link.active { color: var(--pink); }

.nav-follow {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  padding: 10px 16px;
  color: white;
  background: var(--pink);
  border-radius: 8px;
  font-size: 12px;
  font-weight: 700;
  transition: background .2s ease, transform .2s ease;
}

.nav-follow:hover,
.button-primary:hover {
  background: var(--pink-dark);
  transform: translateY(-2px);
}

.menu-toggle { display: none; }

.hero {
  display: grid;
  grid-template-columns: 1fr .92fr;
  align-items: center;
  gap: 58px;
  margin-top: 52px;
  padding: 56px 58px;
  min-height: 365px;
  overflow: hidden;
  border-radius: 24px;
  background: var(--pink-soft);
}

.eyebrow {
  margin: 0 0 12px;
  color: var(--pink);
  font-size: 9px;
  line-height: 1.4;
  letter-spacing: 1.5px;
  font-weight: 800;
}

h1, h2, h3, p { margin-top: 0; }
h1, h2, h3 { font-family: Manrope, sans-serif; }

.hero h1 {
  margin-bottom: 16px;
  font-size: clamp(36px, 4.5vw, 54px);
  line-height: 1.09;
  letter-spacing: -2.5px;
  font-weight: 800;
}

.hero h1 span { color: var(--pink); }

.hero-description {
  max-width: 370px;
  margin-bottom: 25px;
  color: var(--muted);
  font-size: 14px;
}

.button {
  display: inline-flex;
  align-items: center;
  gap: 18px;
  padding: 12px 17px;
  border-radius: 8px;
  font-size: 11px;
  font-weight: 800;
  transition: transform .2s ease, background .2s ease;
}

.button-primary {
  color: white;
  background: var(--pink);
}

.hero-art {
  position: relative;
  height: 250px;
}

.hero-art > img {
  height: 100%;
  object-fit: cover;
  border-radius: 15px;
  box-shadow: var(--shadow);
}

.hero-note {
  position: absolute;
  right: -17px;
  bottom: -18px;
  display: flex;
  align-items: center;
  gap: 12px;
  padding: 14px 18px;
  color: var(--ink);
  background: white;
  border: 1px solid var(--line);
  border-radius: 12px;
  box-shadow: var(--shadow);
  font-family: Manrope, sans-serif;
  font-size: 11px;
  font-weight: 800;
  line-height: 1.35;
}

.note-mark {
  color: var(--pink);
  font-size: 28px;
}

.featured-section { padding-top: 74px; }

.section-heading {
  display: flex;
  align-items: end;
  justify-content: space-between;
  gap: 20px;
  margin-bottom: 22px;
}

.section-heading .eyebrow { margin-bottom: 5px; }

.section-heading h2 {
  margin: 0;
  font-size: 25px;
  line-height: 1.2;
  letter-spacing: -.8px;
}

.text-link,
.read-link {
  color: var(--pink);
  font-size: 11px;
  font-weight: 800;
}

.text-link span,
.read-link span { margin-left: 5px; }

.content-layout {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 245px;
  gap: 24px;
}

.featured-card {
  display: grid;
  grid-template-columns: 48% 1fr;
  min-height: 245px;
  overflow: hidden;
  border: 1px solid var(--line);
  border-radius: var(--radius);
  background: white;
}

.image-link {
  min-height: 245px;
  overflow: hidden;
  background: var(--pink-mid);
}

.image-link img {
  height: 100%;
  object-fit: cover;
  transition: transform .5s ease;
}

.image-link:hover img,
.story-image:hover img { transform: scale(1.04); }

.featured-copy {
  align-self: center;
  padding: 28px;
}

.post-category {
  margin-bottom: 8px;
  color: var(--pink);
  font-size: 8px;
  letter-spacing: 1.1px;
  font-weight: 800;
}

.featured-copy h3 {
  margin-bottom: 10px;
  font-size: 21px;
  line-height: 1.25;
  letter-spacing: -.5px;
}

.featured-copy > p:not(.post-category) {
  margin-bottom: 16px;
  color: var(--muted);
  font-size: 12px;
}

.category-panel {
  padding: 23px;
  border-radius: var(--radius);
  background: var(--pink-soft);
}

.category-panel h3 {
  margin-bottom: 14px;
  font-size: 16px;
}

.category-button {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 10px 0;
  border: 0;
  border-bottom: 1px solid #f2dfe5;
  color: #71666d;
  background: transparent;
  text-align: left;
  font-size: 11px;
  cursor: pointer;
  transition: color .2s ease;
}

.category-button span {
  color: #a99ba1;
  font-size: 9px;
}

.category-button:hover,
.category-button.selected {
  color: var(--pink);
  font-weight: 800;
}

.category-social {
  display: flex;
  align-items: center;
  gap: 8px;
  margin-top: 20px;
  color: var(--muted);
  font-size: 9px;
}

.category-social span { margin-right: auto; }

.category-social a {
  display: grid;
  width: 25px;
  height: 25px;
  place-items: center;
  color: white;
  background: var(--pink);
  border-radius: 50%;
  font-size: 11px;
}

.latest-section {
  padding-top: 78px;
  padding-bottom: 76px;
}

.latest-heading { margin-bottom: 25px; }

.section-subtitle {
  margin: 0 0 2px;
  color: var(--muted);
  font-size: 11px;
}

.story-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 25px 22px;
}

.story-card {
  min-width: 0;
  overflow: hidden;
  border: 1px solid var(--line);
  border-radius: 14px;
  background: white;
  transition: transform .25s ease, box-shadow .25s ease;
}

.story-card:hover {
  transform: translateY(-4px);
  box-shadow: var(--shadow);
}

.story-image {
  display: block;
  height: 178px;
  overflow: hidden;
  background: var(--pink-mid);
}

.story-image img {
  height: 100%;
  object-fit: cover;
  transition: transform .5s ease;
}

.story-copy { padding: 19px 19px 20px; }

.story-copy h3 {
  margin-bottom: 8px;
  font-size: 16px;
  line-height: 1.3;
  letter-spacing: -.3px;
}

.story-copy > p:not(.post-category) {
  min-height: 42px;
  margin-bottom: 13px;
  color: var(--muted);
  font-size: 11px;
}

.empty-state {
  padding: 28px;
  color: var(--muted);
  background: var(--pink-soft);
  border-radius: 12px;
  text-align: center;
  font-size: 13px;
}

.about-strip {
  display: grid;
  grid-template-columns: 78px 1fr auto;
  align-items: center;
  gap: 24px;
  margin-bottom: 76px;
  padding: 30px 34px;
  border-radius: 18px;
  background: var(--pink-soft);
}

.about-symbol {
  display: grid;
  width: 66px;
  height: 66px;
  place-items: center;
  color: white;
  background: var(--pink);
  border-radius: 18px;
  font-family: Manrope, sans-serif;
  font-size: 35px;
  font-weight: 800;
  letter-spacing: -3px;
}

.about-symbol span { color: #ffdce5; }

.about-strip .eyebrow { margin-bottom: 5px; }

.about-strip h2 {
  margin-bottom: 5px;
  font-size: 21px;
  letter-spacing: -.6px;
}

.about-strip p:not(.eyebrow) {
  max-width: 580px;
  margin: 0;
  color: var(--muted);
  font-size: 11px;
}

.button-dark {
  color: white;
  background: var(--ink);
  white-space: nowrap;
}

.button-dark:hover {
  background: #494149;
  transform: translateY(-2px);
}

.site-footer {
  color: white;
  background: #211f22;
}

.footer-inner {
  min-height: 130px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 24px;
}

.footer-brand { color: white; }

.footer-inner p {
  margin: 8px 0 0;
  color: #c5bdc2;
  font-size: 11px;
}

.footer-right {
  display: flex;
  flex-direction: column;
  align-items: end;
  gap: 8px;
  color: #c5bdc2;
  font-size: 10px;
}

.footer-right a {
  color: white;
  font-weight: 700;
}

/* TABLET AND MOBILE RESPONSIVENESS */

@media (max-width: 800px) {
  .page-wrap,
  .header-inner {
    width: min(100% - 40px, 620px);
  }

  .header-inner { min-height: 68px; }

  .menu-toggle {
    width: 42px;
    height: 42px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 5px;
    border: 0;
    border-radius: 9px;
    background: var(--pink-soft);
    cursor: pointer;
  }

  .menu-toggle span {
    width: 18px;
    height: 2px;
    background: var(--ink);
    border-radius: 2px;
  }

  .primary-nav {
    position: absolute;
    top: 68px;
    left: 0;
    right: 0;
    display: none;
    flex-direction: column;
    align-items: stretch;
    gap: 0;
    padding: 10px 20px 18px;
    background: white;
    border-bottom: 1px solid var(--line);
    box-shadow: 0 12px 20px rgba(30,20,25,.06);
  }

  .primary-nav.open { display: flex; }

  .nav-link {
    padding: 12px 4px;
    border-bottom: 1px solid var(--line);
  }

  .nav-follow {
    justify-content: center;
    margin-top: 12px;
  }

  .hero {
    grid-template-columns: 1fr;
    gap: 28px;
    margin-top: 25px;
    padding: 34px 28px 38px;
  }

  .hero h1 { font-size: clamp(36px, 9vw, 48px); }

  .hero-art {
    height: 220px;
    margin-right: 8px;
  }

  .content-layout { grid-template-columns: 1fr; }

  .category-panel {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 0 18px;
  }

  .category-panel h3,
  .category-social { grid-column: 1 / -1; }

  .story-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .about-strip {
    grid-template-columns: 60px 1fr;
    padding: 24px;
  }

  .about-symbol {
    width: 54px;
    height: 54px;
    font-size: 29px;
  }

  .about-strip .button {
    grid-column: 2;
    justify-self: start;
  }
}

/* SMALL MOBILE SCREENS */

@media (max-width: 520px) {
  .page-wrap,
  .header-inner { width: calc(100% - 32px); }

  .brand { font-size: 25px; }

  .hero {
    padding: 30px 22px 34px;
    border-radius: 17px;
  }

  .hero h1 {
    font-size: 38px;
    letter-spacing: -1.8px;
  }

  .hero-description { font-size: 13px; }

  .hero-art { height: 190px; }

  .hero-note {
    right: -8px;
    bottom: -13px;
    padding: 11px 13px;
  }

  .featured-section,
  .latest-section { padding-top: 58px; }

  .section-heading {
    align-items: start;
  }

  .section-heading h2 { font-size: 22px; }

  .text-link {
    padding-top: 20px;
    white-space: nowrap;
    font-size: 10px;
  }

  .featured-card { grid-template-columns: 1fr; }

  .image-link {
    min-height: 190px;
    height: 190px;
  }

  .featured-copy { padding: 22px; }

  .category-panel { padding: 20px; }

  .latest-heading { display: block; }

  .section-subtitle { margin-top: 8px; }

  .story-grid {
    grid-template-columns: 1fr;
    gap: 17px;
  }

  .story-card {
    display: grid;
    grid-template-columns: 39% 1fr;
  }

  .story-image {
    height: 100%;
    min-height: 190px;
  }

  .story-copy { padding: 15px 14px; }

  .story-copy h3 { font-size: 14px; }

  .story-copy > p:not(.post-category) {
    min-height: 0;
    font-size: 10px;
  }

  .post-category { font-size: 7px; }

  .about-strip {
    grid-template-columns: 1fr;
    gap: 14px;
    margin-bottom: 55px;
    padding: 24px;
  }

  .about-strip .button { grid-column: 1; }

  .about-strip h2 { font-size: 19px; }

  .footer-inner {
    min-height: 145px;
    align-items: start;
    flex-direction: column;
    justify-content: center;
    gap: 18px;
    padding-block: 24px;
  }

  .footer-right { align-items: start; }
}

/* ACCESSIBILITY: REDUCED MOTION */

@media (prefers-reduced-motion: reduce) {
  *,
  *::before,
  *::after {
    scroll-behavior: auto !important;
    transition-duration: .01ms !important;
    animation-duration: .01ms !important;
    animation-iteration-count: 1 !important;
  }
}
