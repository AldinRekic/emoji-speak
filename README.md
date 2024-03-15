## Emoji Speak: Express Yourself with Emojis and Text (Next.js, tRPC)

**Unleash the power of emoji expression!** Emoji Speak is a dynamic social media app that lets you combine emojis and text for a unique way to connect. Built with cutting-edge technologies like **Next.js** and **tRPC**, it empowers user expression and fosters a future-proof foundation for real-time interaction.

### Tech Stack:

- **Frontend:** Next.js, React 18, Clerk, tRPC, TailwindCSS
- **Backend:** Prisma
- **Authentication:** Clerk, NextAuth
- **Additional Libraries:** Upstash, SuperJSON, Dayjs, react-hot-toast (for specific functionalities)

**Key Features:**

1. **Secure & Expressive:** Create an account with Clerk and express yourself freely with emojis and text.
2. **Future-Ready Communication:** The foundation is laid for real-time features using tRPC, fostering a dynamic and interactive community.
3. **Effortless Data Management:** Store and retrieve data efficiently with Prisma (ORM).
4. **Fast & Efficient:** Enjoy optimized image loading with Next/Image and fast data transfer with SuperJSON.
5. **Create & Share:** Craft and connect posts to your profile, fostering self-expression. (PostView component with relative timestamps using Dayjs)
6. **Seamless User Experience:** Navigate effortlessly with well-defined routing for profiles and posts (powered by tRPC's createProxySSGHelpers).
7. **Secure & Reliable:** Rest assured with secure authentication practices and user-friendly error handling using Zod and react-hot-toast.

**My Expertise:**

- **Full-Stack Development:** Adept at building both front-end and back-end functionalities.
- **Tech-Savvy:** Eager to learn and implement the latest advancements in web development.
- **User-Centric Design:** Prioritize intuitive and visually appealing user interfaces.
- **Security Champion:** Prioritize secure user authentication and data integrity.
### Cloning the repository

```shell
git clone https://github.com/AldinRekic/emoji-speak.git
```

### Install packages

```shell
npm i
```
### Setup .env file
```js
DATABASE_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

UPSTASH_REDIS_REST_URL=
UPSTASH_REDIS_REST_TOKEN=
```
### Start the app

```shell
npm run dev
```
## Available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |
