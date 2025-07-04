Hi 👋

|N°| CVE 	| Severity 	| Description 	|
|:--:	|:---:	|:--------:	|:-----------:	|
|1 |   [CVE-2022-1993](https://github.com/advisories/GHSA-6vcc-v9vw-g2x5)   	|      High     	|        Path Traversal vulnerability on the endpoint '/info/refs' in Gogs (A self-hosted Git service) - [advisory](https://github.com/advisories/GHSA-6vcc-v9vw-g2x5) 	|
|2 |   [CVE-2022-3607](https://huntr.dev/bounties/2d1db3c9-93e8-4902-a55b-5ea53c22aa11/)   	|      Medium      	|      ZipSlip Symlink variant allows to read any file within OctoPrint Box in Octoprint (An open source 3D printer controller application) 	|
|3 |  [CVE-2022-23530](https://github.com/advisories/GHSA-78m5-jpmf-ch7v)   	|      Low    	|      GuardDog vulnerable to arbitrary file write when scanning a specially-crafted remote PyPI package (DataDog CLI tool to identify malicious PyPI and npm packages or Go modules) - [advisory](https://github.com/advisories/GHSA-78m5-jpmf-ch7v) 	|    
|4 |  [CVE-2023-25804](https://github.com/hap-wi/roxy-wi/security/advisories/GHSA-69j6-crq8-rrhv)   	|     Medium     	|     Limited Path Traversal in name parameter hap-wi/roxy-wi        	|
|5 |  [CVE-2023-25803](https://github.com/hap-wi/roxy-wi/security/advisories/GHSA-cv9w-j9gh-5j3w) [CVE-2023-25802](https://github.com/hap-wi/roxy-wi/security/advisories/GHSA-qcmp-q5h3-784m)  	|    High    	|        Directory Traversal vulnerability in hap-wi/roxy-wi       	|
|6 |   [CVE-2022-23522](https://github.com/mindsdb/mindsdb/security/advisories/GHSA-7x45-phmr-9wqp)  	|    High      	|        Arbitrary File Write when Extracting Tarballs retrieved from a remote location using `shutil.unpack_archive()`       	|
|7 |   [CVE-2023-30620](https://github.com/mindsdb/mindsdb/security/advisories/GHSA-2g5w-29q9-w6hx)  	|    High      	|         Arbitrary File Write when Extracting a Remotely retrieved Tarball using `Tarfile.extractall()` in mindsdb/mindsdb        	|
|8 |   [CVE-2023-31131](https://github.com/greenplum-db/gpdb/security/advisories/GHSA-hgm9-2q42-c7f3)  	|    Medium      	|     Arbitrary File Write when Extracting Tarballs retrieved from a remote location using `shutil.unpack_archive()` in greenplum-db/gpdb        	|
|9 |   [CVE-2023-35932](https://github.com/tanghaibao/jcvi/security/advisories/GHSA-x49m-3cw7-gq5q)  	|    High      	|    Configuration Injection in tanghaibao/jcvi due to unsanitized user input - [advisory](https://github.com/tanghaibao/jcvi/security/advisories/GHSA-x49m-3cw7-gq5q)  	|
|10 |   [GHSA-373w-rj84-pv6x](https://github.com/IncludeSecurity/safeurl-python/security/advisories/GHSA-373w-rj84-pv6x)  	|    Low    	|    Hostname blocklist does not block FQDNs in IncludeSecurity/safeurl-python - [advisory](https://github.com/IncludeSecurity/safeurl-python/security/advisories/GHSA-373w-rj84-pv6x)	|
|11 |   [CVE-2023-39911]()  	|    Medium    	|    ---  	|
|12 |   [CVE-2023-42183](https://nvd.nist.gov/vuln/detail/CVE-2023-42183)  	|    Low    	|     A Post-Unicode Normalization Vulnerability in lockss/lockss-daemon  |
|13 |   [CVE-2023-41889](https://nvd.nist.gov/vuln/detail/CVE-2023-41889) 	|    Medium   	|     Late-Unicode normalization vulnerability in shirasagi/shirasagi   	|
|14 |   [CVE-2023-52081](https://github.com/ewen-lbh/ffcss/security/advisories/GHSA-wpmx-564x-h2mh) 	|   Low   	| Late-Unicode normalization vulnerability in ewen-lbh/ffcss   	|
|15 |   [CVE-2024-21623](https://github.com/mehah/otclient/security/advisories/GHSA-q6gr-wc79-v589)   | Critical |  Arbitrary Expression Injection in github workflow leads to Command execution & leaking secrets in mehah/otclient |
|16 | CVE-2024-23343 | Medium | |
|17 | [CVE-2024-23826](https://github.com/spbu-se/spbu_se_site/security/advisories/GHSA-5vfc-v7hg-pvwm) | Medium |  Uploading an image with a specific filename causes a server-side DoS in spbu-se/spbu_se_site (Website of the Department of System Programming of St. Petersburg State University) |
|18 |  [CVE-2024-24759](https://github.com/mindsdb/mindsdb/security/advisories/GHSA-4jcv-vp96-94xr) | Critical |  Bypass SSRF Protection with DNS Rebinding in mindsdb/mindsdb |
|19 |  [CVE-2024-0081](https://github.com/NVIDIA/NeMo/security/advisories/GHSA-x392-p65g-4rxx) | High | Unicode use in a user-controlled filename may cause a server-side DoS in Nvidia/NeMo - [Nvidia security acknowledgement](https://www.nvidia.com/en-us/security/acknowledgements/) | 
|20 | [CVE-2024-32874](https://github.com/blakeblackshear/frigate/security/advisories/GHSA-w4h6-9wrp-v5jq#event-188171) | Medium | Malicious Long Unicode filenames may cause a Multiple Application-level Denial of Service  |
|21 | [GHSA-9gw7-hxgx-f6rv](https://github.com/certsocietegenerale/fame/security/advisories/GHSA-9gw7-hxgx-f6rv) | Medium | Malicious Long Unicode filenames may cause an Application-level Denial of Service |
| 22 | [CVE-2024-1211]() | Medium | Require confirmation before linking JWT identity on [Gitlab Blog](https://about.gitlab.com/releases/2024/05/08/patch-release-gitlab-16-11-2-released/) |
| 23 | [CVE-2024-35231](https://github.com/rack/rack-contrib/security/advisories/GHSA-8c8q-2xw3-j869#advisory-comment-102825) | High | Denial of Service due to the unconstrained value of the incoming "profiler_runs" parameter  |
| 24 | [CVE-2024-45412](https://github.com/yeti-platform/yeti/security/advisories/GHSA-cwwm-pq9x-2cxv) | Medium | Potential Denial of Service due to the One Milion Unicode characters attack  |
| 25 | [CVE-2024-8124](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2024-8124) | High| Denial of Service via sending a large glm_source parameter in [GitLab](https://gitlab.com/gitlab-org/gitlab/-/issues/480533) |
| 26 | [CVE-2024-47830](https://github.com/makeplane/plane/security/advisories/GHSA-39gx-38xf-c348)| Critical |  Server side request forgery via /_next/image endpoint on makeplane/plane |
| 27 | [CVE-2024-12379](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2024-12379) | Medium | Denial of Service due to Unbounded Object Creation via the scopes parameter in a Personal Access Token in Gitlab EE|
| 28 | [CVE-2024-13054](https://nvd.nist.gov/vuln/detail/CVE-2024-13054) | Medium | Denial of Service Due to Inefficient Processing of Untrusted Input |
| 29 | [CVE-2025-31116](https://github.com/MobSF/Mobile-Security-Framework-MobSF/security/advisories/GHSA-fcfq-m8p6-gw56) | Medium | SSRF on assetlinks_check with DNS Rebinding |
| 30 | [CVE-2025-0549](https://about.gitlab.com/releases/2025/05/07/patch-release-gitlab-17-11-2-released/#partial-bypass-for-device-oauth-flow-using-cross-window-forgery) | Medium | Partial Bypass for Device OAuth flow using Cross Window Forgery |
| 31 | [GHSA-6p2v-wcv8-8j6w](https://github.com/stealthcopter/CaidoExploitGenerator/security/advisories/GHSA-6p2v-wcv8-8j6w) | Medium |  Arbitrary File Read by Copy as a Curl command in a Caido Plugin Exploit Generator - [advisory](https://github.com/stealthcopter/CaidoExploitGenerator/security/advisories/GHSA-6p2v-wcv8-8j6w) |
|32| [CVE-2025-0673](https://about.gitlab.com/releases/2025/06/11/patch-release-gitlab-18-0-2-released/?utm_medium=email&utm_source=marketo&utm_campaign=security+release+email&June+11+2025#cve-2025-0673---denial-of-service-impacts-gitlab-ceee) | High |an attacker can trigger an infinite redirect loop, potentially leading to a denial of service condition in Gitlab EE.  |
|33|CVE-2025-52481| Low | |



 ✨ ⚡
 
 
