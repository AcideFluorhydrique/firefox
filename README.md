# Firefox CI 分支

這個分支只放 GitHub Actions workflow，不含 Firefox 原始碼。

每個 workflow 執行時會依照 `source_repo` / `source_ref` 輸入去抓原始碼，
預設是 `mozilla-firefox/firefox` 的 `main`，所以 fork 的 `main` 不必有任何自己的 commit，
可以一直保持和上游完全相同（Sync fork 只會 fast-forward）。

用法：把這個分支設成 repo 的預設分支（workflow_dispatch 只會讀預設分支上的 workflow）。

<p>
  <a href="https://github.com/AcideFluorhydrique/firefox/releases">
    <img src="https://raw.githubusercontent.com/mmlado/GapSign/main/assets/badges/badge_github.png" alt="Get it on GitHub" height="70" />
  </a>
  <a href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://add/https://github.com/AcideFluorhydrique/firefox/releases">
    <img src="https://raw.githubusercontent.com/mmlado/GapSign/main/assets/badges/badge_obtainium.png" alt="Get it on Obtainium" height="70" />
  </a>
</p>
