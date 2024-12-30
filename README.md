# how-to-run-the-code

I use google colab .First of all  we have to mount google drive with google colab .
code :
from google.colab import drive
drive.mount('/content/drive')
Ensure Required Libraries are Installed:The code uses libraries like torch, torchvision, PIL, cv2 (OpenCV), and matplotlib.
If you're running the code on a platform like Google Colab or a local machine with a GPU, ensure CUDA is available. The code automatically detects the device using.
device = torch.device("cuda" if torch.cuda.is_available() else "cpu")
Ensure the models  are saved in the correct path. 
Ensure the test image is available.
Select the target layer for Grad-CAM visualization from the model's architecture.
Once the setup is complete, execute the code step by step in  Google Colab.
