# Firefox CI Branch

This branch contains only GitHub Actions workflows and does not include the Firefox source code.

When each workflow runs, it fetches the source code according to the `source_repo` / `source_ref` inputs. By default, it uses `main` from `mozilla-firefox/firefox`.

This means the fork's `main` branch does not need to contain any commits of its own and can remain exactly in sync with upstream indefinitely. Sync fork will only perform fast-forward updates.

**Usage:** Set this branch as the repository's default branch. (`workflow_dispatch` only reads workflows from the default branch.)

---

這個分支只包含 GitHub Actions workflows，不包含 Firefox 原始碼。

每個 workflow 執行時，都會根據 `source_repo` / `source_ref` 輸入參數抓取原始碼。預設使用 `mozilla-firefox/firefox` 的 `main` 分支。

這表示 fork 的 `main` 分支不需要包含任何自己的 commit，可以一直與上游保持完全同步（Sync fork 只會執行 fast-forward 更新）。

**使用方式：** 將這個分支設為 repository 的預設分支。（`workflow_dispatch` 只會讀取預設分支上的 workflow。）

<p>
  <a href="https://github.com/AcideFluorhydrique/firefox/releases">
    <img src="https://raw.githubusercontent.com/mmlado/GapSign/main/assets/badges/badge_github.png" alt="Get it on GitHub" height="70" />
  </a>
  <a href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://add/https://github.com/AcideFluorhydrique/firefox/releases">
    <img src="https://raw.githubusercontent.com/mmlado/GapSign/main/assets/badges/badge_obtainium.png" alt="Get it on Obtainium" height="70" />
  </a>
</p>
