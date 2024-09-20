---
# SPDX-License-Identifier: CC0-1.0
# SPDX-FileCopyrightText: 2019-2022 The Foundation for Public Code <info@publiccode.net>, https://standard.publiccode.net/AUTHORS
toc: false
---
# 政府開放原始碼協作指引

《公共程式標準》是一套支持公家機關一同協作開發軟體與政策，以及維護的準則。

《公共程式標準》為那些在建構自身開放原始碼解決方案的公家機關提供指引，以便他們未來能成功與其他地方的類似公部門單位互相協作，並且重複使用各自的成果。這份標準涵蓋寫給政策制定者、政府管理人員、開發人員與供應商的建議。《公共程式標準》支持公家機關透過協作方式，創造出好用、開放、易懂、課責、近用、永續的程式基底。這份標準從設計之初，就是要用於各種不同政府層級的程式基底，小從市政府，大到超國家組織都行。

《公共程式標準》將「[公共程式](glossary.md#public-code)」定義為：由公家機關所開發的開放原始碼軟體，同時包含協作與重複使用所需的政策與指引。

《公共程式標準》當中的準則，符合開放原始碼軟體開發的指引與最佳實務。

{% for page in site.pages %}{% if page.name == "foreword.md" %} 其他情境與背景資訊請參閱[序文](foreword.md)。 {% endif%}{% endfor %}

## 目次

* [讀者指引：如何解讀本標準](readers-guide.md)
* [詞彙表](glossary.md)
* [準則](criteria/){% assign sorted = site.pages | sort:"order" %}{% for page in
sorted %}{% if page.dir == "/criteria/" %}{% if page.name != "index.md" %}{%
if page.title %}
   * [{{page.title}}]({{page.url}}){% endif%}{% endif%}{% endif%}{% endfor %}
* [作者群](AUTHORS.md)
* [貢獻指引](CONTRIBUTING.md)
* [行為守則](CODE_OF_CONDUCT.md)
* [治理方式](GOVERNANCE.md)
* [版本歷史](CHANGELOG.md)
* [授權](license.html)

## 社群會議

我們通常在每月第一個週四的 15:00 (CET/CEST) 舉辦社群會議。[議程](https://write.publiccode.net/pads/Community-Call-Standard-for-Public-Code)在會議前
約一週的時間更新。您可以[註冊](https://odoo.publiccode.net/survey/start/594b9243-c7e5-4bc1-8714-35137c971842)
報名，會再寄送會議通話邀請函給您。

## 其他資源

* 本標準非官方的其他語言[社群翻譯](https://publiccodenet.github.io/community-translations-standard/)
* 公部門開放原始碼程式基底的《[標準遵循自我評估](https://publiccodenet.github.io/assessment-eligibility/)》
* Foundation for Public Code 執事人員用於程式基底審查的《[標準準則檢查清單](/docs/review-template.html)》
