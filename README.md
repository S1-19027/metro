# MetroFlow: Human Mobility Datasets in the Complex Metro System of Shanghai

MetroFlow is an open-sourced, city-scale metro flow dataset, covering the period of May-August 2017 and 302 metro stations in Shanghai, China. This codebase contains Jupyter notebooks utilized during dataset organization and analyses.



<img src="SupplementaryFiles/Overviewcut.jpg" width="100%" class="center">  



### Processing Pipeline
The project follows a sequential workflow:

1. **Step 1**: Extract trips from transaction records and label trips.  (step1_LabelUser.ipynb)
2. **Step 2**: Extract OD flow at a 10-minute temporal resolution.  (step2_ExtractOD.ipynb)
3. **Step 3**: Extract In-Out flow at a 10-minute temporal resolution. (step3_ExtractFlow.ipynb)



### Directory Structure

- **Analysis/**: Contains analysis scripts for technical validation
- **results/**: Stores analysis results
- **tool/**: Includes tool scripts for metadata acquisition and data processing
- **Data/**: Homes for data files 




### Usage

 Dependencies are listed in `requirements.txt`

Install the required dependencies to get started:
```
pip install -r requirements.txt
```



### Data Repo

The data repository is available on Figshare:

https://doi.org/10.6084/m9.figshare.28844942



### Data Descriptor
https://www.nature.com/articles/s41597-025-05416-8

Please cite the paper if you use this repository in your research:

```bibtex
@article{sun2025human,
  title={Human mobility datasets in the complex metro system of shanghai},
  author={Sun, Peiyan and Yang, Jinming and Huang, Zongyuan and Huang, Shaoyu and Xu, Shengyuan and Wang, Weipeng and Guo, Wenxuan and Feng, Yuting and Zhai, Xi and Yang, Tao and others},
  journal={Scientific Data},
  volume={12},
  number={1},
  pages={1--9},
  year={2025},
  publisher={Nature Publishing Group}
}
、、、
