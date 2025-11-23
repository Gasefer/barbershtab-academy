import { NuxtLink } from '../../../.nuxt/components';
<template>
  <header class="header">
    <div class="header__container">
      <a href="/" class="header__logo-link">
        <NuxtImg
          src="/images/logo.webp"
          alt="Barbershtab Logo"
          class="header__logo-img"
        />
      </a>

      <nav class="header__nav">
        <ul class="header__nav-list">
          <li class="header__nav-item">
            <a href="#courses" class="header__nav-link">Курси</a>
          </li>
          <li class="header__nav-item">
            <a href="#teachers" class="header__nav-link">Викладачі</a>
          </li>
        </ul>
      </nav>

      <div class="header__actions">
        <div class="header__socials">
          <a
            href="https://www.facebook.com/barbershtab"
            class="header__social-link"
            aria-label="Facebook"
          >
            <svg
              width="20"
              height="20"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              class="header__icon"
            >
              <path
                fill-rule="evenodd"
                d="M1.98 22.02c.63.63 1.49.98 2.38.98h15.28A3.36 3.36 0 0 0 23 19.64V4.36A3.36 3.36 0 0 0 19.64 1H4.36A3.36 3.36 0 0 0 1 4.36v15.28c0 .89.35 1.75.98 2.38Zm.85-2.38V4.36c0-.84.69-1.53 1.53-1.53h15.28c.84 0 1.53.69 1.53 1.53v15.28c0 .84-.69 1.53-1.53 1.53H4.36c-.84 0-1.53-.69-1.53-1.53Zm10.07-7.1V18h-2.13v-5.47H9V10.4h1.77V8.82C10.77 7 11.84 6 13.4 6c.53 0 1.06.03 1.59.08V8h-1.08c-.86 0-1.02.43-1.02 1.04v1.37h2.04l-.27 2.14H12.9Z"
                clip-rule="evenodd"
              ></path>
            </svg>
          </a>
          <a
            href="https://www.instagram.com/barber_shtab_lutsk/"
            class="header__social-link"
            aria-label="Instagram"
          >
            <svg
              width="20"
              height="20"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              class="header__icon"
            >
              <path
                fill-rule="evenodd"
                d="M21.117 2.844a5.618 5.618 0 0 1 1.267 1.945c.326.865.5 1.78.514 2.704.068 1.167.068 1.545.068 4.525 0 2.98-.016 3.352-.069 4.526a8.03 8.03 0 0 1-.51 2.666 5.626 5.626 0 0 1-3.212 3.212 8.067 8.067 0 0 1-2.667.51C15.343 23 14.962 23 11.983 23s-3.35-.016-4.525-.067a8.031 8.031 0 0 1-2.666-.549 5.623 5.623 0 0 1-3.213-3.21 8.044 8.044 0 0 1-.51-2.668C1 15.338 1 14.959 1 11.98c0-2.98.016-3.351.068-4.525.018-.911.191-1.813.511-2.666a5.61 5.61 0 0 1 3.212-3.21 7.994 7.994 0 0 1 2.664-.513C8.62 1 9.002 1 11.98 1c2.98 0 3.351.015 4.526.066a8.057 8.057 0 0 1 2.666.512c.73.282 1.392.714 1.945 1.266Zm-.598 15.63c.243-.659.371-1.355.38-2.058h.013c.052-1.165.052-1.485.052-4.456 0-2.973-.013-3.299-.066-4.459a6.196 6.196 0 0 0-.379-2.035 3.649 3.649 0 0 0-2.088-2.089 6.05 6.05 0 0 0-2.037-.379c-1.18-.067-1.485-.067-4.457-.067-2.973 0-3.299.015-4.459.067a6.111 6.111 0 0 0-2.036.38 3.643 3.643 0 0 0-2.096 2.088 6.145 6.145 0 0 0-.38 2.057c-.064 1.182-.064 1.486-.064 4.459 0 2.971.012 3.298.064 4.457.012.695.14 1.383.38 2.036a3.64 3.64 0 0 0 2.096 2.087 6.05 6.05 0 0 0 2.036.379c1.181.067 1.485.067 4.459.067 2.971 0 3.298-.013 4.457-.067a6.083 6.083 0 0 0 2.037-.38 3.644 3.644 0 0 0 2.088-2.086ZM17.838 7.44a1.315 1.315 0 1 0 0-2.63 1.315 1.315 0 0 0 0 2.63Zm-5.864-1.107a5.64 5.64 0 1 0 0 11.28 5.64 5.64 0 0 0 0-11.28Zm0 9.303a3.665 3.665 0 1 1 0-7.329 3.665 3.665 0 0 1 0 7.33Z"
                clip-rule="evenodd"
              ></path>
            </svg>
          </a>
          <a
            href="https://www.tiktok.com/@barber_shtab_lutsk"
            class="header__social-link"
            aria-label="TikTok"
          >
            <svg
              width="20"
              height="20"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              class="header__icon"
            >
              <path
                d="M18.7 5.7c-.16-.07-.3-.16-.44-.25a5.25 5.25 0 0 1-2.37-3.53c-.09-.56-.05-.92-.04-.92h-3.78v15.19l-.01.07v.04a3.2 3.2 0 0 1-3.18 2.96 3.2 3.2 0 0 1-3.19-3.2A3.2 3.2 0 0 1 9.86 13V9.15a7.02 7.02 0 0 0-7.02 3.58 6.91 6.91 0 0 0-.43 5.68v.01c.1.26.45 1.14 1.03 1.87.46.6 1.01 1.12 1.63 1.55v-.01h.01C6.91 23.09 8.94 23 8.94 23c.35-.02 1.53 0 2.86-.63a7.18 7.18 0 0 0 3.6-3.86c.33-.9.45-1.97.45-2.4V8.36l.66.43s.87.56 2.25.93c.98.26 2.3.31 2.3.31V6.28a4.9 4.9 0 0 1-2.37-.57Z"
              ></path>
            </svg>
          </a>
        </div>

        <NuxtLink to="tel:+380502133169" class="header__btn" type="button">
          <svg
            class="header__btn-icon"
            width="20"
            height="20"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path d="M13 2L3 14H12L11 22L21 10H12L13 2Z" fill="currentColor" />
          </svg>
          Записатися
        </NuxtLink>
      </div>
    </div>
  </header>
</template>
