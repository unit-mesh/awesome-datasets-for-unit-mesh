# Awesome AI Datasets for engineer efficiency

Resources:

- https://datasetsearch.research.google.com/
- https://huggingface.co/

Pre-Trainning:

- [CodeGen (CodeGen-Mono 16B) ](https://huggingface.co/Salesforce/codegen-16B-mono)
- [CodeGeeX](https://github.com/THUDM/CodeGeeX) An Open Multilingual Code Generation Model 
- [StarCodes](https://huggingface.co/blog/starcoder) are 15.5B parameter models trained on 80+ programming languages from The Stack (v1.2), with opt-out requests excluded. 

Code Smells:

- [QScored](https://zenodo.org/record/7484812) A Large Dataset of Code Smells and Quality Metrics

AI Server

- [FauxPilot](https://github.com/fauxpilot/fauxpilot) s is an attempt to build a locally hosted alternative to GitHub Copilot. It uses the SalesForce CodeGen models inside of NVIDIA's Triton Inference Server with the FasterTransformer backend.

## Programming

### Common

- [GitHub-Code-Clean](https://huggingface.co/datasets/codeparrot/github-code-clean) is a cleaner version of Github-code dataset, we add the following filters: Average line length < 100, Alpha numeric characters fraction > 0.25, Remove auto-generated files (keyword search).

### Text To Code

[XLCost for text-to-code synthesis](https://huggingface.co/datasets/codeparrot/xlcost-text-to-code), a subset of XLCoST benchmark, for text-to-code generation at snippet level and program level for 7 programming languages: Python, C, C#, C++, Java, Javascript and PHP.

### Performance

[APPS](https://huggingface.co/datasets/codeparrot/apps) is a benchmark for code generation with 10000 problems. It can be used to evaluate the ability of language models to generate code from natural language specifications. You can also find APPS metric in the hub here codeparrot/apps_metric.

### Complex

[Code](https://huggingface.co/datasets/codeparrot/codecomplex) consists of 4,200 Java codes submitted to programming competitions by human programmers and their complexity labels annotated by a group of algorithm experts.

## ByLanguages

### Python

[github-jupyter-parsed](https://huggingface.co/codeparrot) with markdown and code pairs. We provide the preprocessing script in preprocessing.py. The data is deduplicated and consists of 451662 examples. 

### Java


#### semeru/Text-Code-concode-Java

https://huggingface.co/datasets/semeru/Text-Code-concode-Java

> Generate source code of class member functions in Java, given natural language description and class environment.
> Class environment is the programmatic context provided by the rest of the class, including other member variables and
> member functions in class. Models are evaluated by exact match and BLEU.

#### semeru/completeformer_java_data

https://huggingface.co/datasets/semeru/completeformer_java_data

> AutoCompleteFormer

