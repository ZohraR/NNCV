CodaLab username: ZohraR
Emailadress: z.rasuli@student.tue.nl

This README file describes the following ...
    1. Packages to install for running the models
    2. Steps on how to run the models

# Installing packages
The packages that need to be installed are:
    - Torch 
    - TorchInfo
    - ultralytics-thop
      - pip install --upgrade git+https://github.com/ultralytics/thop.git

  # How to run the models
  To train/run the models, the following line in the train.py file should be changed:
      from ... import Model, he_initialization
  Instead of the dotted lines the name of the model python script should be added.
  E.g. ResUnet.py -> change ... with ResUnet
    
    



