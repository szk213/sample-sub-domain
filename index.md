## sample-sub-domain

1. お名前のDNSレコード設定で以下の用に設定
    - `sub.szk213.com CNAME 3600 szk213.github.io`
    - `www.szk213.com CNAME 3600 szk213.github.io`
2. Ghのプロジェクトの設定のGitHub Pagesに以下の用に設定
    - Custom domain: sub.szk213.com
    - Enforce HTTPS: [*]
        - ※時間たってから
