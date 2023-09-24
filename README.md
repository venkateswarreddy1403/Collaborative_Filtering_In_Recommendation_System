# Collaborative_Filtering_In_Recommendation_System

Collaborative filtering is a popular technique used in recommendation systems to provide personalized recommendations to users based on the preferences and behaviours of similar users. It's a method that leverages
user-item interaction data to make predictions about what a user might like or find interesting. Collaborative filtering relies on the assumption that users who have shown similar behaviour in the past will continue to have similar preferences in the future.

**Collaborative Filtering:**
  This method recommends products based on the behaviour and preferences of similar users. It can be user-based, where recommendations are made by identifying users with similar behaviours to 
the target user, or item-based, where recommendations are made based on the similarity between items that the user has interacted with.

There are two primary types of collaborative filtering:

**User-Based Collaborative Filtering:**

•	User-Item Matrix: Collaborative filtering starts with a matrix known as the user-item matrix. In this matrix, rows represent users, columns represent items (products, movies, etc.), and the cells contain information about user interactions with those items. Typically, the entries in this matrix can be binary (indicating whether a user has interacted with an item or not) or numeric (indicating some measure of user engagement, such as ratings or purchase history).

•	User Similarity: To make recommendations for a specific user, the system identifies users who are most similar to the target user in terms of their historical interactions. Similarity metrics such as cosine similarity or Pearson correlation coefficient are commonly used to quantify how alike two users are based on their interactions with items.

•	Recommendation Generation: Once similar users are identified, the system recommends items that these similar users have interacted with but the target user has not. These recommendations are typically ranked by some relevance score (e.g., by considering the frequency of interaction or the average rating).

**Item-Based Collaborative Filtering:**

•	Item-Item Matrix: In item-based collaborative filtering, instead of comparing users, the system focuses on comparing items. An item-item matrix is constructed, where each row represents an item, and each column represents another item. The values in this matrix represent the similarity between items based on user interactions.

•	Item Similarity: Similarity between items can be calculated using techniques such as cosine similarity or Pearson correlation. This measures how often two items are interacted with by the same users and the magnitude of these interactions.

•	Recommendation Generation: To make recommendations for a user, the system identifies items that the user has already interacted with. Then, it looks for items that are similar to the ones the user has interacted with but have not been interacted with by the user. These similar items are then recommended to the user.

**Paradigm:** Collaborative filtering

**Data:** Tabular, Text.

**Model:** Auto-Encoders.

**Process:** Setup, Encode & Embed, Design, Train & Select, Serve & Scale, Measure, Test & Improve.

**Tools:** python-data-stack: pandas, scipy.

# Algorithms

Approaches Collaborative Filtering for Implicit Feedback Datasets.

Neural Collaborative Filtering.

Variational Autoencoders for Collaborative Filtering Evaluations Evaluating Recommendation Systems.



