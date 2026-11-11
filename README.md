🛠 Используемые технологии

Frontend:

- [Next.js (App Router)](https://nextjs.org/) — React-фреймворк для SSR.
- React Context — для управления состоянием корзины.
- Vanilla CSS — для стилизации.
- LocalStorage — для сохранения корзины пользователя между сессиями.

Backend:

- [Strapi (Headless CMS)](https://strapi.io/) — для управления контентом.
- SQLite — база данных (встроенная, не требует отдельной установки).
- REST API — для связи между фронтендом и бэкендом.

ЗАПУСК БЭКЕНД:

1. npm install
2. npm run dev
   дождаться "Welcome back! To manage your project 🚀1"

   http://localhost:1337
   админка: http://localhost:1337/admin
   (Примечание: если база данных пуста, вам нужно будет зарегистрировать администратора в Strapi, создать модели Product и Category, наполнить их данными и обязательно нажать Publish).
