# Vercel's Portfolio Blog Starter With Next Themes Toggle.

![Image](/public/images/toggle-action.gif)

This template now includes Next-Themes for light and dark modes, along with a convenient toggle button.

To clarify, I only added a few components and changed the CSS structure; the rest is exactly the same as the original Vercel portfolio template. This template already includes:

- MDX and Markdown support
- Optimized for SEO (sitemap, robots, JSON-LD schema)
- RSS Feed
- Dynamic OG images
- Syntax highlighting
- Vercel Speed Insights / Web Analytics
- Geist font
- [Next-Themes](https://github.com/pacocoursey/next-themes) Light & Dark Mode Toggle

## Live Demo

https://portfolio-starter-with-toggle.vercel.app/

## Changes

I was having issues with the alpha version of Tailwind 4, so I reverted back to the latest stable release and installed [Next-Themes](https://github.com/pacocoursey/next-themes).

Then I created 2 components `app/components/mode-toggle.tsx`, and `app/components/theme-provider.tsx` to make the toggle work. Then I wrapped the application with the theme provider in `app/layout.tsx`, and finally, I added the icon to the `app/components/nav.tsx` file.

Besides that, nothing else was changed or touched. This is the exact same template as the original Portfolio Blog Starter kit, with a light and dark mode toggle added for convenience.

For more details and a step-by-step guide, check the [blog post](https://www.jorge-perez.dev/blog/template-with-toggle)

### Clone and Deploy

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [pnpm](https://pnpm.io/installation) to bootstrap the example:

```bash
pnpm create next-app --example https://github.com/JPerez00/portfolio-starter-with-toggle/tree/main your-project-name-here

```

Then, run Next.js in development mode:

```bash
pnpm dev
```

Deploy it to the cloud with [Vercel](https://vercel.com/templates) ([Documentation](https://nextjs.org/docs/app/building-your-application/deploying)).
