CodaLab username: ZohraR <br>
Email adress: z.rasuli@student.tue.nl

# README

This README file describes the following:

1. Packages to install for running the models  
2. Steps on how to run the models

---

## Installing packages

The packages that need to be installed are:

- Torch  
- TorchInfo  
- ultralytics-thop  
  - Install with:  
    ```bash
    pip install ultralytics-thop
    pip install --upgrade git+https://github.com/ultralytics/thop.git
    ```

---

## How to run the models

To train/run the models, the following line in the `train.py` file should be changed to the desired model:

```python
from ... import Model, he_initialization

```
The models that can be opted are: unet.py, ResUnet.py and Efficient_Unet.py.    



