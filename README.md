# Assignment 3

### Tasks
1. **Task 1:** Graph Cut Segmentation  
2. **Task 2:** Fully Convolutional Network (FCN)  
3. **Task 3:** Variational Autoencoder (VAE)  

---

### Clone the Repository
```cmd
git clone https://github.com/shakyarahul435/ComputerVisionAssignment3.git
```
```cmd
cd ComputerVisionAssignment3
```


---

### Folder Structure
```
Assignment/
├── coco128/ # Contains coco128 images
├── data/ # MNIST dataset and additional images
│ ├── asm-1.jpg
│ └── asm-2.jpg
├── env/ # Python virtual environment (Python 3.11)
├── output/ # All task outputs will be saved here
├── segmented/ # Segmented images will be saved here
├── Task1.ipynb # Notebook for Task 1
├── Task2.ipynb # Notebook for Task 2
└── Task3.ipynb # Notebook for Task 3
```

### 1. Create the virtual environment
```cmd
py -3.11 -m venv env
```
### 2. Activate the virtual environment
```cmd
env\Scripts\activate
```
### 3. Install Dependencies
```cmd
pip install -r requirements.txt
```

### 4. Install torch, torchvision and torchaudio 
- <b>For GPU</b>
```cmd
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu130
```

- <b> For CPU </b>
```cmd
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
```


---

After activating virtual environment in VSCode Tasks will run smoothly as expected.

---

### Notes
- Images:coco128/ - Contains sample COCO images.
- data/ - Contains MNIST dataset and custom images (asm-1.jpg, asm-2.jpg).
- Python version: 3.11 in virtual environment (env/) so that torch, torchvision, torchaudio works without issue.
- Outputs: All task outputs saved to output folder and segmented images saved to segmented folder.