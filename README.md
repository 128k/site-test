<div align="center">

# site-test

**A scratch repo for testing Jekyll on GitHub Pages.**

<br>

![Jekyll](https://img.shields.io/badge/Jekyll-Static_Site-CC0000?style=for-the-badge&logo=jekyll&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Deploy-GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Scratch](https://img.shields.io/badge/Status-Scratch-9CA3AF?style=for-the-badge)

</div>

---

## What this is

A minimal test of the **explicit** GitHub Pages path: a `_config.yml` plus a [GitHub Actions](https://docs.github.com/en/actions) workflow that builds and deploys with [Jekyll](https://jekyllrb.com), rather than relying on Pages' default built-in processing.

| File | Purpose |
|---|---|
| `_config.yml` | Jekyll configuration |
| `index.md` | The single page |
| `.github/workflows/jekyll-gh-pages.yml` | Build and deploy workflow |

The distinction is the point of the experiment: default Pages processing is zero-config but limited to a fixed plugin set, while the Actions route gives full control over the Jekyll build at the cost of maintaining a workflow.

---

## Related

[`rtest`](https://github.com/128k/rtest) is the companion — same idea, using default Pages processing with no config or workflow.

---

<div align="center">

**[James Mitchell](https://github.com/128k)**

</div>
