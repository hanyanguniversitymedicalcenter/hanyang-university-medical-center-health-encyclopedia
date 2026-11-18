---
license: cc-by-4.0
language:
  - ko
  - en
pretty_name: Hanyang University Medical Center Health Encyclopedia (Korean and English)
tags:
  - medical
  - healthcare
  - health-education
  - korean
  - english
  - rag
---

# Hanyang University Medical Center Health Encyclopedia Dataset
# 한양대학교의료원 건강백과 데이터셋

**Languages:** [English](#english) | [한국어](#한국어)  
**License / 라이선스:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)  
**Source / 제공기관:** Hanyang University Medical Center · 한양대학교의료원

---

<a id="english"></a>
## English

### 1. Overview

The Hanyang University Medical Center Health Encyclopedia Dataset is a bilingual collection of general health information published by Hanyang University Medical Center in South Korea. It contains **311 Korean articles with content and 311 English articles**, totaling **622 articles with content**. The collection includes titles, introductions, tags, section headings, article text, source attribution, and links to the corresponding original pages.

The dataset is made available for health information services, research, AI development, model training, retrieval-augmented generation (RAG), and other lawful uses, including commercial applications, under **CC BY 4.0**. It is **not a substitute for medical diagnosis, treatment, or professional clinical judgment**.

The **311 Korean entries correspond one-to-one with the 311 English entries**, providing Korean and English versions of the same health encyclopedia topics.

#### Official websites and original sources

