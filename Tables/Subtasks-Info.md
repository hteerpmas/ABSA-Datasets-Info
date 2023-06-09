# Subtasks Info

[back to README.md](../README.md)

This table gives a list of all the introduced Subtasks of ABSA since its evolution. 
If you want to add any new tasks or change any information, please create a fork of the master repository and create a pull request, so that we can verify it and commit the change.


| Index | Year | Paper                                                                    | CommonName                          | Acronym | Input                                                                            | ExpectedOutput                                                                |
| ----- | ---- | ------------------------------------------------------------------------ | ----------------------------------- | ------- | -------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1     | 2004 | [Hu and Liu, 2004a](https://doi.org/10.1145/1014052.1014073)             | Aspect Term Extraction              | ATE     | "The pasta was very yummy but the place has some weird smell."                   | pasta, place                                                                  |
| 2     | 2004 | [Hu and Liu, 2004a](https://doi.org/10.1145/1014052.1014073)             | Aspect Term Sentiment Analysis      | ATSA    | "The pasta was very yummy but the place has some weird smell.", (pasta, place)   | positive, negative                                                            |
| 3     | 2014 | [Pontiki etal., 2014](https://doi.org/10.3115/v1/S14-2004)               | Aspect Category Detection           | ACD     | "The pasta was very yummy but the place has some weird smell."                   | Food, Ambience                                                                |
| 4     | 2015 | [Pontiki etal., 2014](https://doi.org/10.3115/v1/S14-2004)               | Aspect Category Sentiment Analysis  | ACSA    | "The pasta was very yummy but the place has some weird smell.", (Food, Ambience) | positive, negative                                                            |
| 5     | 2015 | [Pontiki etal., 2015](https://aclanthology.org/S15-2082)                 | Target Detection                    | TD      | "The pasta was very yummy but the place has some weird smell."                   | pasta, place                                                                  |
| 6     | 2014 | [Pontiki etal., 2014](https://doi.org/10.3115/v1/S14-2004)               | Target Aspect Detection             | TAD     | "The pasta was very yummy but the place has some weird smell."                   | (pasta, Food), (place, Ambience)                                              |
| 7     | 2018 | [Schmitt etal., 2018](https://doi.org/10.18653/v1/D18-1139)              | Aspect Sentiment Joint Detection    | ASD     | "The pasta was very yummy but the place has some weird smell."                   | (Food, positive), (Ambience, negative)                                        |
| 8     | 2018 | [Li etal., 2018](http://arxiv.org/abs/1811.05082)                        | Target Sentiment Joint Detection    | TSD     | "The pasta was very yummy but the place has some weird smell."                   | (pasta, positive), (place, negative)                                          |
| 9     | 2020 | [Peng etal., 2020](http://arxiv.org/abs/1811.05082)                      | Aspect Sentiment Triplet Extraction | ASTE    | "The pasta was very yummy but the place has some weird smell."                   | (pasta, very yummy, positive), (place, weird smell, negative)                 |
| 10    | 2020 | [Wan etal., 2020](https://aaai.org/ojs/index.php/AAAI/article/view/6447) | Target Aspect Sentiment Detection   | TASD    | "The pasta was very yummy but the place has some weird smell."                   | (pasta, Food, positive), (place, Ambience, negative)                          |
| 11    | 2019 | [Fan etal., 2019](https://doi.org/10.18653/v1/N19-1259)                  | Target Opinion Word Extraction      | TOWE    | "The pasta was very yummy but the place has some weird smell."                   | (pasta, very yummy), (place, weird smell)                                     |
| 12    | 2021 | [Zhang etal., 2021a](https://doi.org/10.48550/ARXIV.2110.00796)          | Aspect Sentiment QuadPrediction     | ASQP    | "The pasta was very yummy but the place has some weird smell."                   | (pasta, Food, positive, very yummy), (place, Ambience, negative, weird smell) |

[back to README.md](../README.md)
