<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/varbees/varbees/main/assets/header-dark.svg">
  <img src="https://raw.githubusercontent.com/varbees/varbees/main/assets/header-light.svg" alt="harshavardhan beesabathina — 1442 contributions in the last year" width="100%">
</picture>

[antharmaya.com](https://antharmaya.com) · [linkedin](https://linkedin.com/in/varbees) · [email](mailto:harshavar968@gmail.com)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/varbees/varbees/main/assets/s-about-dark.svg">
  <img src="https://raw.githubusercontent.com/varbees/varbees/main/assets/s-about-light.svg" alt="about" width="100%">
</picture>

> Self-taught into systems from the web side. Small tools that do one thing
> completely, over frameworks that do everything badly.

I direct a multi-agent workforce to build production software, and I review
everything it writes. That habit is the whole job — it's why I can point at
783 passing test functions instead of claiming coverage.

Right now that's **stallwatch** — your machine freezes, every monitor says it's
fine, and nothing tells you what stopped you. It reads the pressure data Linux
already writes and names the process. Zero dependencies, no root.

Going deeper into kernel-side resource control: cgroups, PSI, and what it takes
to bound an AI agent on a real machine without giving it root.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/varbees/varbees/main/assets/s-stack-dark.svg">
  <img src="https://raw.githubusercontent.com/varbees/varbees/main/assets/s-stack-light.svg" alt="stack" width="100%">
</picture>

rust  go  typescript  python  postgres  linux  cgroups  systemd  mcp
next.js  react  webgpu  cloudflare workers  docker

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/varbees/varbees/main/assets/s-projects-dark.svg">
  <img src="https://raw.githubusercontent.com/varbees/varbees/main/assets/s-projects-light.svg" alt="projects" width="100%">
</picture>

[**stallwatch**](https://github.com/varbees/stallwatch) · rust, no dependencies
Names the systemd unit, then the process, that froze your machine. Wakes on
kernel triggers instead of polling, so it costs nothing until something breaks.

[**rateguard**](https://github.com/varbees/rateguard) · go, node, python
An agent holds your API key and no sense of when to stop. Budgets and breakers
enforced in-process. No proxy, no network hop.

[**memory-bridge**](https://github.com/antharmaya/mem-bridge) · python, mcp
Every coding agent starts each task blind. Finds the conversations already on
your disk and gives them one shared memory.

[**photoselect**](https://photoselect.space) · go, next.js, postgres
Payment-gated gallery delivery for Indian wedding studios. Shipped solo, 911
commits. Shelved on purpose — the backend is off on a lapsed bill, not a design
failure.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/varbees/varbees/main/assets/s-stats-dark.svg">
  <img src="https://raw.githubusercontent.com/varbees/varbees/main/assets/s-stats-light.svg" alt="stats" width="100%">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/varbees/varbees/main/assets/stats-dark.svg">
  <img src="https://raw.githubusercontent.com/varbees/varbees/main/assets/stats-light.svg" alt="languages by bytes written, and the year" width="100%">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/varbees/varbees/main/assets/s-about-this-page-dark.svg">
  <img src="https://raw.githubusercontent.com/varbees/varbees/main/assets/s-about-this-page-light.svg" alt="about this page" width="100%">
</picture>

Every graphic here is generated, not embedded from anyone else's server.
[`tools/refresh.py`](tools/refresh.py) pulls the numbers from the GitHub API,
[`tools/make_assets.py`](tools/make_assets.py) draws the SVGs, and both are
committed here.

Badge and stat-card services rate-limit, go down, change their rendering
without telling you, and see the traffic of everyone who visits. A page that
opens by saying I care about dependencies shouldn't load ten of them first.

Every graphic is drawn twice, light and dark, and picked by
`prefers-color-scheme`. A light panel on a dark profile is a glaring white
rectangle; shipping one theme means choosing which half of readers get the bad
version.

The headings are SVGs for the same reason: GitHub strips CSS from READMEs, so
an image is the only way to put this page's own type on them. No webfont is
carried — it uses whatever monospace you already have.

Numbers are checked before they're written. Contributions and languages from
the API, test counts by running the suites. A stale one is a bug.
