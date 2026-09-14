# rsshub-vuln - 漏洞总览

| # | CVE | 漏洞版本 (commit) | 端点 | 类型 | 状态 |
|---|---|---|---|---|---|
| 1 | CVE-2021-21278 | `e8beb4029` (2021-01-25) | `GET /tencent/lemon` | 代码注入 / RCE (CWE-94) | **VULNERABLE** |
| 2 | CVE-2022-31110 | `041cfc376` (2022-06-21) | `GET /:route?filter=` | ReDoS (CWE-1333) | **VULNERABLE** |
| 3 | CVE-2023-22493 | `041cfc376` (2022-06-21) | `GET /gitlab/explore/:type/:host` | SSRF (CWE-918) | **VULNERABLE** |
| 4 | CVE-2023-26491 | `041cfc376` (2022-06-21) | `GET /:route?brief=` | 反射型 XSS (CWE-79) | **VULNERABLE** |
| 5 | CVE-2024-27926 | `cbbd82918` (2024) | `GET /rsshub/m/:key/:url` | 存储/反射型 XSS (CWE-79) | **VULNERABLE** |
| 6 | CVE-2024-27927 | `cbbd82918` (2024) | `GET /mastodon/acct/:acct` | SSRF (CWE-918) | **VULNERABLE** |
