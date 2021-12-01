---
permalink: /projects/
layout: archive
title: Projects
website_one:
    - image_path: "https://raw.githubusercontent.com/greenelab/annorxiver_manuscript/main/content/images/figure-pieces/homescreen_doi.png"
      title: "Preprint similarity search"
      url: "https://greenelab.github.io/preprint-similarity-search"
      excerpt: |
        Provides users with a listing of linguistically similar journals and papers to a preprint of interest.
        Here is more a description
      btn_label: |
       <i class="fab fa-firefox-browser"></i> <i class="fab fa-chrome"></i> Visit Websites
      btn_class: "btn--primary"
research_projects_one:
     - image_path: /assets/images/biovectors_screenshot.png
       title: Biovectors
       url: "https://github.com/greenelab/biovectors/"
       excerpt: "Detecting semantic shifts through time by using word embeddings trained on pubmed Abstracts."
       btn_label: |
        <i class="fab fa-fw fa-github" aria-hidden="true"></i> View Repo
       btn_class: "btn--primary"
research_projects_two:
     - image_path: https://raw.githubusercontent.com/danich1/annorxiver/65ee4a556ab69f2308e5e4d9192905e8cfec3728/figure_generation/output/Figure_2.png
       title: Annorxiver
       url: "https://github.com/greenelab/annorxiver/"
       excerpt: "Performing a linguistic analysis of the bioRxiv repository Lets add more text to see if this parsing will make more sense."
       btn_label: |
        <i class="fab fa-fw fa-github" aria-hidden="true"></i> View Repo
       btn_class: "btn--primary"
research_projects_three:
     - image_path: https://raw.githubusercontent.com/greenelab/text_mined_hetnet_manuscript/3a040e78114208417d2b1784ae558fb323eabe01/content/images/figures/hetionet/metagraph_highlighted_edges.png
       title: Snorkeling-Full-Text
       url: "https://github.com/greenelab/snorkeling-full-text/"
       excerpt: "Extracting biomedical relationships from literature using weak supervision via the Snorkel python library."
       btn_label: |
        <i class="fab fa-fw fa-github" aria-hidden="true"></i> View Repo
       btn_class: "btn--primary"
research_projects_four:
     - image_path: /assets/images/pubtator_screenshot.png
       title: Pubtator
       url: "https://github.com/greenelab/pubtator/"
       excerpt: "Resource for converting Pubtator and Pubtator Central annotations into BioCXML format. (depreciated now that PubMed Central provides BioCXML)."
       btn_label: |
        <i class="fab fa-fw fa-github" aria-hidden="true"></i> View Repo
       btn_class: "btn--primary"
---

# Website Resources

{% include feature_row id="website_one" type="left" %}


# Research Projects

{% include feature_row id="research_projects_one" type="left"%}
{% include feature_row id="research_projects_two" type="right"%}
{% include feature_row id="research_projects_three" type="left"%}
{% include feature_row id="research_projects_four" type="right"%}
