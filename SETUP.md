# 🚀 Profile README — Setup (3 minutes)

Your special repo is **`chetankumarmk56/chetankumarmk56`** (a repo whose name matches your
username is what renders on your profile page).

## 1. Add the files
Put these in the **root** of that repo, keeping the folder structure:

```
chetankumarmk56/
├── README.md
├── banner.svg
└── .github/
    └── workflows/
        └── snake.yml
```

- `README.md`  → your profile content
- `banner.svg` → the custom banner (README loads it with `./banner.svg`)
- `snake.yml`  → the GitHub Action that generates the contribution snake

## 2. Turn on the snake 🐍
1. Push the files. Go to the repo's **Actions** tab.
2. If prompted, click **"I understand my workflows, enable them."**
3. Open **"Generate Snake Animation"** → click **Run workflow** (the manual run).
4. Wait ~1 minute. It creates an `output` branch with `snake-dark.svg`.
5. Refresh your profile — the snake now animates across your contributions.

> ⚠️ The first run will fail if the repo has no `output` branch yet **and** the
> token lacks write access. If it errors, go to **Settings → Actions → General →
> Workflow permissions** and select **"Read and write permissions"**, then re-run.

> The snake auto-refreshes every 12 hours. Until step 3 finishes once, the snake
> image will show as broken — that's expected; it appears after the first run.

## Notes
- **Banner** is a committed file, so it never depends on a flaky external service. ✅
- The **stats / streak / languages / trophies** cards still load live from free
  services and can briefly show a loading state — a refresh fixes them.
