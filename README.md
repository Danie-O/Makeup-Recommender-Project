Makeup-Product-Recommender-System
-------------------------------------

Final year project: A recommender system for content-based recommendation of makeup products based on facial features identified from users' images.

This recommender utilises a deep learning model, trained using Convolutional Neural Networks(CNNs), to predict the skintone class of a user.
The model is then used to generate makeup product(foundation) recommendations by matching user skintones to products based on the skintone class which they fall under.

A user can get recommendations through a simple web application that allows users to upload their image. The uploaded image is processed and the output returned to the user consists of:

- Skintone-based makeup product recommendations
- Links to purchase recommended products
- A follow-up email with the recommended products (on request).


Libraries and frameworks used include:
---------------------------------------
- Pytorch
- Tensorflow
- Python(Pandas, numpy, matplotlib and seaborn)
- Python(Flask)
- Python(Streamlit)
- Bootstrap

Usage
----
- To run the Flask app locally, navigate to the project directory and run the following command in the terminal:
```
flask run
```

After running the flask app, a Plotly window would pop up showing the classes and their predicted probabilities for the given image.
Close the popup window and access the landing page via: <http://127.0.0.1:5000/>


- To run the Streamlit app locally, navigate to the project directory and run the following command in the terminal:
```
streamlit run steamlit-app.py
```

A link would be generated and displayed in the terminal, through which the streamlit application can be accessed.



