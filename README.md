# thermal-multimodal-covid-detector

**[COVID-19 detection from thermal image and tabular medical data utilizing multi-modal machine learning](https://doi.org/10.1109/CBMS58004.2023.00122)**, Mahbub Ul Alam, Jaakko Hollmén and Rahim Rahmani. IEEE 36th International Symposium on Computer-Based Medical Systems (CBMS), 2023, pp. 646-653, https://doi.org/10.1109/CBMS58004.2023.00122. (**[presentation slides](https://github.com/anondo1969/thremaltimodal-covidetector/raw/main/slides_and_results/presentation_slides_v3.pdf)**)

## Abstract

COVID-19 is a viral infectious disease that has created a global pandemic, resulting in millions of deaths and disrupting the world order. Different machine learning and deep learning approaches were considered to detect it utilizing different medical data. Thermal imaging is a promising option for detecting COVID-19 as it is low-cost, non-invasive, and can be maintained remotely. This work explores the COVID-19 detection issue using the thermal image and associated tabular medical data obtained from a publicly available dataset. We incorporate a multi-modal machine learning approach where we investigate the different combinations of medical and data type modalities to get an improved result. We use different machine learning and deep learning methods, namely random forests, Extreme Gradient Boosting (XGBoost), Multilayer Perceptron (MLP), and Convolutional Neural Network (CNN). Overall multi-modal results outperform any single modalities, and it is observed that the thermal image is a crucial factor in achieving it. XGBoost provided the best result with the area under the receiver operating characteristic curve (AUROC) score of 0.91 and the area under the precision-recall curve (AUPRC) score of 0.81. We also report the average of leave-one-positive-instance-out cross-validation evaluation scores. This average score is consistent with the test evaluation score for random forests and XGBoost methods. Our results suggest that utilizing thermal image with associated tabular medical data could be a viable option to detect COVID-19, and it should be explored further to create and test a real-time, secure, private, and remote COVID-19 detection application in the future.

### Schematic Diagram

![Schematic Diagram](https://raw.githubusercontent.com/anondo1969/thremaltimodal-covidetector/main/slides_and_results/schematic_diagram.jpeg)

### Best Results

![XGBoost AUROC](https://raw.githubusercontent.com/anondo1969/thremaltimodal-covidetector/main/slides_and_results/xg_boost_graph_x.jpeg)

![XGBoost AUPRC](https://raw.githubusercontent.com/anondo1969/thremaltimodal-covidetector/main/slides_and_results/xg_boost_auprc_graph_x.jpeg)

## Citation

Please acknowledge the following work in papers or derivative software:

M.U. Alam, J. Hollmén and R. Rahmani, "COVID-19 detection from thermal image and tabular medical data utilizing multi-modal machine learning," 2023 IEEE 36th International Symposium on Computer-Based Medical Systems (CBMS), 2023, pp. 646-653, doi: 10.1109/CBMS58004.2023.00122.

### Bibtex Format for Citation

```
@INPROCEEDINGS{alam2023_covid19,
  author={Alam, Mahbub Ul and Hollmén, Jaakko and Rahmani, Rahim},
  booktitle={2023 IEEE 36th International Symposium on Computer-Based Medical Systems (CBMS)}, 
  title={COVID-19 detection from thermal image and tabular medical data utilizing multi-modal machine learning}, 
  year={2023},
  volume={},
  number={},
  pages={646-653},
  doi={10.1109/CBMS58004.2023.00122}
  }
```


