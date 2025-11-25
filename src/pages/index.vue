<template>
  <div class="page-wrapper">
    <main class="main-content">
      <section class="hero-section">
        <div class="hero-section__overlay"></div>
        <div class="hero-section__content">
          <!-- <img
            src="/images/barbershtab-logo.png"
            alt="Barbershtab Academy Logo"
            class="hero-section__logo"
          /> -->
          <h1 class="hero-section__title">BARBERSHTAB</h1>
          <p class="hero-section__subtitle">ACADEMY</p>
          <p class="hero-section__description">
            НАВЧАЙСЯ БАРБЕРИНГУ З НУЛЯ ТА ПІДВИЩУЙ КВАЛІФІКАЦІЮ
          </p>
          <p class="hero-section__tagline">
            ОБЕРИ СВІЙ ШЛЯХ. ЗАПИШИСЬ НА ЗАНЯТТЯ У СФЕРІ БАРБЕРИНГУ!
          </p>
        </div>
      </section>

      <section id="courses" class="courses-section">
        <h2 class="teachers-section__title">Курси</h2>

        <div class="courses-section__grid">
          <article class="course-card">
            <div class="course-card__header">
              <!-- <img
                src="/images/course-barber-from-scratch.jpg"
                alt="Барбер з нуля"
                class="course-card__image"
              /> -->
              <h3 class="course-card__title">
                Індивідуальний курс “Барбер з нуля”
              </h3>
              <div class="course-card__image-wrapper">
                <NuxtImg
                  src="/images/course1.webp"
                  alt="Course 1"
                  class="course-card__image"
                />
              </div>
            </div>
            <div class="course-card__body">
              <p class="course-card__text">
                Курс включає в себе таку інформацію:
              </p>
              <ul class="course-card__list">
                <li class="course-card__list-item">
                  Професія барбер, етика та комунікація з клієнтом. Сервіс в
                  барбершопі
                </li>
                <li class="course-card__list-item">
                  Інструменти та обладнання, догляд за ним
                </li>
                <li class="course-card__list-item">
                  Типи та види чоловічих стрижок, підбір форми
                </li>
                <li class="course-card__list-item">
                  Види фейду, їх застосування
                </li>
                <li class="course-card__list-item">
                  Техніка виконання подовжених стрижок
                </li>
                <li class="course-card__list-item">
                  Укладання волосся різними засобами (Пасти, помади, воски та
                  інші)
                </li>
                <li class="course-card__list-item">
                  Техніки стрижки бороди, догляд за бородою
                </li>
                <li class="course-card__list-item">
                  Техніки традиційного гоління, розпарювання та гоління
                  небезпечною бритвою
                </li>
                <li class="course-card__list-item">
                  Воскова депіляція та камуфляж сивини
                </li>
              </ul>
              <p class="course-card__text">
                Тривалість повного курсу 26 занять.
              </p>
              <p class="course-card__text">
                Тривалість одного заняття 2-3 години.
              </p>
              <p class="course-card__text">
                Цей курс забезпечить вам всебічні знання та практичні навички,
                необхідні для успішної роботи в барбершопі, включаючи всі
                основи, від технік стрижки до догляду за волоссям та розвитку
                кар’єри.
              </p>
              <p class="course-card__text">
                Після успішного проходження курсу видаємо сертифікат.
              </p>
              <p class="course-card__price">Вартість: 20 000 грн</p>
            </div>
          </article>

          <article class="course-card">
            <div class="course-card__header">
              <!-- <img
                src="/images/course-advanced.jpg"
                alt="Підвищення кваліфікації"
                class="course-card__image"
              /> -->
              <h3 class="course-card__title">
                Індивідуальний курс “Підвищення кваліфікації барбера”
              </h3>
              <div class="course-card__image-wrapper">
                <NuxtImg
                  src="/images/course2.webp"
                  alt="Course 2"
                  class="course-card__image"
                />
              </div>
            </div>
            <div class="course-card__body">
              <p class="course-card__text">
                Курс включає в себе таку інформацію:
              </p>
              <ul class="course-card__list">
                <li class="course-card__list-item">
                  Поглиблене вивчення технік та видів фейду
                </li>
                <li class="course-card__list-item">
                  Підбір фейду на основі вихідних даних клієнта (аналіз
                  кісткової структури, типу волосся)
                </li>
                <li class="course-card__list-item">Детальний розбір стрижок</li>
                <li class="course-card__list-item">
                  Оформлення бороди та гоління
                </li>
                <li class="course-card__list-item">
                  Догляд за волоссям клієнта (шампуні, стайлінги, сольові спреї
                  та тоніки, детальний розбір)
                </li>
                <li class="course-card__list-item">
                  Подовжені чоловічі стрижки (види, техніки стрижки, та укладка
                  довгого волосся)
                </li>
                <li class="course-card__list-item">
                  Психологія та комунікація з клієнтом
                </li>
                <li class="course-card__list-item">
                  Практичні заняття (реалізація набутих навичок на практиці)
                </li>
              </ul>
              <p class="course-card__text">Тривалість курсу 15 занять.</p>
              <p class="course-card__text">
                Цей курс підвищення кваліфікації допоможе барберам оновити свої
                навички, освоїти новітні техніки та підвищити якість
                обслуговування клієнтів. Цей курс підійде барберам з досвідом,
                або людям які пройшли курс “Барбер з нуля”.
              </p>
              <p class="course-card__text">
                Після успішного проходження курсу видаємо сертифікат.
              </p>
              <p class="course-card__price">Вартість: 12 000 грн</p>
            </div>
          </article>

          <article class="course-card">
            <div class="course-card__header">
              <!-- <img
                src="/images/course-beard-styling.jpg"
                alt="Оформлення бороди"
                class="course-card__image"
              /> -->
              <h3 class="course-card__title">
                Індивідуальний курс “Оформлення бороди”
              </h3>
              <div class="course-card__image-wrapper">
                <NuxtImg
                  src="/images/course3.webp"
                  alt="Course 3"
                  class="course-card__image"
                />
              </div>
            </div>
            <div class="course-card__body">
              <p class="course-card__text">
                Курс включає в себе таку інформацію:
              </p>
              <ul class="course-card__list">
                <li class="course-card__list-item">Анатомія обличчя</li>
                <li class="course-card__list-item">Типи та форми борід</li>
                <li class="course-card__list-item">
                  Техніки створення різних форм борід
                </li>
                <li class="course-card__list-item">
                  Підготовка шкіри перед голінням
                </li>
                <li class="course-card__list-item">
                  Оформлення контурів небезпечною бритвою
                </li>
                <li class="course-card__list-item">
                  Фейд на бороді та їх види
                </li>
                <li class="course-card__list-item">
                  Догляд за бородою та підбір косметики
                </li>
                <li class="course-card__list-item">Камуфляж бороди</li>
                <li class="course-card__list-item">
                  Відпрацювання учня на моделях
                </li>
              </ul>
              <p class="course-card__text">Тривалість курсу 10 занять</p>
              <p class="course-card__text">
                Після успішного проходження курсу видаємо сертифікат.
              </p>
              <p class="course-card__price">Вартість: 8 000 грн</p>
            </div>
          </article>

          <article class="course-card">
            <div class="course-card__header">
              <!-- <img
                src="/images/course-perm.jpg"
                alt="Чоловіча біозавивка"
                class="course-card__image"
              /> -->
              <h3 class="course-card__title">
                Індивідуальний курс «Чоловіча біозавивка»
              </h3>
              <div class="course-card__image-wrapper">
                <NuxtImg
                  src="/images/course4.webp"
                  alt="Course 4"
                  class="course-card__image"
                />
              </div>
            </div>
            <div class="course-card__body">
              <p class="course-card__text">
                Курс включає в себе таку інформацію:
              </p>
              <ul class="course-card__list">
                <li class="course-card__list-item">
                  Консультація з клієнтом перед біозавивкою
                </li>
                <li class="course-card__list-item">
                  Види коклюшок, схеми накруток
                </li>
                <li class="course-card__list-item">
                  Відпрацювання завивки на моделі
                </li>
                <li class="course-card__list-item">
                  Догляд за волоссям після завивки
                </li>
              </ul>
              <p class="course-card__text">Тривалість курсу 4-5 годин</p>
              <p class="course-card__text">Після курсу видаємо сертифікат</p>
              <p class="course-card__price">Вартість: 3 000 грн</p>
            </div>
          </article>
        </div>
      </section>

      <section id="teachers" class="teachers-section">
        <h2 class="teachers-section__title">Викладачі Академії</h2>
        <div class="teachers-section__grid">
          <div class="teacher-card">
            <NuxtImg
              src="/images/teacher1.webp"
              alt="Ім'я Викладача 1"
              class="teacher-card__image"
            />
            <p class="teacher-card__name">Вікторія Ананьєва</p>
            <p>
              Майстер із 10-річним досвідом, який успішно підготував понад 40
              кваліфікованих барберів.
            </p>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>
