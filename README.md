# Fashion MNIST Classification  
This project applies deep learning to classify **Fashion MNIST images** into **10 clothing categories** using a **Convolutional Neural Network (CNN)**.  
A **Streamlit web app** is included for interactive predictions.  

## 👕 Clothing Categories  
1️⃣ T-shirt/Top  
2️⃣ Trouser  
3️⃣ Pullover  
4️⃣ Dress  
5️⃣ Coat  
6️⃣ Sandal  
7️⃣ Shirt  
8️⃣ Sneaker  
9️⃣ Bag  
🔟 Ankle boot  

## 📂 Project Structure  
- `fashion_mnist_dl.py` → **Trains the deep learning model** on the Fashion MNIST dataset.  
- `streamlit_app.py` → **Streamlit web app** for uploading images and getting predictions.  
- `requirements.txt` → **Lists dependencies** required to run the project.  

## 🚀 How to Run the Project  

### 1️⃣ **Clone the Repository**  
```sh
git clone https://github.com/AakritiGoenka/Fashion_MNIST_DL.git
cd Fashion_MNIST_DL

2️⃣ Set Up the Virtual Environment (Recommended)
python -m venv venv
source venv/Scripts/activate  # For Windows
#

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Train the Deep Learning Model

python fashion_mnist_dl.py

5️⃣ Run the Streamlit Web App

streamlit run fashion_streamlit.py


