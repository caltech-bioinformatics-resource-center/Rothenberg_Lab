# single-cell Perturb-Seq pipelines

### This repository includes

* 1) Guide RNA data (a novel design of dual guides in vector backbone) processing pipeline to quantify guide UMIs in individual cells and binarize the count table using Gaussian Mixed Modeling; 
* 2) Benchmarking of a test guide RNA dataset generated from 10x Genomics platform. Both in-house guide processing tool and Cellranger3 were used for comparison.

#### Directory contents 
* [Guide RNA pipeline](/guiderna): A folder with RUST excutable file. 
* [Benchmarking of guide RNA data](/benchmarking): A folder with benchmarking results.

#### Installation of `guiderna_tool`
```
git clone https://github.com/caltech-bioinformatics-resource-center/Rothenberg_Lab
chmod +x Rothenberg_Lab/guidedna/guiderna_tool
sudo cp Rothenberg_Lab/guidedna/guiderna_tool /usr/bin/
```

### An online resource to understand the basics of 10X single-cell perturb-seq
[Sarah Teichmann's group at EMBL-EBI / Wellcome Trust Sanger Institute](https://teichlab.github.io/scg_lib_structs/methods_html/10xChromium3fb.html)
