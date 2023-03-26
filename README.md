# Facial-emotion-expression
"Downloading and Unzipping a Kaggle Dataset in Google Colab"

1. Install the Kaggle package using pip:
!pip install kaggle

2. Upload your Kaggle API key (kaggle.json) to Google Colab:
from google.colab import files
files.upload()

3. Create a directory for your Kaggle API key:
!mkdir ~/.kaggle

4. Move your Kaggle API key into the newly created directory:
!cp kaggle.json ~/.kaggle/

5. Set permissions for your Kaggle API key:
!chmod 600 ~/.kaggle/kaggle.json

6. Download the Kaggle dataset using the Kaggle CLI:
!kaggle datasets download -d samaneheslamifar/facial-emotion-expressions

7. Unzip the downloaded dataset:
!unzip /content/facial-emotion-expressions.zip
