# restaurant_recommendation
Restaurant Recommendation based on Generative AI

1. Project Goals:
Problem Statement
In today's fast-paced world, people often seek quick and convenient dining options, making restaurants a popular choice. However, with so many restaurants available, customers may find it challenging to discover new options that suit their preferences.
To address this issue, we aim to develop a Restaurant Recommendation System. This system will utilize user preferences, such as cuisine type, location, budget, and dietary restrictions, to recommend the most suitable restaurants in 'New York', 'Florida', 'California', 'Pennsylvania', 'Texas' or 'Washington'.

2. Data Sources:
The data for this project will be sourced from multiple fast food restaurant directories, review platforms, and user-generated content. The primary data sources include:
Public data:
•	https://data.world/datafiniti/fast-food-restaurants-across-america
Fast food restaurant directories: Data will be scraped from online directories such as 
•	https://www.yellowpages.com
•	http://www.citysearch.com

3. Design Choices:
Approach:
1.	Conversation and Information Gathering: The chatbot will utilize language models to understand and generate natural responses. Through a conversational flow, it will ask relevant questions to gather information about the user's requirements.
2.	Information Extraction: Once the essential information is collected, rule-based functions come into play, extracting top recommendations that best match the user's needs.
3.	Personalized Recommendation: Leveraging this extracted information, the chatbot engages in further dialogue with the user, efficiently addressing their queries and aiding them in finding the best restaurant based on the users’ dietary habits.
We have a dataset restaurant_data.csv which represents the features of the hotel. The chatbot that we build will leverage LLMs to parse this features column and then determine the user's requirements. For simplicity, we have used 5 features to encapsulate the user's needs. 

The 5 features are as follows:
•	Cuisine preference
•	State Preferences
•	Parking
•	Dining in    
•	Budget
Confirm if the user's requirements have been correctly captured at the end.
After that the chatbot lists down the top recommendations that are the most relevant and engages in further conversation to help the user find the best one.

4. Challenges Faced:
Data Collection: Obtaining a comprehensive on fast food restaurants can be challenging due to the dynamic nature of the industry and the sheer volume of restaurants.
Data Quality: Ensuring the quality and consistency of the collected data, especially user-generated content such as reviews and ratings, can be challenging.
Recommendation Accuracy: Designing an accurate recommendation algorithm that considers user preferences, restaurant attributes, and user feedback poses a significant challenge.
Scalability: Ensuring that the system is scalable to handle many users and restaurants while maintaining performance and responsiveness.
User Privacy: Addressing concerns about user privacy and data security, especially when collecting and storing user preferences.

5. Future Enhancements:
•	Now it is limited to a few states 'New York', 'Florida', 'California', 'Pennsylvania', 'Texas' and 'Washington’ in United States. Need to extend this to the remaining states and gradually global wise.
•	Integration with user interface (front end web) for user authentication and sharing recommendations.
•	Incorporation of machine learning models for real-time personalization and recommendation refinement.
Conclusion:
The Restaurant Recommendation System aims to provide users with personalized recommendations based on their preferences, location, budget, and dietary restrictions. By leveraging data from multiple sources and implementing advanced recommendation algorithms, the system aims to enhance the dining experience for users and help them discover new dining options quickly and conveniently.