- [Hanyang University Medical Center](https://www.hyumc.com/)
- [Hanyang University Seoul Hospital](https://seoul.hyumc.com/)
- [Hanyang University Guri Hospital](https://guri.hyumc.com/)
- [Health Encyclopedia (Korean)](https://seoul.hyumc.com/hydic/)
- [Health Encyclopedia (English)](https://seoul.hyumc.com/hydicen/)
- [Hanyang University Seoul Hospital (English website)](https://seoul.hyumc.com/eng/)

Individual articles are linked in each dataset record via `ARTICLE_URL` or `article_url`.

### 2. Files and dataset size

| File | Description |
| --- | --- |
| `Korean_dictionary.xlsx` | Korean health encyclopedia: 311 entries |
| `Korean_dictionary.csv` | Korean dataset in CSV format; same content as the XLSX file |
| `Korean_dictionary.json` | Korean structured data: 311 records |
| `English_dictionary.xlsx` | English dataset: 311 entries |
| `English_dictionary.csv` | English dataset in CSV format; same content as the XLSX file |
| `English_dictionary.json` | English structured data: 311 records |

- **Articles with content:** 622 (Korean 311; English 311)
- **Total characters:** 1,406,509 across titles, introductions, tags, section headings, and article bodies (Korean: 407,889; English: 998,620)
- **CSV encoding:** UTF-8 with BOM; comma-separated; fields containing line breaks are quoted
- **Article source links:** `ARTICLE_URL` is the final column in XLSX/CSV files; `article_url` is the final field of each JSON record
- **Source attribution:** `Hanyang University Medical Center` for English content and `한양대학교의료원` for Korean content

### 3. Sources and preparation

The collection was developed from approximately **10 years of medical articles and columns** authored by medical professionals, including contributions for external publications and columns selected for a bimonthly publication by a committee composed of physicians. The original editorial process involved clinician authorship and editorial cross-checking.

The selection and preparation process considered **recency, source reliability, medical accuracy, and public relevance**. Limiting the source period to approximately 10 years was intended to reduce reliance on older material; it does not guarantee that every statement remains current.

The preparation workflow included:

1. Selecting and organizing source materials, then writing, editing, or translating the entries into an encyclopedia-style format.
2. Reviewing content with multiple generative AI systems, including ChatGPT, Claude, and Gemini. The Korean content underwent **at least seven rounds** of AI-assisted cross-checking, and the English content underwent **at least three rounds**.
3. Revising or excluding statements with insufficiently established medical consensus, and using conservative wording to reduce the risk of overconfident self-diagnosis or treatment decisions.
4. Making the database content available for an internal clinician review period following database entry: approximately **two months for Korean content** and **one month for English content**. The material was available for review by faculty physicians across Hanyang University Seoul Hospital (approximately 260) and Hanyang University Guri Hospital (approximately 160).

These steps describe the dataset's preparation and review process. **AI-assisted cross-checking and the clinician review period do not constitute a guarantee of complete error detection, individual approval of every entry, or validation for clinical use.** Users should independently verify medical information against current clinical guidelines and authoritative sources before applying or redistributing it.

### 4. License and attribution

The textual dataset is released under **[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)**. Subject to the license terms, users may copy, redistribute, adapt, transform, build upon, and use the dataset **for commercial or noncommercial purposes**.

When using or redistributing the dataset, users must:

- Credit **Hanyang University Medical Center** as the source.
- Include the **original article URL** provided in the relevant record, wherever reasonably practicable for the form of use.
- Provide a link to the **CC BY 4.0 license**.
- **Indicate whether changes were made**, including translations, edits, abridgments, or other modifications, and retain notices of prior modifications where applicable.

**Suggested attribution:**

> Source: Hanyang University Medical Center, Health Encyclopedia Dataset. Original article: [use the `article_url` / `ARTICLE_URL` value]. Licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). [Indicate modifications, if any.]

**Names, trademarks, and endorsement:** CC BY 4.0 does **not** grant rights to Hanyang University Medical Center's trademarks, logos, seals, branding, or other rights outside the scope of the license. Source attribution is permitted and required, but users must not imply that Hanyang University Medical Center sponsors, endorses, certifies, or officially approves their products, services, models, or derivative works unless separately authorized.

### 5. Medical disclaimer and limitations

This information is provided **for general reference, education, research, and development only**. It does not replace professional medical advice, diagnosis, prescriptions, or treatment. Symptoms, individual circumstances, and treatment outcomes can vary. For diagnosis and treatment, consult a qualified medical professional.

**If symptoms are severe or a medical emergency is suspected, seek emergency care immediately. In South Korea, call 119 or visit the nearest emergency department; elsewhere, use the local emergency number.**

Medical knowledge and clinical recommendations change over time. Despite multiple review steps, the dataset may contain omissions, outdated statements, translation issues, or other errors. AI-generated outputs based on the dataset may differ from the source material and may introduce additional inaccuracies. Users should independently verify information before relying on it, especially for medical or safety-critical applications.

**The dataset is provided “as is,” without warranties of accuracy, completeness, currency, fitness for a particular purpose, or clinical suitability. Hanyang University Medical Center disclaims liability for health, financial, legal, or other consequences arising from reliance on, interpretation of, or application of the dataset or derivative AI outputs, to the extent permitted by applicable law.** No use of this dataset establishes a physician–patient relationship.

### 6. Data handling notes

- The dataset contains **311 corresponding Korean–English article pairs**, with each Korean entry matched to its English version.
- Article URLs should be preserved where possible to maintain provenance and enable users to consult the original content.

---

<a id="한국어"></a>
## 한국어

### 1. 데이터셋 소개

'한양대학교의료원 건강백과 데이터셋'은 한양대학교의료원이 공개한 건강정보를 국문·영문으로 정리한 자료입니다. **국문 본문 수록 항목 311건, 영문 311건 등 총 622건**으로 구성했습니다. 항목별 제목, 소개, 태그, 소제목, 본문, 출처, 홈페이지 원문 링크를 제공합니다.

건강정보 서비스, 연구, AI 개발, 모델 학습, 검색증강생성(RAG) 등에 활용할 수 있으며, **CC BY 4.0에 따라 상업적 이용도 허용**합니다. 다만 이 자료는 **진단·치료·처방이나 의료진의 전문적 판단을 대신하지 않습니다**.

**국문 311건과 영문 311건은 항목별로 1:1 대응**하며, 동일한 건강백과 주제의 국문·영문 자료를 제공합니다.

#### 공식 홈페이지 및 건강백과 원문

- [한양대학교의료원](https://www.hyumc.com/)
- [한양대학교병원(서울)](https://seoul.hyumc.com/)
- [한양대학교구리병원](https://guri.hyumc.com/)
- [건강백과(국문)](https://seoul.hyumc.com/hydic/)
- [건강백과(영문)](https://seoul.hyumc.com/hydicen/)
- [한양대학교병원 영문 홈페이지](https://seoul.hyumc.com/eng/)

항목별 원문 주소는 각 파일의 `ARTICLE_URL` 또는 `article_url`에 수록돼 있습니다.

### 2. 제공 파일 및 규모

| 파일명 | 내용 |
| --- | --- |
| `Korean_dictionary.xlsx` | 국문 건강백과 311건 |
| `Korean_dictionary.csv` | 국문 XLSX와 같은 내용의 CSV |
| `Korean_dictionary.json` | 국문 구조화 데이터 311건 |
| `English_dictionary.xlsx` | 영문 건강백과 311건 |
| `English_dictionary.csv` | 영문 XLSX와 같은 내용의 CSV |
| `English_dictionary.json` | 영문 구조화 데이터 311건 |

- **본문 수록 항목:** 국문 311건·영문 311건, 총 622건
- **문자 수:** 제목·소개·태그·소제목·본문 합계 1,406,509자(국문 407,889자·영문 998,620자)
- **CSV 형식:** UTF-8(BOM 포함), 쉼표 구분. 줄바꿈이 포함된 필드는 큰따옴표로 묶음
- **원문 주소:** XLSX·CSV의 마지막 `ARTICLE_URL` 열, JSON의 마지막 `article_url` 필드에 수록
- **출처 표기:** 국문 `한양대학교의료원`, 영문 `Hanyang University Medical Center`

### 3. 원자료와 제작·검증 과정

이 데이터셋은 **최근 약 10년간 의료진이 집필한 기고문**과 **의료진으로 구성된 위원회가 선정한 격월간지 건강 칼럼** 등을 바탕으로 구축했습니다. 원자료는 의료진의 집필과 편집인의 교차 확인 등 편집 과정을 거쳐 제작됐습니다.

원자료 선정과 가공에는 **최신성, 출처의 신뢰성, 의학적 정확성, 정보 수요 및 시의성**을 고려했습니다. 비교적 최근 10년간의 자료를 중심으로 구성해 오래된 정보의 비중을 줄이고자 했으나, 모든 내용이 현재의 진료지침과 일치한다는 의미는 아닙니다.

제작 과정은 다음과 같습니다.

1. **원자료 선정 및 구성:** 건강정보 원문을 선별하고 백과사전 형식에 맞게 작성·편집·번역
2. **생성형 AI 교차 검토:** ChatGPT, Claude, Gemini 등 복수의 AI를 활용해 **국문 7차례 이상, 영문 3차례 이상** 교차 확인
3. **보수적 수정·선별:** 의학적 합의가 충분하지 않은 설명은 수정하거나 제외하고, 독자의 자의적인 진단·치료 또는 과신을 유발할 수 있는 표현을 점검
4. **의료진 확인 기간:** 데이터베이스 탑재 후 **국문 약 2개월, 영문 약 1개월**의 의료진 확인 기간 운영. 서울병원 약 260명·구리병원 약 160명의 교수 의료진이 자료를 살펴볼 수 있도록 운영

위 절차는 자료 제작과 확인 과정을 설명한 것입니다. **AI 교차 검토와 의료진 확인 기간이 모든 오류의 제거, 모든 항목에 대한 개별 의료진의 승인, 임상적 사용 적합성의 보증을 뜻하지는 않습니다.** 이용자는 최신 진료지침과 공신력 있는 자료를 통해 내용을 다시 검증할 것을 권장합니다.

### 4. 이용조건 및 출처 표기

본 데이터셋의 텍스트는 **[저작자표시 4.0 국제(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.ko)** 조건으로 공개합니다. 해당 조건을 준수하면 **상업적·비상업적 이용, 복제, 재배포, 수정, 번역, 가공 및 2차 저작물 작성**이 가능합니다.

이용·재배포 시 다음 사항을 준수해야 합니다.

- **출처 명시:** `한양대학교의료원(Hanyang University Medical Center)` 표기
- **원문 연결:** 해당 항목의 `ARTICLE_URL` 또는 `article_url`에 기재된 홈페이지 원문 링크 표시(이용 방식에 맞게 합리적으로 가능한 범위에서)
- **라이선스 안내:** CC BY 4.0 명칭 및 링크 표시
- **변경사항 표시:** 번역·요약·수정·편집 등 변경 여부를 명시하고, 기존 변경 표시가 있으면 유지

**출처 표기 예시**

> 출처: 한양대학교의료원 건강백과 데이터셋. 원문: [해당 항목의 `ARTICLE_URL` 또는 `article_url`]. 이용허락: CC BY 4.0(https://creativecommons.org/licenses/by/4.0/deed.ko). [수정한 경우 변경사항 기재]

**상표·로고 및 공식 승인 오인 방지:** CC BY 4.0은 한양대학교의료원의 **명칭·로고·상표·표장 등 별도의 권리 사용을 허락하는 라이선스가 아닙니다.** 출처를 정확히 밝히기 위한 의료원 명칭 사용은 가능하지만, 별도 허가 없이 의료원이 이용자의 상품·서비스·AI 모델·가공 자료를 **후원·인증·추천·공식 승인한 것처럼 표시하거나 오인하게 해서는 안 됩니다.**

### 5. 의료정보 이용 시 주의사항 및 면책

본 자료는 **일반적인 건강정보 제공과 교육·연구·개발을 위한 참고자료**입니다. 전문적인 의학적 자문, 진단, 처방, 치료를 대신하지 않습니다. 증상과 치료 결과는 개인에 따라 다를 수 있으므로, 정확한 진단과 치료를 위해 의료진의 진료를 받으시기 바랍니다.

**증상이 심하거나 응급상황으로 판단되면 즉시 119 또는 가까운 응급실을 이용하시기 바랍니다.** 해외에서는 현지 응급전화 또는 응급의료기관을 이용해야 합니다.

의학 지식과 권고는 시간이 지나면서 달라질 수 있습니다. 여러 차례 검토했더라도 누락, 오래된 정보, 번역상 차이, 기타 오류가 남아 있을 수 있습니다. 이 자료로 학습하거나 검색한 AI의 답변 역시 원문과 다르거나 부정확할 수 있습니다. 특히 진단·치료 등 안전에 영향을 주는 용도로 사용할 때는 관련 내용을 별도로 검증해야 합니다.

**본 데이터셋은 정확성·완전성·최신성·특정 목적 적합성 또는 임상적 적합성에 대한 보증 없이 현 상태대로 제공됩니다. 한양대학교의료원은 관련 법령이 허용하는 범위에서 자료나 이를 활용한 AI 답변의 해석·신뢰·적용으로 발생하는 건강상·재산상·법적 문제 및 기타 손해에 대해 책임을 지지 않습니다.** 데이터셋 이용만으로 의료진과 이용자 사이에 진료관계가 성립하지 않습니다.

### 6. 데이터 활용 참고사항

- **국문 311건과 영문 311건은 항목별로 1:1 대응**하는 국·영문 건강백과 자료임
- 출처 추적과 원문 확인을 위해 가능하면 원문 링크를 함께 유지할 것

---

**Copyright © Hanyang University Medical Center. Dataset text licensed under CC BY 4.0.**  
**저작권 © 한양대학교의료원. 데이터셋 텍스트에 CC BY 4.0 적용.**
