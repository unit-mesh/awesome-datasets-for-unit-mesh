# Awesome AI Datasets for engineer efficiency

Resources:

- https://datasetsearch.research.google.com/
- https://huggingface.co/

## Programming

### Common

- [GitHub-Code-Clean](https://huggingface.co/datasets/codeparrot/github-code-clean) is a cleaner version of Github-code dataset, we add the following filters: Average line length < 100, Alpha numeric characters fraction > 0.25, Remove auto-generated files (keyword search).

### Text To Code

[XLCost for text-to-code synthesis](https://huggingface.co/datasets/codeparrot/xlcost-text-to-code), a subset of XLCoST benchmark, for text-to-code generation at snippet level and program level for 7 programming languages: Python, C, C#, C++, Java, Javascript and PHP.

### Performance

[APPS](https://huggingface.co/datasets/codeparrot/apps) is a benchmark for code generation with 10000 problems. It can be used to evaluate the ability of language models to generate code from natural language specifications. You can also find APPS metric in the hub here codeparrot/apps_metric.

### Complex

[Code](https://huggingface.co/datasets/codeparrot/codecomplex) consists of 4,200 Java codes submitted to programming competitions by human programmers and their complexity labels annotated by a group of algorithm experts.

### ByLanguages

#### Python

[github-jupyter-parsed](https://huggingface.co/codeparrot) with markdown and code pairs. We provide the preprocessing script in preprocessing.py. The data is deduplicated and consists of 451662 examples. 


