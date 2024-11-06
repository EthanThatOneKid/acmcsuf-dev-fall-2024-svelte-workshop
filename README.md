# acmcsuf-dev-fall-2024-svelte-workshop

Everything you need to build a Svelte project, powered by
[`sv`](https://github.com/sveltejs/cli).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
deno -A npm:sv create

# create a new project in my-app
deno -A npm:sv create my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or
`pnpm install` or `yarn`), start a development server:

```bash
deno task dev

# or start the server and open the app in a new browser tab
deno task dev -- --open
```

## Building

To create a production version of your app:

```bash
deno task build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an
> [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.

## Shoutouts

-[Hoang Nguyen](https://github.com/kylenguyen-cs30)

---

Developed with 💙 [**@acmcsufdev**](https://github.com/acmcsufdev) by
[**@EthanThatOneKid**](https://etok.codes/) at Svelte Workshop on Nov 5th, 2024
