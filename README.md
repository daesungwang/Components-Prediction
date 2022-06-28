# Component-Prediction

## Introduction
This repository is for the research paper(Under review): Automatic Components Prediction for Issue Reports by using Fine-tuned Pre-trained Language Models.

## Gathering option
| Repository         |      Product     |          Option          |
|:-------------------|:----------------:|:------------------------:|
| Bugzilla           |      Firefox     | Resolved, Solved, Closed |
| Eclipse Foundation |     Community    | Resolved, Solved, Closed |
| Eclipse Platform   | Eclipse Projecet | Resolved, Solved, Closed |

## Result
| Dataset            | Collected Issues | Collected Components |
|:-------------------|:----------------:|:--------------------:|
| Bugzilla Firefox   |      19,870      |          77          |
| Eclipse Foundation |      21,644      |          41          |
| Eclipse Platform   |      18,886      |          19          |

## Task based method evaluation Result
### Validation loss
<img src = "https://user-images.githubusercontent.com/22803510/176155200-d681af29-be3d-40fb-ad44-0e2708a879da.png" width="60%">  
  
### Recall at k by Task 1-3
<img src = "https://user-images.githubusercontent.com/22803510/176163908-23d93401-9a6a-4295-9706-277e41c6fa3f.png" width="60%">
<img src = "https://user-images.githubusercontent.com/22803510/176163903-08ca6a2d-182c-40e1-88a2-eec9e46b56ad.png" width="60%">
<img src = "https://user-images.githubusercontent.com/22803510/176163905-695809f1-45ff-46dc-a961-abc6b54c9123.png" width="60%">


## Reference
- Bugzilla_Firefox: https://bugzilla.mozilla.org
- Eclipse_Foundation & Eclipse_Platform: https://bugs.eclipse.org/bugs
