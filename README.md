# CRediT Generator

CRediT Generator prepares the CRediT paragraph for your scientific publication. The names and roles can be saved in a standardized XML file to be used again during manuscript revision process to add new authors or as a source file for journal submission system. 

[![CRediT Generator](/assets/CRediT-solid-01.png)](http://credit.metabolomics.fgu.cas.cz)

The CRediT (Contributor Roles Taxonomy) system provides a standardized and transparent way to recognize the diverse contributions of authors in scientific publications. By categorizing roles such as data curation, writing, supervision, and conceptualization, CRediT ensures that each contributor receives appropriate credit for their specific work, preventing disputes over authorship and clarifying responsibilities. This is especially valuable in the context of Open Science, where transparency and accountability are paramount. Open Science promotes the sharing of research outputs and processes, and the implementation of CRediT enhances this by making contributions visible and traceable. This not only facilitates collaboration but also supports nuanced citation practices, ensuring a fair and accurate representation of contributions in multidisciplinary research and large collaborative projects.

# How to use?

- use the [CRediT Generator online](http://credit.metabolomics.fgu.cas.cz) 

- run your own app

```sh
git clone https://github.com/IPHYS-Bioinformatics/CRediT-Generator.git
cd CRediT-Generator
python -m venv credit-venv
credit-venv\Scripts\activate
pip install -r requirements.txt
python app.py
```
and visit [https://localhost:8050](http://127.0.0.1:8050)

# Acknowledgment

Supported by the project National Institute for Research of Metabolic and Cardiovascular Diseases (Programme EXCELES, ID Project No. **LX22NPO5104**) – Funded by the European Union – Next Generation EU.

![](/assets/3logo_EC_NPO_MSMT_en.jpg)

# License

- **Code**: The code in this repository is licensed under the [MIT License](./LICENSE).
- **Content**: All non-code content (e.g., documentation, images) is licensed under the [Creative Commons Attribution 4.0 International License](./LICENSE-CONTENT).
