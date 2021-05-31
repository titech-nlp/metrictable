Data used in [Metric-Type Identification for Multi-Level Header Numerical Tables in Scientific Papers](https://www.aclweb.org/anthology/2021.eacl-main.267/ "Metric-Type Identification for Multi-Level Header Numerical Tables in Scientific Papers")  (Suadaa et al; EACL 2021). If you use this data, please cite the above paper.
<br />
<br />
<b>License</b>
<br />
Distributed under the [Creative Commons 4.0 Attribution-ShareAlike (CC4.0-BY-SA)](https://creativecommons.org/licenses/by-sa/4.0/) license.
<br />
<br />
<b>Dataset Statistics</b>

&nbsp;| Train | Val | Test
--- | --- | --- | ---
No. of tables | 1,084 | 136 | 135
Average row/column | 6 | 6 | 5
Max level of row header | 9 | 6 | 4
Max level of column header | 6 | 5 | 6
Vocab size of headers | 8,270 | 1,435 | 1,230
Vocab size of all metric-types | 807 | 175 | 185
Vocab size of unique metric-types | 90 | 22 | 28

<br />
<b>Table Data (json)</b>
<br />

```
[
{
        "caption": "Bilingual Lexicon Induction performance from es, it, nl to en. Gouws and S\u00f8gaard (2015) + Panlex/Wikt is our reimplementation using Panlex/Wiktionary dictionary. All our models use Panlex as the dictionary. We reported the recall at 1 and 5. The best performance is bold.",
        "row_header_level": 2,
        "row_headers": [
            [
                "Model",
                "Gouws and S\u00f8gaard (2015) + Panlex"
            ],
            [
                "Model",
                "Gouws and S\u00f8gaard (2015) + Wikt"
            ],
            [
                "Model",
                "BilBOWA: Gouws et al. (2015)"
            ],
            [
                "Model",
                "Vulic and Moens (2015)"
            ],
            [
                "Model",
                "Our model (random selection)"
            ],
            [
                "Model",
                "Our model (EM selection)"
            ],
            [
                "Model",
                "Our model (EM selection) + Joint model"
            ],
            [
                "Model",
                "Our model (EM selection) + combine embeddings (\u03b4 = 0.01)"
            ],
            [
                "Model",
                "Our model (EM selection) + lemmatization"
            ]
        ],
        "column_header_level": 2,
        "column_headers": [
            [
                "es-en",
                "rec1"
            ],
            [
                "es-en",
                "rec5"
            ],
            [
                "it-en",
                "rec1"
            ],
            [
                "it-en",
                "rec5"
            ],
            [
                "nl-en",
                "rec1"
            ],
            [
                "nl-en",
                "rec5"
            ],
            [
                "Average",
                "rec1"
            ],
            [
                "Average",
                "rec5"
            ]
        ],
        "contents": [
            [
                "37.6",
                "63.6",
                "26.6",
                "56.3",
                "49.8",
                "76.0",
                "38.0",
                "65.3"
            ],
            [
                "61.6",
                "78.9",
                "62.6",
                "81.1",
                "65.6",
                "79.7",
                "63.3",
                "79.9"
            ],
            ...
        ],
        "metrics_loc": "column",
        "metrics_type": [
            "rec1",
            "rec5",
            "rec1",
            "rec5",
            "rec1",
            "rec5",
            "rec1",
            "rec5"
        ],
        "paper_id": "D16-1136",
        "table_id": "table_3",
        "table_id_paper": "D16-1136table_3",
        "table_name": "Table 3",
        "valid": 1
    }
    ...
]
```
<br />

