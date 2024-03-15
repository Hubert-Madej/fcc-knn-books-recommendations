# Book Recommendation Algorithm using K-Nearest Neighbors

Create a book recommendation algorithm using K-Nearest Neighbors.

## Dataset Overview

The dataset used for this project is the Book-Crossings dataset, which contains 1.1 million ratings (scale of 1-10) of 270,000 books by 90,000 users.

## Approach

1. **Data Import and Cleaning**: Import the dataset and clean it by removing users with less than 200 ratings and books with less than 100 ratings.
2. **K-Nearest Neighbors**: Utilize the NearestNeighbors algorithm from sklearn.neighbors to develop a model that suggests books similar to a given book.
3. **Function Implementation**: Create a function named `get_recommends` that takes a book title as an argument and returns a list of 5 similar books with their distances from the input book.
4. **Testing**: Validate the functionality of the algorithm using provided test cases.
