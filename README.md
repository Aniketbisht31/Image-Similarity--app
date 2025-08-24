# Image-Similarity-app
Image Similarity Tool (using CLIP + FAISS)
This is a small project where I built a simple image similarity search tool using two open-source libraries: CLIP (by OpenAI) and FAISS (by Meta).

You can:

. Upload images to build an index
. Search for similar images by uploading a new image
. Or search by entering a text query
. The app is built with Streamlit for quick testing and demo purposes.

How to Run
. Clone the repository
. git clone https://github.com/Aniketbisht31/Image-similarity--app.git
. cd image-similarity-app
. Set up the virtual environment
. python -m venv venv
source venv/bin/activate    # Linux/Mac
# or
.\venv\Scripts\activate      # Windows
Install the dependencies
pip install -r requirements.txt
Start the Streamlit app
streamlit run streamlit_ui/app.py
🛠️ Tech Stack
. CLIP (OpenAI)
. FAISS (Meta)
. Streamlit
. Python

Acknowledgements
. OpenAI for CLIP
. Meta for FAISS
. The open-source community for making these amazing tools available!
