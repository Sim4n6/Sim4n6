![CVEs](https://img.shields.io/badge/Vulnerabilities%20Reported-37-blue)
![Critical](https://img.shields.io/badge/Critical-4-critical)
![High](https://img.shields.io/badge/High-10-orange)
![Medium](https://img.shields.io/badge/Medium-19-yellow)
![Low](https://img.shields.io/badge/Low-4-lightgrey)

---

## CVEs & Security Advisories

<details open>
<summary><strong>2026 (1)</strong></summary>

| N° | CVE | Severity | Target | Description |
|:--:|:---:|:--------:|:------:|:-----------:|
| 35 | CVE-2026-1388 | High | GitLab CE/EE | Regular Expression Denial of Service issue in GitLab merge requests - [GitLab Patch Release](https://about.gitlab.com/releases/2026/02/25/patch-release-gitlab-18-9-1-released/#cve-2026-1388---regular-expression-denial-of-service-issue-in-gitlab-merge-requests-impacts-gitlab-ceee) |

</details>

<details open>
<summary><strong>2025 (8)</strong></summary>

| N° | CVE | Severity | Target | Description |
|:--:|:---:|:--------:|:------:|:-----------:|
| 37 | [CVE-2025-12576](https://about.gitlab.com/releases/2026/03/11/patch-release-gitlab-18-9-2-released/#cve-2025-12576---denial-of-service-issue-in-webhook-endpoint-impacts-gitlab-ceee) | Medium | GitLab CE/EE | Denial of Service issue in webhook endpoint - [GitLab Patch Release](https://about.gitlab.com/releases/2026/03/11/patch-release-gitlab-18-9-2-released/#cve-2025-12576---denial-of-service-issue-in-webhook-endpoint-impacts-gitlab-ceee) |
| 36 | [CVE-2025-13690](https://about.gitlab.com/releases/2026/03/11/patch-release-gitlab-18-9-2-released/#cve-2025-13690---denial-of-service-issue-in-webhook-custom-headers-impacts-gitlab-ceee) | Medium | GitLab CE/EE | Denial of Service issue in webhook custom headers - [GitLab Patch Release](https://about.gitlab.com/releases/2026/03/11/patch-release-gitlab-18-9-2-released/#cve-2025-13690---denial-of-service-issue-in-webhook-custom-headers-impacts-gitlab-ceee) |
| 34 | [CVE-2025-13335](https://about.gitlab.com/releases/2026/01/21/patch-release-gitlab-18-8-2-released/#cve-2025-13335---infinite-loop-issue-in-wiki-redirects-impacts-gitlab-ceee) | Medium | GitLab CE/EE | Crafted wiki file may lead to endless server-side redirections - [Bleeping Computer](https://www.bleepingcomputer.com/news/security/gitlab-warns-of-high-severity-2fa-bypass-denial-of-service-flaws/) |
| 33 | [CVE-2025-0673](https://about.gitlab.com/releases/2025/06/11/patch-release-gitlab-18-0-2-released/#cve-2025-0673---denial-of-service-impacts-gitlab-ceee) | High | GitLab CE/EE | An attacker can trigger an infinite redirect loop, leading to a denial of service condition - [Patch Release](https://about.gitlab.com/releases/2025/06/11/patch-release-gitlab-18-0-2-released/#cve-2025-0673---denial-of-service-impacts-gitlab-ceee) |
| 32 | [GHSA-6p2v-wcv8-8j6w](https://github.com/stealthcopter/CaidoExploitGenerator/security/advisories/GHSA-6p2v-wcv8-8j6w) | Critical | Caido Plugin | Arbitrary File Read by Copy as a Curl command in Caido Plugin Exploit Generator - [advisory](https://github.com/stealthcopter/CaidoExploitGenerator/security/advisories/GHSA-6p2v-wcv8-8j6w) |
| 31 | [CVE-2025-0549](https://about.gitlab.com/releases/2025/05/07/patch-release-gitlab-17-11-2-released/#partial-bypass-for-device-oauth-flow-using-cross-window-forgery) | Medium | GitLab | Partial Bypass for Device OAuth flow using Cross Window Forgery |
| 30 | [CVE-2025-31116](https://github.com/MobSF/Mobile-Security-Framework-MobSF/security/advisories/GHSA-fcfq-m8p6-gw56) | Medium | MobSF | SSRF on assetlinks_check with DNS Rebinding |

</details>

<details open>
<summary><strong>2024 (15)</strong></summary>

| N° | CVE | Severity | Target | Description |
|:--:|:---:|:--------:|:------:|:-----------:|
| 29 | [Hall of Fame](https://dev.to/security) | Medium | DEV.to | Denial of Service Due to Inefficient Processing of Unicode Input |
| 28 | [CVE-2024-13054](https://nvd.nist.gov/vuln/detail/CVE-2024-13054) | Medium | GitLab EE | Denial of Service Due to Inefficient Processing of Untrusted Input |
| 27 | [CVE-2024-12379](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2024-12379) | Medium | GitLab EE | Denial of Service due to Unbounded Object Creation via the scopes parameter in a Personal Access Token |
| 26 | [CVE-2024-47830](https://github.com/makeplane/plane/security/advisories/GHSA-39gx-38xf-c348) | Critical | Plane | Server side request forgery via /_next/image endpoint |
| 25 | [CVE-2024-8124](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2024-8124) | High | [GitLab](https://gitlab.com/gitlab-org/gitlab/-/issues/480533) | Denial of Service via sending a large glm_source parameter |
| 24 | [CVE-2024-45412](https://github.com/yeti-platform/yeti/security/advisories/GHSA-cwwm-pq9x-2cxv) | Medium | Yeti Platform | Potential Denial of Service due to the One Million Unicode Characters attack |
| 23 | [CVE-2024-35231](https://github.com/rack/rack-contrib/security/advisories/GHSA-8c8q-2xw3-j869) | High | Rack::Contrib | Denial of Service due to the unconstrained value of the incoming "profiler_runs" parameter |
| 22 | [CVE-2024-1211](https://about.gitlab.com/releases/2024/05/08/patch-release-gitlab-16-11-2-released/) | Medium | GitLab | Require confirmation before linking JWT identity - [GitLab Blog](https://about.gitlab.com/releases/2024/05/08/patch-release-gitlab-16-11-2-released/) |
| 21 | [GHSA-9gw7-hxgx-f6rv](https://github.com/certsocietegenerale/fame/security/advisories/GHSA-9gw7-hxgx-f6rv) | Medium | FAME (Cert SG) | Malicious Long Unicode filenames may cause an Application-level Denial of Service |
| 20 | [CVE-2024-32874](https://github.com/blakeblackshear/frigate/security/advisories/GHSA-w4h6-9wrp-v5jq) | Medium | Frigate | Malicious Long Unicode filenames may cause Multiple Application-level Denial of Service |
| 19 | [CVE-2024-0081](https://github.com/NVIDIA/NeMo/security/advisories/GHSA-x392-p65g-4rxx) | High | NVIDIA NeMo | Unicode use in a user-controlled filename may cause a server-side DoS - [Nvidia Acknowledgement](https://www.nvidia.com/en-us/security/acknowledgements/) |
| 18 | [CVE-2024-24759](https://github.com/mindsdb/mindsdb/security/advisories/GHSA-4jcv-vp96-94xr) | Critical | MindsDB | Bypass SSRF Protection with DNS Rebinding |
| 17 | [CVE-2024-23826](https://github.com/spbu-se/spbu_se_site/security/advisories/GHSA-5vfc-v7hg-pvwm) | Medium | SPbU SE Site | Uploading an image with a specific filename causes a server-side DoS |
| 16 | CVE-2024-23343 | Medium | — | — |
| 15 | [CVE-2024-21623](https://github.com/mehah/otclient/security/advisories/GHSA-q6gr-wc79-v589) | Critical | OTClient | Arbitrary Expression Injection in GitHub workflow leads to Command execution & leaking secrets |

</details>

<details open>
<summary><strong>2023 (10)</strong></summary>

| N° | CVE | Severity | Target | Description |
|:--:|:---:|:--------:|:------:|:-----------:|
| 14 | [CVE-2023-52081](https://github.com/ewen-lbh/ffcss/security/advisories/GHSA-wpmx-564x-h2mh) | Low | ffcss | Late-Unicode normalization vulnerability |
| 13 | [CVE-2023-41889](https://nvd.nist.gov/vuln/detail/CVE-2023-41889) | Medium | Shirasagi | Late-Unicode normalization vulnerability |
| 12 | [CVE-2023-42183](https://nvd.nist.gov/vuln/detail/CVE-2023-42183) | Low | LOCKSS | A Post-Unicode Normalization Vulnerability |
| 11 | CVE-2023-39911 | Medium | — | — |
| 10 | [GHSA-373w-rj84-pv6x](https://github.com/IncludeSecurity/safeurl-python/security/advisories/GHSA-373w-rj84-pv6x) | Low | safeurl-python | Hostname blocklist does not block FQDNs - [advisory](https://github.com/IncludeSecurity/safeurl-python/security/advisories/GHSA-373w-rj84-pv6x) |
| 9 | [CVE-2023-35932](https://github.com/tanghaibao/jcvi/security/advisories/GHSA-x49m-3cw7-gq5q) | High | jcvi | Configuration Injection due to unsanitized user input - [advisory](https://github.com/tanghaibao/jcvi/security/advisories/GHSA-x49m-3cw7-gq5q) |
| 8 | [CVE-2023-31131](https://github.com/greenplum-db/gpdb/security/advisories/GHSA-hgm9-2q42-c7f3) | Medium | Greenplum DB | Arbitrary File Write when Extracting Tarballs using `shutil.unpack_archive()` |
| 7 | [CVE-2023-30620](https://github.com/mindsdb/mindsdb/security/advisories/GHSA-2g5w-29q9-w6hx) | High | MindsDB | Arbitrary File Write when Extracting a Remotely retrieved Tarball using `Tarfile.extractall()` |
| 6 | [CVE-2022-23522](https://github.com/mindsdb/mindsdb/security/advisories/GHSA-7x45-phmr-9wqp) | High | MindsDB | Arbitrary File Write when Extracting Tarballs using `shutil.unpack_archive()` |
| 5 | [CVE-2023-25803](https://github.com/hap-wi/roxy-wi/security/advisories/GHSA-cv9w-j9gh-5j3w) / [CVE-2023-25802](https://github.com/hap-wi/roxy-wi/security/advisories/GHSA-qcmp-q5h3-784m) | High | Roxy-WI | Directory Traversal vulnerability |
| 4 | [CVE-2023-25804](https://github.com/hap-wi/roxy-wi/security/advisories/GHSA-69j6-crq8-rrhv) | Medium | Roxy-WI | Limited Path Traversal in name parameter |

</details>

<details open>
<summary><strong>2022 (3)</strong></summary>

  # In Sum
  
  Security Researcher focused on vulnerability discovery through responsible disclosure and bug bounty programs.                                              
  
  Specializing in **Path Traversal**, **SSRF**, **Denial of Service (Unicode/ReDoS)**, **Arbitrary File Write**, and **CI/CD Security**.                      
  

| N° | CVE | Severity | Target | Description |
|:--:|:---:|:--------:|:------:|:-----------:|
| 3 | [CVE-2022-23530](https://github.com/advisories/GHSA-78m5-jpmf-ch7v) | Low | GuardDog (DataDog) | GuardDog vulnerable to arbitrary file write when scanning a specially-crafted remote PyPI package - [advisory](https://github.com/advisories/GHSA-78m5-jpmf-ch7v) |
| 2 | [CVE-2022-3607](https://huntr.dev/bounties/2d1db3c9-93e8-4902-a55b-5ea53c22aa11/) | Medium | OctoPrint | ZipSlip Symlink variant allows to read any file within OctoPrint Box |
| 1 | [CVE-2022-1993](https://github.com/advisories/GHSA-6vcc-v9vw-g2x5) | High | Gogs | Path Traversal vulnerability on the endpoint '/info/refs' - [advisory](https://github.com/advisories/GHSA-6vcc-v9vw-g2x5) |

</details>
