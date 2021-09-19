# Random Geekery Blog Astro Adoc

My attempt to build a version of [my blog][rgb-site] and its [Asciidoctor][adoc] content with [Astro][astro].

[rgb-site]: https://randomgeekery.org
[adoc]: http://asciidoctor.org
[astro]: https://astro.build

Since I have no deep Node.js or JavaScript knowledge, it mostly involves me starting
from the Astro generic starter and flailing a lot.

Things that seem to have settled down a bit already:

- Asciidoctor files go under `content/`
- draft posts go under `content/draft/`
- `<Asciidoctor content={content} />` stuffs Asciidoctor content into a layout
- the index file for each section has a `SectionLayout` listing articles

Everything not noted here is expected to fluctuate wildly as I figured out what the heck I'm doing.

The rest of this document is a lightly edited version of the original Astro starter `README.md`.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command         | Action                                      |
| :-------------- | :------------------------------------------ |
| `npm install`   | Installs dependencies                       |
| `npm run dev`   | Starts local dev server at `localhost:3000` |
| `npm run build` | Build your production site to `./dist/`     |

## 👀 Want to learn more?

- [Astro documentation](https://github.com/snowpackjs/astro)
- [Asciidoctor documentation](https://docs.asciidoctor.org)
