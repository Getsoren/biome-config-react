# @getsoren/biome-config-react

🧹 **Shared Biome configuration for React projects**.
This package provides a centralized and consistent linting and formatting setup using [Biome](https://biomejs.dev/), ensuring clean and maintainable code across all front-end applications.

---

## 📦 Installation

```bash
bun add -D @biomejs/biome @getsoren/biome-config-react
# or
yarn add -D @biomejs/biome @getsoren/biome-config-react
# or
npm install -D @biomejs/biome @getsoren/biome-config-react
```

## ⚙️ Usage

Create or update a biome.json (or biome.jsonc) file at the root of your project:

```JSON
{
  "extends": ["@getsoren/biome-config-react"]
}
```

## 🧭 Commands

Check for linting and formatting issues:

```bash
bun x biome check .
```

Automatically fix issues:

```bash
bun x biome check . --write
```

Format files:

```bash
bun x biome format . --write
```
