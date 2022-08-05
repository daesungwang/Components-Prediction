# Component-Prediction

## Introduction
This repository is for the research paper(Under review): Automatic Component Prediction for Issue Reports Using Fine-tuned Pretrained Language Models.
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
<img src = "https://user-images.githubusercontent.com/22803510/176393856-9a878abe-6d38-426f-9f7e-fb02e730d68b.png" width="80%">  
  
### Recall at k by Task 1-3
<img src = "https://user-images.githubusercontent.com/22803510/176165936-ac5dd574-a27c-44a8-81ed-846a80c81e7e.png" width="80%">
<img src = "https://user-images.githubusercontent.com/22803510/176165929-40adddb1-7b8f-43d3-a106-c815f17dfabd.png" width="80%">
<img src = "https://user-images.githubusercontent.com/22803510/176165933-ac2fc21f-3e02-46d4-89af-d9d7a5bcfbe4.png" width="80%">


## Reference
- Bugzilla_Firefox: https://bugzilla.mozilla.org
- Eclipse_Foundation & Eclipse_Platform: https://bugs.eclipse.org/bugs
