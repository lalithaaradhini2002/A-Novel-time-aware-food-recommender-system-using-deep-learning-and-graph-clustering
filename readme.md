# A NOVEL TIME AWARE FOOD RECOMMENDER SYSTEM BASED ON DEEP LEARNING AND GRAPH CLUSTERING
This project deals with a novel time-based food recommender system that combines deep learning and graph clustering. The system addresses the limitations of traditional recommender systems by incorporating the temporal aspect of users' preferences. Deep learning algorithms are used to model complex relationships and extract meaningful features from food data. Graph clustering techniques are employed to identify user communities and capture data structure. Experimental results show that the proposed system outperforms traditional approaches in terms of accuracy and user satisfaction. It effectively handles data sparsity and cold start problems. The system provides personalized and timely recommendations, adapting to users' changing dietary habits. It promotes healthier food choices by considering user preferences and utilizing previous ratings.The integration of deep learning and graph clustering enhances the recommendation accuracy.Overall, the proposed system offers an effective solution for personalized food recommendations in a dynamic food landscape.

## Keywords

Recommender-system, food recommendation, healthcare, deep learning, graph clustering.

## FEATURES

### 1) Food Recommendation System with Ingredient Awareness: 
Our innovative approach combines collaborative filtering and content-based models to provide personalized food
recommendations. By incorporating the user's preferences and past ratings, the system suggests a curated list of foods that align with their tastes and preferences.
### 2) Time-Sensitive Food Recommendation System: 
Our solution introduces a unique time-aware similarity measure, which considers changes in food preferences and dietary habits
 over time. This feature allows the system to adapt and accommodate users' evolving preferences and provide accurate recommendations accordingly.
### 3) Trust-Based Food Recommendation System: 
To address the challenges posed by the cold start problem, our model incorporates a trust-aware approach. By establishing a trust network among users based on follower-following relationships, we enhance the efficiency of predicting user ratings for unseen food items. Trust statements and user ratings-based similarity play a crucial role in mitigating data sparsity issues and improving recommendation accuracy.
### 4) Community-Driven Food Recommendation System: 
Unlike conventional methods, our model takes into account users' communities when generating food recommendations. It automatically determines the optimal number of user clusters and leverages a graphical representation that incorporates user ratings-based similarity and trust network. This approach enhances the system's performance with sparse datasets and provides more meaningful recommendations based on community preferences.

## REQUIREMENTS
- Python 3.6
- TensorFlow (version X.X.X)
- Keras (version X.X.X)
- NumPy (version X.X.X)
- Pandas (version X.X.X)
- scikit-learn (version X.X.X)
- openpyxl (version X.X.X)
- wordcloud (version X.X.X)
- xlwt (version X.X.X)

## USAGE
- git clone

## Install the required dependencies:
pip install -r requirements.txt

## Prepare your dataset:
Ensure your dataset is properly formatted for detecting whether the text is bullying one or not, with labeled examples.Split your dataset into training and testing sets. Place the data files in the appropriate directories (e.g., data/train.csv, data/test.csv).
## Configure the model:
Adjust the hyperparameters, such as learning rate, batch size, and network architecture, in the config.py file.
## Train the model:
python train.py
## Evaluate the model:
python evaluate.py
## Results:
Detects whether the food is recommended or not according to the parameters entered.

![Screenshot 2023-06-13 145007](https://github.com/lalithaaradhini2002/A-Novel-time-aware-food-recommender-system-using-deep-learning-and-graph-clustering/assets/113698687/61b9015f-34e4-4b26-b87d-2dea6fa5f881)

## Acknowledgements:
- We acknowledge the authors of the original datasets used in training and evaluation.
- Special thanks to the open-source community for their valuable contributions.

## Contact:
For any inquiries or questions, please feel free to reach out to us at the following contact information:
- Email: lalithaaradhinik@gmail.com
- GitHub: https://github.com/lalithaaradhini2002
- LinkedIn: https://www.linkedin.com/in/lalithaaradhini/

We welcome any feedback, suggestions, or collaboration opportunities related to this project. Don't hesitate to get in touch with us, and we'll be happy to assist you. Thank you for your interest and support!


