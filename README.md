This repository contains the IPARE corpus described in <url>https://aclanthology.org/2025.emnlp-industry.102/</url>

The format of the corpus file is as follows:

Each line contains a single entry consisting of 6 tab-separated elements

<b>[text snippet]</b>  <b>[information provision actvity flag]</b> <b>[reporting entity]</b> <b>[target entity]</b> <b>[frequency]</b> <b>[deadline]</b>

The field <b>text snippet</b> contains the text fragment.

The value of <b>information provision actvity flag</b> is either 0 or 1 depending on whether the text fragment contains information provision requirement activity mention.

The remaining fields contain the information on reporting entity, target entity, frequency and deadline information that is contained in text snippet. 
In case a value is missing a "-" symbol is used, whereas in case of mutiple values (e.g., multiple entites, deadlines, etc.), they are separated by a semicolon. 


