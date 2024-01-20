<h1 align="center"> Hi there, I’m Alessio 👋 </h1>

### Summary

- [Blogs](#blogs)
- [CTF Challenges](#ctf-challenges)
- [CVE](#cve)
- [Other Security Advisories](#other-security-advisories)
- [Public Acknowledgements](#public-acknowledgements)
- [Academic Papers](#academic-papers)

---
### Blogs
- [Rediscovering argument injection when using VCS tools - git and mercurial](https://snyk.io/blog/argument-injection-when-using-git-and-mercurial/)
- [JavaScript type confusion: Bypassed input validation (and how to remediate)](https://snyk.io/blog/remediate-javascript-type-confusion-bypassed-input-validation/)

---
### CTF Challenges 
- Damn Vulnerable Defi - [solutions](https://github.com/dellalibera/damn-vulnerable-defi-solutions) | [write-ups](https://github.com/dellalibera/ctf-writeups/tree/main/Damn_Vulnerable_DeFI)
- EVM Puzzles - [solutions](https://github.com/dellalibera/evm-puzzles-solutions) | [write-ups](https://github.com/dellalibera/ctf-writeups/tree/main/EVM_Puzzles)
- Offensive Vyper - [solutions](https://github.com/dellalibera/offensive_vyper-solutions) | [write-ups](https://github.com/dellalibera/ctf-writeups/tree/main/Offensive_Vyper)

---
### CVE

| # | Reference     | Vulnerability  | Project    | Language |
|---|-------------- | -------------- | ---------- |----------|
| 71  | [CVE-2023-26148](https://www.cve.org/CVERecord?id=CVE-2023-26148)                | CRLF Injection               | **libhv**                 | C/C++                     |
| 70  | [CVE-2023-26147](https://www.cve.org/CVERecord?id=CVE-2023-26147)                | HTTP Response Splitting      | **libhv**                 | C/C++                     |
| 69  | [CVE-2023-26146](https://www.cve.org/CVERecord?id=CVE-2023-26146)                | Cross-Site Scripting (XSS)   | **libhv**                 | C/C++                     |
| 68  | [CVE-2023-26142](https://www.cve.org/CVERecord?id=CVE-2023-26142)                | HTTP Response Splitting      | **Crow**                  | C/C++                     |
| 67  | [CVE-2023-26138](https://www.cve.org/CVERecord?id=CVE-2023-26138)                | CRLF Injection               | **drogon**                | C/C++                     |
| 66  | [CVE-2023-26137](https://www.cve.org/CVERecord?id=CVE-2023-26137)                | HTTP Response Splitting      | **drogon**                | C/C++                     |
| 65  | [CVE-2022-25883](https://www.cve.org/CVERecord?id=CVE-2022-25883)                | Regular Expression Denial of Service (ReDoS) | **semver**                | JavaScript                |
| 64  | [CVE-2023-26131](https://www.cve.org/CVERecord?id=CVE-2023-26131)                | Cross-Site Scripting (XSS)   | **xyproto/algernon**      | Go                        |
| 63  | [CVE-2023-26130](https://www.cve.org/CVERecord?id=CVE-2023-26130)                | CRLF Injection               | **cpp-httplib**           | C/C++                     |
| 62  | [CVE-2023-26103](https://www.cve.org/CVERecord?id=CVE-2023-26103)                | Regular Expression Denial of Service (ReDoS) | **deno**                  | Rust                      |
| 61  | [CVE-2023-0040](https://www.cve.org/CVERecord?id=CVE-2023-0040)                  | CRLF Injection               | **async-http-client**     | Swift                     |
| 60  | [CVE-2022-3918](https://www.cve.org/CVERecord?id=CVE-2022-3918)                  | CRLF Injection               | **apple/swift-corelibs-foundation** | Swift                     |
| 59  | [CVE-2022-3215](https://www.cve.org/CVERecord?id=CVE-2022-3215)                  | HTTP Response Splitting      | **apple/swift-nio**       | Swift                     |
| 58  | [CVE-2022-24065](https://www.cve.org/CVERecord?id=CVE-2022-24065)                | Command Injection            | **cookiecutter**          | Python                    |
| 57  | [CVE-2022-26945](https://www.cve.org/CVERecord?id=CVE-2022-26945)                | Command Injection            | **hashicorp/go-getter**   | Go                        |
| 56  | [CVE-2022-25878](https://www.cve.org/CVERecord?id=CVE-2022-25878)                | Prototype Pollution          | **protobufjs**            | JavaScript                |
| 55  | [CVE-2022-25865](https://www.cve.org/CVERecord?id=CVE-2022-25865)                | Command Injection            | **workspace-tools**       | JavaScript                |
| 54  | [CVE-2022-21190](https://www.cve.org/CVERecord?id=CVE-2022-21190)                | Prototype Pollution          | **convict**               | JavaScript                |
| 53  | [CVE-2022-29184](https://www.cve.org/CVERecord?id=CVE-2022-29184)                | Remote Code Execution (RCE)  | **gocd**                  | Java                      |
| 52  | [CVE-2022-21189](https://www.cve.org/CVERecord?id=CVE-2022-21189)                | Prototype Pollution          | **dexie**                 | JavaScript                |
| 51  | [CVE-2022-25303](https://www.cve.org/CVERecord?id=CVE-2022-25303)                | Cross-Site Scripting (XSS)   | **whoogle-search**        | Python                    |
| 50  | [CVE-2022-25866](https://www.cve.org/CVERecord?id=CVE-2022-25866)                | Command Injection            | **czproject/git-php**     | PHP                       |
| 49  | [CVE-2022-25648](https://www.cve.org/CVERecord?id=CVE-2022-25648)                | Command Injection            | **git**                   | Ruby                      |
| 48  | [CVE-2022-25766](https://www.cve.org/CVERecord?id=CVE-2022-25766)                | Remote Code Execution (RCE)  | **ungit**                 | JavaScript                |
| 47  | [CVE-2022-24440](https://www.cve.org/CVERecord?id=CVE-2022-24440)                | Command Injection            | **cocoapods-downloader**  | Ruby                      |
| 46  | [CVE-2022-24433](https://www.cve.org/CVERecord?id=CVE-2022-24433)                | Command Injection            | **simple-git**            | JavaScript                |
| 45  | [CVE-2022-23915](https://www.cve.org/CVERecord?id=CVE-2022-23915)                | Remote Code Execution (RCE)  | **Weblate**               | Python                    |
| 44  | [CVE-2022-21803](https://www.cve.org/CVERecord?id=CVE-2022-21803)                | Prototype Pollution          | **nconf**                 | JavaScript                |
| 43  | [CVE-2022-21235](https://www.cve.org/CVERecord?id=CVE-2022-21235)                | Command Injection            | **Masterminds/vcs**       | Go                        |
| 42  | [CVE-2022-21223](https://www.cve.org/CVERecord?id=CVE-2022-21223)                | Command Injection            | **cocoapods-downloader**  | Ruby                      |
| 41  | [CVE-2022-21187](https://www.cve.org/CVERecord?id=CVE-2022-21187)                | Command Injection            | **libvcs**                | Python                    |
| 40  | [CVE-2021-23820](https://www.cve.org/CVERecord?id=CVE-2021-23820)                | Prototype Pollution          | **json-pointer**          | JavaScript                |
| 39  | [CVE-2021-23807](https://www.cve.org/CVERecord?id=CVE-2021-23807)                | Prototype Pollution          | **jsonpointer**           | JavaScript                |
| 38  | [CVE-2021-23784](https://www.cve.org/CVERecord?id=CVE-2021-23784)                | Cross-Site Scripting (XSS)   | **tempura**               | JavaScript                |
| 37  | [CVE-2021-23682](https://www.cve.org/CVERecord?id=CVE-2021-23682)                | Prototype Pollution          | **litespeed.js**          | JavaScript                |
| 37  | [CVE-2021-23682](https://www.cve.org/CVERecord?id=CVE-2021-23682)                | Prototype Pollution          | **appwrite/server-ce**    | JavaScript                |
| 36  | [CVE-2021-23624](https://www.cve.org/CVERecord?id=CVE-2021-23624)                | Prototype Pollution          | **dotty**                 | JavaScript                |
| 35  | [CVE-2021-23597](https://www.cve.org/CVERecord?id=CVE-2021-23597)                | Denial of Service (DoS)      | **fastify-multipart**     | JavaScript                |
| 34  | [CVE-2021-23509](https://www.cve.org/CVERecord?id=CVE-2021-23509)                | Prototype Pollution          | **json-ptr**              | JavaScript                |
| 33  | [CVE-2021-23472](https://www.cve.org/CVERecord?id=CVE-2021-23472)                | Cross-Site Scripting (XSS)   | **bootstrap-table**       | JavaScript                |
| 32  | [CVE-2021-23447](https://www.cve.org/CVERecord?id=CVE-2021-23447)                | Cross-Site Scripting (XSS)   | **teddy**                 | JavaScript                |
| 31  | [CVE-2021-23445](https://www.cve.org/CVERecord?id=CVE-2021-23445)                | Cross-Site Scripting (XSS)   | **datatables.net**        | JavaScript                |
| 30  | [CVE-2021-23444](https://www.cve.org/CVERecord?id=CVE-2021-23444)                | Prototype Pollution          | **jointjs**               | JavaScript                |
| 29  | [CVE-2021-23443](https://www.cve.org/CVERecord?id=CVE-2021-23443)                | Cross-Site Scripting (XSS)   | **edge.js**               | JavaScript                |
| 28  | [CVE-2021-23440](https://www.cve.org/CVERecord?id=CVE-2021-23440)                | Prototype Pollution          | **set-value**             | JavaScript                |
| 27  | [CVE-2021-23438](https://www.cve.org/CVERecord?id=CVE-2021-23438)                | Prototype Pollution          | **mpath**                 | JavaScript                |
| 26  | [CVE-2021-23436](https://www.cve.org/CVERecord?id=CVE-2021-23436)                | Prototype Pollution          | **immer**                 | JavaScript                |
| 25  | [CVE-2021-23434](https://www.cve.org/CVERecord?id=CVE-2021-23434)                | Prototype Pollution          | **object-path**           | JavaScript                |
| 24  | [CVE-2021-23390](https://www.cve.org/CVERecord?id=CVE-2021-23390)                | Arbitrary Code Execution     | **total4**                | JavaScript                |
| 23  | [CVE-2021-23389](https://www.cve.org/CVERecord?id=CVE-2021-23389)                | Arbitrary Code Execution     | **total.js**              | JavaScript                |
| 22  | [CVE-2021-23358](https://www.cve.org/CVERecord?id=CVE-2021-23358)                | Arbitrary Code Execution     | **underscore**            | JavaScript                |
| 21  | [CVE-2021-23352](https://www.cve.org/CVERecord?id=CVE-2021-23352)                | Command Injection            | **madge**                 | JavaScript                |
| 20  | [CVE-2021-23335](https://www.cve.org/CVERecord?id=CVE-2021-23335)                | LDAP Injection               | **is-user-valid**         | JavaScript                |
| 19  | [CVE-2020-8186](https://www.cve.org/CVERecord?id=CVE-2020-8186)                  | Command Injection            | **devcert**               | JavaScript                |
| 18  | [CVE-2020-7792](https://www.cve.org/CVERecord?id=CVE-2020-7792)                  | Prototype Pollution          | **mout**                  | JavaScript                |
| 17  | [CVE-2020-7789](https://www.cve.org/CVERecord?id=CVE-2020-7789)                  | Command Injection            | **node-notifier**         | JavaScript                |
| 16  | [CVE-2020-7777](https://www.cve.org/CVERecord?id=CVE-2020-7777)                  | Arbitrary Code Execution     | **jsen**                  | JavaScript                |
| 15  | [CVE-2020-7772](https://www.cve.org/CVERecord?id=CVE-2020-7772)                  | Prototype Pollution          | **doc-path**              | JavaScript                |
| 14  | [CVE-2020-7770](https://www.cve.org/CVERecord?id=CVE-2020-7770)                  | Prototype Pollution          | **json8**                 | JavaScript                |
| 13  | [CVE-2020-7766](https://www.cve.org/CVERecord?id=CVE-2020-7766)                  | Prototype Pollution          | **json-ptr**              | JavaScript                |
| 12  | [CVE-2020-7746](https://www.cve.org/CVERecord?id=CVE-2020-7746)                  | Prototype Pollution          | **chart.js**              | JavaScript                |
| 11  | [CVE-2020-7743](https://www.cve.org/CVERecord?id=CVE-2020-7743)                  | Prototype Pollution          | **mathjs**                | JavaScript                |
| 10  | [CVE-2020-7742](https://www.cve.org/CVERecord?id=CVE-2020-7742)                  | Prototype Pollution          | **simpl-schema**          | JavaScript                |
| 9   | [CVE-2020-28499](https://www.cve.org/CVERecord?id=CVE-2020-28499)                | Prototype Pollution          | **merge**                 | JavaScript                |
| 8   | [CVE-2020-28495](https://www.cve.org/CVERecord?id=CVE-2020-28495)                | Prototype Pollution          | **total.js**              | JavaScript                |
| 7   | [CVE-2020-28494](https://www.cve.org/CVERecord?id=CVE-2020-28494)                | Command Injection            | **total.js**              | JavaScript                |
| 6   | [CVE-2020-28480](https://www.cve.org/CVERecord?id=CVE-2020-28480)                | Prototype Pollution          | **jointjs**               | JavaScript                |
| 5   | [CVE-2020-28478](https://www.cve.org/CVERecord?id=CVE-2020-28478)                | Prototype Pollution          | **gsap**                  | JavaScript                |
| 4   | [CVE-2020-28477](https://www.cve.org/CVERecord?id=CVE-2020-28477)                | Prototype Pollution          | **immer**                 | JavaScript                |
| 3   | [CVE-2020-28464](https://www.cve.org/CVERecord?id=CVE-2020-28464)                | Arbitrary Code Execution     | **djv**                   | JavaScript                |
| 2   | [CVE-2020-28458](https://www.cve.org/CVERecord?id=CVE-2020-28458)                | Prototype Pollution          | **datatables.net**        | JavaScript                |
| 1   | [CVE-2020-28442](https://www.cve.org/CVERecord?id=CVE-2020-28442)                | Prototype Pollution          | **js-data**               | JavaScript                |

---
### Other Security Advisories

| # | Reference     | Vulnerability  | Project    | Language |
|---|-------------- | -------------- | ---------- |----------|
| 23  | [Link](https://github.com/grafana/grafana-json-datasource/blob/main/CHANGELOG.md#v135---2023-04-05) | Cross-Site Scripting (XSS)   | **grafana/grafana-json-datasource** | JavaScript                |
| 22  | [Link](https://discourse.mozilla.org/t/security-fix-repository-url-validation/94362) | Remote Code Execution (RCE)  | **mozilla/pontoon**       | Python                    |
| 21  | [Snyk Advisory](https://security.snyk.io/vuln/SNYK-JS-STYLEDICTIONARY-1080632)   | Prototype Pollution          | **style-dictionary**      | JavaScript                |
| 20  | [Snyk Advisory](https://security.snyk.io/vuln/SNYK-JS-HIGHCHARTS-1018906)        | Prototype Pollution          | **highcharts**            | JavaScript                |
| 19  | [Snyk Advisory](https://security.snyk.io/vuln/SNYK-JS-JIFF-1017118)              | Prototype Pollution          | **jiff**                  | JavaScript                |
| 18  | [Snyk Advisory](https://security.snyk.io/vuln/SNYK-JS-I18NEXT-585930)            | Prototype Pollution          | **i18next**               | JavaScript                |
| 17  | [Snyk Advisory](https://security.snyk.io/vuln/SNYK-JS-PROPS-1015750)             | Unsafe Deserialization       | **props**                 | JavaScript                |
| 16  | [HackerOne Report](https://hackerone.com/reports/1001218)                        | Prototype Pollution          | **@firebase/util**        | JavaScript                |
| 15  | [HackerOne Report](https://hackerone.com/reports/907311)                         | LDAP Injection               | **meemo-app**             | JavaScript                |
| 14  | [HackerOne Report](https://hackerone.com/reports/906959)                         | LDAP Injection               | **cloudron-surfer**       | JavaScript                |
| 13  | [HackerOne Report](https://hackerone.com/reports/858674)                         | Command Injection            | **wireguard-wrapper**     | JavaScript                |
| 12  | [HackerOne Report](https://hackerone.com/reports/871156)                         | Prototype Pollution          | **plain-object-merge**    | JavaScript                |
| 11  | [HackerOne Report](https://hackerone.com/reports/878339)                         | Prototype Pollution          | **extend-merge**          | JavaScript                |
| 10  | [HackerOne Report](https://hackerone.com/reports/871071)                         | Command Injection            | **gfc**                   | JavaScript                |
| 9   | [HackerOne Report](https://hackerone.com/reports/864354)                         | Command Injection            | **diskstats**             | JavaScript                |
| 8   | [HackerOne Report](https://hackerone.com/reports/878394)                         | Prototype Pollution          | **objtools**              | JavaScript                |
| 7   | [HackerOne Report](https://hackerone.com/reports/877515)                         | Prototype Pollution          | **keyd**                  | JavaScript                |
| 6   | [HackerOne Report](https://hackerone.com/reports/856588)                         | Cross-Site Scripting (XSS)   | **flsaba**                | JavaScript                |
| 5   | [HackerOne Report](https://hackerone.com/reports/863956)                         | Command Injection            | **extra-asciinema**       | JavaScript                |
| 4   | [HackerOne Report](https://hackerone.com/reports/864777)                         | Command Injection            | **vboxmanage.js**         | JavaScript                |
| 3   | [HackerOne Report](https://hackerone.com/reports/863944)                         | Command Injection            | **extra-ffmpeg**          | JavaScript                |
| 2   | [HackerOne Report](https://hackerone.com/reports/878332)                         | Prototype Pollution          | **object-path-set**       | JavaScript                |
| 1   | [HackerOne Report](https://hackerone.com/reports/865168)                         | Command Injection            | **xps**                   | JavaScript                |

---
### Public Acknowledgements
- Swift forums:
    - CVE-2023-0040: [Swift Forum Announcement](https://forums.swift.org/t/asynchttpclient-crlf-injection-in-http-request-headers-cve-2023-0040/62604)
    - CVE-2022-3215: [Swift Forum Announcement](https://forums.swift.org/t/cve-2022-3215-improper-neutralization-of-crlf-sequences-in-http-headers-http-response-splitting-in-swift-nio/60532)
- Mozilla Web Hall of Fame: [1st Quarter 2022](https://www.mozilla.org/en-US/security/bug-bounty/web-hall-of-fame/)
- gocd: [releases 22.1.0](https://www.gocd.org/releases/#22-1-0)
- hashicorp: [HCSEC-2022-13](https://discuss.hashicorp.com/t/hcsec-2022-13-multiple-vulnerabilities-in-go-getter-library/39930)
- Fastweb Hall of Fame: [2020](https://www.fastweb.it/corporate/responsible-disclosure/?lng=EN)
- TIM Hall of Fame: [2020](https://www.gruppotim.it/en/footer/responsible-disclosure.html)

---
### Academic Papers
- Are mHealth Apps Secure? A Case Study. Chiara Braghin, Stelvio Cimato, and Alessio Della Libera. *In: 2018 IEEE 42nd
Annual Computer Software and Applications Conference, COMPSAC 2018, Tokyo, Japan, 23-27 July 2018, Volume 2. pp. 335-340.* doi:
[10.1109/COMPSAC.2018.10253](https://ieeexplore.ieee.org/document/8377881)
