# Movie-Recommender-System-Content-Based_Filtering
Technical Description: Movie Recommender System with Content-Based Filtering Deployed Using Streamlit

### **Overview**:

The Movie Recommender System presented here is a sophisticated solution built upon content-based filtering principles. This project uses text vectorization (Bag of Words) and K-Nearest Neighbors (KNN) to suggest movies based on user preferences. The system analyzes the plot summaries of movies to find similarities and recommend 5 films with similar content.

### **Architecture**:

The system follows a modular architecture, comprising three main components: the Content-Based Filtering Engine, the Streamlit Web Application, and the Movie Database.

### **Content-Based Filtering Engine:**

#### **Feature Extraction:** Utilizes advanced natural language processing (NLP) techniques to extract relevant features from movie metadata, including genres, keywords, and plot summaries.
Text Vectorization: Movies are represented using the Bag of Words model, where plot summaries are converted into vectors.
K-Nearest Neighbors (KNN): The system uses KNN to find the most similar movies based on the vectorized plot descriptions.
Similarity Calculation: Determines movie similarities using cosine similarity, allowing the system to identify content-wise related films.

### **Streamlit Web Application:**

#### **User Interface:** Developed with Streamlit, the application offers an intuitive and user-friendly interface. Users can input preferences and receive personalized movie recommendations.
Integration with Content-Based Engine: Establishes seamless communication with the Content-Based Filtering Engine to fetch and display recommendations based on user inputs.

#### **Comprehensive Data**: The system relies on a comprehensive movie database containing detailed information about a vast array of films.
Integration with Content Engine: Ensures that the content-based filtering engine has access to up-to-date and accurate movie data for optimal recommendation accuracy.

#### Technologies Used:
Python: The entire system is developed in Python, leveraging its rich ecosystem of libraries for data processing, machine learning, and web development.

NLP Libraries: Utilizes state-of-the-art NLP libraries for feature extraction and processing of textual data.

To use the model write streamlit run website.py and then a web page appears with the heading Movie Recommender System, then type or select a movie from the dropdown and click Show Recommendation, then five most similar movies from the one you selected will appear on the screen.
Streamlit: Employs Streamlit for the rapid development and deployment of the web application, streamlining the user interface design process.





