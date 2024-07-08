# Restaurant Recommendation System using Zomato Dataset

## Overview
This project at Cognify Technologies focuses on creating a restaurant recommendation system based on user preferences using the Zomato dataset. The system leverages content-based filtering techniques to suggest restaurants similar to user-selected criteria such as cuisine preference and price range.

## Project Structure
- `data/`: Contains the Zomato dataset (`zomato.csv`).
- `scripts/`: Scripts for data preprocessing (`data_preprocessing.py`) and recommendation system implementation (`recommendation_system.py`).
- `README.md`: Project overview, setup instructions, and usage details.
- `requirements.txt`: Python dependencies required to run the project.

## Technical Implementation
1. **Data Preprocessing:**
   - Removed unnecessary columns (`rest_type`, `cuisines`, `url`).
   - Handled missing values and duplicates.
   - Standardized data formats (`cost`, `rate`).

2. **Criteria Determination:**
   - Identified user preferences (cuisine preference, price range).

3. **Content-Based Filtering:**
   - Cleaned and preprocessed text data (`reviews_list`).
   - Created TF-IDF matrix for text similarity analysis.
   - Computed cosine similarities for restaurant recommendations.

4. **Evaluation Metrics:**
   - Used Mean Average Precision (MAP) and Mean Reciprocal Rank (MRR) to evaluate recommendation quality.
   - Achieved [specific evaluation metrics results].

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Santhosh-reddyp/cognify-restaurant-recommendation.git
   cd cognify-restaurant-recommendation
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run data preprocessing:

bash
Copy code
python scripts/data_preprocessing.py
Run recommendation system:

bash
Copy code
python scripts/recommendation_system.py
Results and Performance

Achieved [specific performance metrics results].
Validated recommendation system effectiveness through [evaluation metrics].
Future Enhancements

Incorporate collaborative filtering for broader recommendation coverage.
Enhance user interface for better user interaction.
Contributors

Santhosh Reddy (GitHub)
License

This project is licensed under the MIT License.

vbnet
Copy code

In this template:
- Replace `[specific evaluation metrics results]` with actual evaluation results.
- Customize the setup instructions and technical implementation details based on your scripts and requirements.
- Add any additional sections or details as per your project's specific needs and achievements.

Make sure to update the sections with accurate information and links relevant to your project before publishing your `README.md` file on GitHub or any other platform.





