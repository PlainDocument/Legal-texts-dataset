## Dataset
Dataset of Russian legal documents of different genres

Collected and processed as part of the [Plain Document Project](https://www.plaindocument.org/)


## Structure
Xml file structure

    ├── head 
    │   └── title
    └── body                 
        ├── chapter
        │ ├── paragraph
        │   ├── sentence
        │     ├── word
        │     │ ├── text
        │     │ ├── lemma
        │     │ ├── pos tag
        │     │ ├── dep tag
        │     │ ├── pymorphy morph and pos tags
        │     │ └── slovnet morph tags
        │     └── ...
        │
        |     
        └── ... 



## Files and downloads
### Processed data
* Full archived dataset is available at [YandexDisk](https://disk.yandex.ru/d/7j_2-9ep835kaA)
* xml_test contains 500 sample files
### Complexity metrics
Linguistic parameters and features related to the task of [text complexity estimation](https://github.com/PlainDocument/Models)
* Full metrics file is available at [YandexDisk](https://disk.yandex.ru/d/IZno-v2hSOiyuQ)
* test_metrcis.csv contains metrics for the 500 sample documents
