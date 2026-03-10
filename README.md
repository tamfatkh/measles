# Measles
This is part of the working Python code and the publicly available data used in the measles paper titled "The 2025 Measles Outbreak in Texas" by Dr. Tamer Oraby and Dr. Martial Ndeffo-Mbah.

Put all of the files in the same folder, which I call "measles." Use the Python Jupyter notebook to run the code. Make sure to use the correct path to the folder "measles" at the beginning of the code. The following is where you want to put your path to the folder "measles."

################################

import os

your_path = 'yourpath/measles'

os.makedirs(your_path, exist_ok=True)

os.chdir(your_path)

################################

The NB will work with the shared data on [Google Colab](https://colab.research.google.com/).
