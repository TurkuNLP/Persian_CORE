# ParsCORE
This repository contains ParsCORE v0.1, a collection of Persian (Farsi) web-crawled documents from HPLT3 annotated with a hierarchical register scheme based on the CORE taxonomy, originally developed for English by Biber and Egbert (2018) and Laippala et al. (2022).
# Usage
If you use this dataset in your research or projects, please cite the following paper:

@inproceedings{razzaghi-etal-2026-parscore,
    title = "{P}ars{CORE}: The {P}ersian Corpus of Online Registers",
    author = "Razzaghi, Alireza  and
      Henriksson, Erik  and
      Laipalla, Veronika",
    editor = "Merchant, Rayyan  and
      Megerdoomian, Karine",
    booktitle = "The Proceedings of the First Workshop on {NLP} and {LLM}s for the {I}ranian Language Family",
    month = mar,
    year = "2026",
    address = "Rabat, Morocco",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2026.silkroadnlp-1.7/",
    doi = "10.18653/v1/2026.silkroadnlp-1.7",
    pages = "60--73",
    ISBN = "979-8-89176-371-5",
    abstract = "Despite recent advances in automatic web register (genre) labeling and its applications to web-scale datasets and LLM development, the effectiveness of these tools for digitally lowresource languages remains unclear. This study introduces ParsCORE, the first largescale collection of Persian web registers (genres), and evaluates deep learning models for register classification and keyword analysis across major registers. Using 2,000 humanannotated documents, the models achieved a micro F1-score of 0.76. The findings provide a foundation for future research on the linguistic and cultural specificities of Persian registers."
}

# Register Label Scheme

The register annotation scheme used in this corpus is hierarchical, with the following categories:

    MT: Machine translated or generated
    LY: Lyrical
    SP: Spoken
        it: Interview
    ID: Interactive discussion
    NA: Narrative
        ne: News report
        sr: Sports report
        nb: Narrative blog
    HI: How-to or instructions
        re: Recipe
    IN: Informational description
        en: Encyclopedia article
        ra: Research article
        dtp: Description of a thing or person
        fi: Frequently asked questions
        lt: Legal terms and conditions
    OP: Opinion
        rv: Review
        ob: Opinion blog
        rs: Denominational religious blog or sermon
        av: Advice
    IP: Informational persuasion
        ds: Description with intent to sell
        ed: News & opinion blog or editorial
