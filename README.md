# lurker-for-reddit-svelte

# 🚀 Welcome to Lurker for Reddit. A reddit site that looks nice and has no user-setup 🚀

https://github.com/coding-to-music/lurker-for-reddit-svelte

https://coding-to-music.github.io/lurker-for-reddit-svelte

https://lurker-for-reddit-svelte.vercel.app

From / By https://github.com/industry-standard-good-practice/lurker-for-reddit

https://lurker.me

https://lurker-for-reddit-lhk7gboam-industry-standard.vercel.app/l/all

https://kit.svelte.dev/docs/adapters

## Environment variables:

```java

```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/lurker-for-reddit-svelte.git
git push -u origin main
```

## Output messages

```
401 - {"message":"Unauthorized","error":401}
StatusCodeError: 401 - {"message":"Unauthorized","error":401}
```

# Lurker for Reddit

[Live site](https://lurker.me)

Welcome to Lurker for Reddit. A reddit site that looks nice and has no user-setup. Everything is stored in local storage with no tracking, ads, or analytics of any kind. Lurker is a hobby project built with Sveltekit. As such, there's not a ton of active development, so don't expect new features or updates. If you do want something, though, always feel free to open an issue or pull request.

## Developing

Clone this repo locally. Install dependencies via `npm install` (or `pnpm install` or `yarn`), then start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

In order for data to be fetched from the Reddit API, you must create a `.env` or `.env.local` file in the root of the directory. In it put `CLIENT_SECRET="YOUR CLIENT SECRET"`.

> To get your client secret, go to [this link](https://www.reddit.com/prefs/apps) and create an app.

## Building

To create a production version:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

## License

MIT
