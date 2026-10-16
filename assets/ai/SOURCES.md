# Profile README artwork provenance

Exact official brand marks used by the AI tables in `README.md`, verified
October 2026. Self-hosted so the README never depends on third-party icon
packs (whose glyphs are redrawn approximations). Brand marks are trademarks
of their respective owners and are used only to identify the tools/models.

| File | Brand | Source | Notes |
|---|---|---|---|
| `claude.svg` | Anthropic Claude | Simple Icons `claude` (`https://cdn.simpleicons.org/claude`) | Exact starburst path in brand coral `#D97757`. Identifies the Claude model; the Claude Code tool uses its own app icon below. |
| `claude-code.png` | Anthropic Claude Code | Anthropic's VS Code Marketplace listing (`anthropic.claude-code`, v2.1.301): `https://anthropic.gallerycdn.vsassets.io/extensions/anthropic/claude-code/2.1.301/1792092236961/Microsoft.VisualStudio.Services.Icons.Default` | Official Claude Code product icon (266×266): ivory spark on the clay disc. Distinct from the plain Claude spark. SHA-256 `7241633e…f6ba1`. Anthropic's press kit (`https://www.anthropic.com/press-kit`) names the same product artwork `Claude Code logo`. |
| `grok-bot.png` | xAI Grok Bot | Original Grok Bot app icon (256×256) from the x.ai/bot product, via `https://raw.githubusercontent.com/Kargatharaakash/grok-bot-usage/main/assets/logo.png` (design cross-checked against the x.ai/bot avatar recreations) | Official "bloub" avatar: white blob with two capsule eyes on the dark tile. Distinct from the Grok slash logomark. Downscaled 256px → 128px. |
| `cursor-black.svg` / `cursor-white.svg` | Cursor | Simple Icons `cursor` (`https://cdn.simpleicons.org/cursor`) | Exact mark path. Black/white pair switched via `<picture>` + `prefers-color-scheme` so the README stays readable in both GitHub themes. |
| `grok-black.svg` / `grok-white.svg` | xAI Grok | `Grok-feb-2025-logo.svg` on Wikimedia Commons (`https://commons.wikimedia.org/wiki/File:Grok-feb-2025-logo.svg`), copied from x.ai's own header artwork | Mark-only extraction (the two `id="mark"` paths, wordmark omitted). Black/white pair per xAI's pure black / pure white guidance. |
| `meta.svg` | Meta | Simple Icons `meta` (`https://cdn.simpleicons.org/meta`) | Exact infinity path in brand blue `#0467DF`. Used for Muse Code, matching dev.meta.ai's official site asset. |
| `muse.svg` | Meta Muse | `https://introducing.muse.ai/landing/MuseLogo.svg` | Official Muse "M" pen-stroke logomark (Jessica Hische, Sept 2026), blue gradient `#0082FB` → `#0064E0` → `#0040DC`. Byte-exact copy. |
| `codex.png` | OpenAI Codex | `icon-codex-light.png` from the signed macOS ChatGPT app bundle (SHA-256 `de7d43f3…c07` verified before downscaling 1024px → 128px) | Official Codex product mark: blue-violet gradient cloud with the white `>_` prompt. Distinct from the OpenAI blossom used for GPT. |
| `openai-black.svg` / `openai-white.svg` | OpenAI GPT | `OpenAI logo 2025 (symbol).svg` on Wikimedia Commons (`https://commons.wikimedia.org/wiki/File:OpenAI_logo_2025_(symbol).svg`), sourced from `https://openai.com/brand/` | The blossom symbol in use since February 2025. Black/white pair for both GitHub themes. |
