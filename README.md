

<h1 align="center">
Nuclei Templates
</h1>
<h4 align="center">Community curated list of templates for the nuclei engine to find security vulnerabilities in applications.</h4>


<p align="center">
<a href="https://github.com/projectdiscovery/nuclei-templates/issues"><img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat"></a>
<a href="https://github.com/projectdiscovery/nuclei-templates/releases"><img src="https://img.shields.io/github/release/projectdiscovery/nuclei-templates"></a>
<a href="https://twitter.com/pdnuclei"><img src="https://img.shields.io/twitter/follow/pdnuclei.svg?logo=twitter"></a>
<a href="https://discord.gg/projectdiscovery"><img src="https://img.shields.io/discord/695645237418131507.svg?logo=discord"></a>
</p>
      
<p align="center">
  <a href="https://nuclei.projectdiscovery.io/templating-guide/">Documentation</a> •
  <a href="#-contributions">Contributions</a> •
  <a href="#-discussion">Discussion</a> •
  <a href="#-community">Community</a> •
  <a href="https://nuclei.projectdiscovery.io/faq/templates/">FAQs</a> •
  <a href="https://discord.gg/projectdiscovery">Join Discord</a>
</p>

----

Templates are the core of the [nuclei scanner](https://github.com/projectdiscovery/nuclei) which powers the actual scanning engine.
This repository stores and houses various templates for the scanner provided by our team, as well as contributed by the community.
We hope that you also contribute by sending templates via **pull requests** or [Github issues](https://github.com/projectdiscovery/nuclei-templates/issues/new?assignees=&labels=&template=submit-template.md&title=%5Bnuclei-template%5D+) to grow the list.


## Nuclei Templates overview


An overview of the nuclei template project, including statistics on unique tags, author, directory, severity, and type of templates. The table below contains the top ten statistics for each matrix; an expanded version of this is [available here](TEMPLATES-STATS.md), and also available in [JSON](TEMPLATES-STATS.json) format for integration.

<table>
<tr>
<td> 

## Nuclei Templates Top 10 statistics

|    TAG    | COUNT |    AUTHOR     | COUNT |    DIRECTORY     | COUNT | SEVERITY | COUNT |  TYPE   | COUNT |
|-----------|-------|---------------|-------|------------------|-------|----------|-------|---------|-------|
| cve       |   666 | dhiyaneshdk   |   248 | cves             |   674 | info     |   615 | http    |  1859 |
| panel     |   236 | pikpikcu      |   246 | vulnerabilities  |   284 | high     |   535 | file    |    46 |
| lfi       |   228 | pdteam        |   198 | exposed-panels   |   235 | medium   |   413 | network |    39 |
| xss       |   225 | daffainfo     |   183 | exposures        |   186 | critical |   236 | dns     |    11 |
| exposure  |   221 | geeknik       |   150 | technologies     |   170 | low      |   161 |         |       |
| wordpress |   206 | dwisiswant0   |   132 | misconfiguration |   129 |          |       |         |       |
| rce       |   193 | gy741         |    72 | takeovers        |    71 |          |       |         |       |
| cve2020   |   159 | madrobot      |    62 | default-logins   |    54 |          |       |         |       |
| wp-plugin |   139 | princechaddha |    55 | file             |    46 |          |       |         |       |
| cve2021   |   112 | pussycat0x    |    55 | workflows        |    35 |          |       |         |       |

**150 directories, 2015 files**.

</td>
</tr>
</table>

📖 Documentation
-----

Please navigate to https://nuclei.projectdiscovery.io for detailed documentation to **build** new or your own **custom** templates.
We have also added a set of templates to help you understand how things work.

💪 Contributions
-----

Nuclei-templates is powered by major contributions from the community.
[Template contributions ](https://github.com/projectdiscovery/nuclei-templates/issues/new?assignees=&labels=&template=submit-template.md&title=%5Bnuclei-template%5D+), [Feature Requests](https://github.com/projectdiscovery/nuclei-templates/issues/new?assignees=&labels=&template=feature_request.md&title=%5BFeature%5D+) and [Bug Reports](https://github.com/projectdiscovery/nuclei-templates/issues/new?assignees=&labels=&template=bug_report.md&title=%5BBug%5D+) are more than welcome.

💬 Discussion
-----

Have questions / doubts / ideas to discuss?
Feel free to open a discussion on [Github discussions](https://github.com/projectdiscovery/nuclei-templates/discussions) board.

👨‍💻 Community
-----

You are welcome to join our [Discord Community](https://discord.gg/KECAGdH).
You can also follow us on [Twitter](https://twitter.com/pdiscoveryio) to keep up with everything related to projectdiscovery.

💡 Notes
-----
-  Use YAMLlint (e.g. [yamllint](http://www.yamllint.com/) to validate the syntax of templates before sending pull requests.


Thanks again for your contribution and keeping this community vibrant. :heart:
