# Repository for *Beyond Partisan Leaning: A Comparative Analysis of Political Bias in Large Language Models*  

> *Note: The paper title may change depending on submission policies.*
> *This work is currently under review.*

## Data and Code Structure  

- **Preprocessing**  
  It is recommended to use the provided `.ipynb` notebooks to preprocess and clean the data.  

- **LLM-Generated Data**  
  The generated outputs are stored in `.data/Results_with_Jailbreak`.  
  We attempt to extract the selected options from the responses whenever possible.  

- **Descriptive Statistics**  
  Summary statistics are stored in `.statistics`.  
  These include counts of scores (mapping options to their original order) for each question by each LLM.  

- **Question Data**  
  The prompt questions are stored in `.question_json_ver3`.  
  To reduce randomness from option ordering, multiple versions of the questions are generated.  

- **LLM Scripts**  
  The generation scripts for LLMs are provided in `.model_script`.  
  You can reproduce the results using these scripts, but please verify the LLM versions and APIs.  

## Citation  

If you find this work useful, please cite:  

```bibtex
@article{peng2024beyond,
  title={Beyond Partisan Leaning: A Comparative Analysis of Political Bias in Large Language Models},
  author={Peng, Tai-Quan and Yang, Kaiqi and Lee, Sanguk and Li, Hang and Chu, Yucheng and Lin, Yuping and Liu, Hui},
  journal={arXiv preprint arXiv:2412.16746},
  year={2024}
}

