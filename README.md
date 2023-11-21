AuthForm - это форма авторизации, разработанная с использованием технологий TypeScript, React, Prisma и MongoDB. Этот проект предоставляет безопасный и эффективный механизм аутентификации для ваших пользователей.

Основные функциональности:

1. Вход в систему:<br>
 Пользователь вводит свой адрес электронной почты и пароль.<br>
 Форма производит валидацию введенных данных с использованием TypeScript, обеспечивая типизированную безопасность.<br>
 Происходит отправка запроса на сервер для проверки учетных данных в базе данных MongoDB с использованием Prisma.<br>

2. Регистрация нового пользователя:<br>
Форма также поддерживает регистрацию новых пользователей.<br>
Пользователь вводит необходимые данные, такие как имя, адрес электронной почты и пароль.<br>
Данные проходят валидацию и отправляются на сервер для создания новой записи в базе данных MongoDB через Prisma.

 <img width="1000px" src="imgs/Снимок экрана 2023-11-21 в 18.57.28.png" alt="qr"/>

Технологии:

Frontend: Разработан с использованием React и TypeScript для построения динамичного и масштабируемого интерфейса.<br>
Бэкенд: TypeScript используется для написания серверной логики. Prisma служит в качестве ORM (Object-Relational Mapping) для взаимодействия с базой данных MongoDB.<br>
База данных: MongoDB выбрана как хранилище данных для удобства масштабирования и гибкости.<br>

Как использовать:

1. Установите зависимости на сервере с использованием npm или yarn.
2. Запустите сервер и подключите его к вашей MongoDB базе данных.
3. Установите зависимости на клиенте с помощью npm или yarn.
4. Запустите клиентскую часть для доступа к форме авторизации.
## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
