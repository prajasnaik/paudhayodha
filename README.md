Develop an AI/MLdriven plant growth monitoring system that utilizes mobile camera technology
to capture images for analysis of key growth factors such as plant size, leaf color, and overall health. 
The system should employ machine learning algorithms to process these images in real-time, providing 
insights into plant health and growth. Additionally, the model should evaluate the plant species
and provide tailored recommendations, including Do's and Dont's for optimal care, helping farmers 
and gardeners enhance crop yield and plant quality.

The application is created by [Jeet Shah](https://github.com/jeetsh4h) and [Aniket Khetan](https://github.com/aniketkhetan).

Way to run the application locally:
```bash
git clone https://github.com/jeetsh4h/paudhayodha.git
cd paudhayodha

python -m venv .venv
pip install -r requirements.txt -y
python -m streamlit run Home.py
```