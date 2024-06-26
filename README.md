<a href="https://ani.rohi.dev">
  <img alt="Anirohi – an open-source streaming site built with Nextjs 14 app router" src="https://raw.githubusercontent.com/gneiru/anirohi/master/public/images/landing.png">
  <h1 align="center">Anirohi</h1>
</a>

<p align="center">
  An open-source anime streaming site built with Nextjs 14 app router.
</p>

<p align="center">
  <a href="#introduction"><strong>Introduction</strong></a> ·
  <a href="#run-locally"><strong>Run Locally</strong></a> ·
  <a href="#tech-stack"><strong>Tech Stack</strong></a> ·
  <a href="#implementation"><strong>Implementation</strong></a> ·
</p>
<br/>

## Introduction

Anirohi is an open-source anime streaming site with tracking, watching, and dashboard. Built with [Nextjs](https://nextjs.org/), [Consumet](https://docs.consumet.org), [Anilist](https://anilist.gitbook.io/), and [NeonDB](https://neon.tech/).

Here are some of the features that Anirohi provides:

- [Anilist Integration](#anilist-integration)
- [OG Image](#og-image)
- [Comments](#comments)

### Anilist Integration

Check your stats

![Anilist Dashboard](https://raw.githubusercontent.com/gneiru/anirohi/master/public/images/anilist-dashboard.png)

While watching authenticated, you can update your Anilist anime progress.

![Anilist Update Button](https://raw.githubusercontent.com/gneiru/anirohi/master/public/images/mark-anilist.png)

### OG Image

Share the link and see the detailed OG Image about the series or episode. Powered by [Vercel Satori](https://og-playground.vercel.app/).

![OG From Discord](https://raw.githubusercontent.com/gneiru/anirohi/master/public/images/socialshare-preview.png)

### Comments

Share your thoughts in episode

![Comment Section](https://raw.githubusercontent.com/gneiru/anirohi/master/public/images/comment-section.png)

## Run Locally

Clone the project

```bash
  git clone https://github.com/gneiru/anirohi
```

Go to the project directory

```bash
  cd anirohi
```

Install dependencies

```bash
  bun install
```

Start the server

```bash
  bun dev
```

## Tech Stack

- [Next.js](https://nextjs.org/) – framework
- [Typescript](https://www.typescriptlang.org/) – language
- [Tailwind](https://tailwindcss.com/) – CSS
- [Upstash](https://upstash.com/) – ratelimit
- [Neon](https://neon.tech/) – database
- [Drizzle](https://orm.drizzle.team/) - ORM
- [NextAuth.js](https://next-auth.js.org/) – auth
- [Vercel](https://vercel.com/) – hosting & KV

## Implementation

Anirohi is built as a standard Next.js application with [Consumet](https://docs.consumet.org). <br>
[Satori](https://og-playground.vercel.app/) is used for generating open-graph images based on Anime series and episode. <br>
[Anilist](https://anilist.gitbook.io/) is used as the auth provider as well as for mutating user progress. <br>
[React-player](https://www.npmjs.com/package/react-player) is used to play video sources to watch anime on. <br>
[PostgreSQL](https://www.postgresql.org/) is used as the database for storing user data, history, and comments . You can refer to the Drizzle schema [here](/src/db/schema). <br>

## Contributing

We love our contributors! Here's how you can contribute:

- [Open an issue](https://github.com/gneiru/anirohi/issues) if you believe you've encountered a bug.
- Make a [pull request](https://github.com/gneiru/anirohi/pull) to add new features/make quality-of-life improvements/fix bugs.

<a href="https://github.com/gneiru/anirohi/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=gneiru/anirohi" />
</a>

## Repo Activity

![Anirohi repo activity – generated by Axiom](https://repobeats.axiom.co/api/embed/da795c147fb49c098e7ab96086fadcbd2cf7e777.svg "Repobeats analytics image")


## Star History

<a href="https://star-history.com/#gneiru/anirohi&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=gneiru/anirohi&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=gneiru/anirohi&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=gneiru/anirohi&type=Date" />
  </picture>
</a>

