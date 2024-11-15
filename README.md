# RateFlix

RateFlix is a platform where users can upload movie details, such as movie name, genre, release date, and rate their own movies. This README file provides an overview of the project, setup instructions, assumptions made during development, completion status of different tasks, and problems faced with incomplete parts.

## Language and Database
- **Language:** Python
- **Framework:** Django
- **Database:** PostgreSQL (Render PostgreSQL)

## Setup Instructions
1. Clone the project repository from the provided git link: [RateFlix Git Repository](https://movie-rating-postgres.onrender.com)
2. Ensure you have Python installed on your system.
3. Create a virtual environment and activate it:

python -m venv env
.\env\Scripts\activate # For Windows
source env/bin/activate # For Unix or MacOS

4. Install Django and other dependencies:

pip install -r requirements.txt

5. Set up the database connection in the Django project settings to Render PostgreSQL.
6. Connect the project to AWS S3 bucket for static files storage.

## Assumptions
- This project was developed to meet specific requirements and constraints, including time constraints.
- **Assumption:** Developing this project under pressure and within a short timeframe will provide valuable experience for handling similar situations in the future.
- **Learning:** The project has provided an opportunity to learn new features of Django which will be beneficial in future projects.

## Completion Status
1. User can login - Completed
2. User can add a movie - Completed
3. User can view a list of all movies - Completed
4. User can rate a movie - Incomplete (Only the uploader of the movie can rate; implementation pending)
5. User can search for a specific movie and view its details along with the average rating - Completed

## Problems Faced with Incomplete Parts
- The implementation of the feature allowing only the uploader of the movie to rate is pending due to time constraints. However, with additional time, this feature can be completed.

## I have created some users for the visitors.
Name : john_doe, pass : userpass1, email : john_dooe@gmail.com .

Name : jane_doe, pass : userpass2, email :  jane_doe@gmail.com .

Name : Mark_Doe, pass :  userpass3, email : Mark_Doe@gmail.com .


## Live Site and Git Repository
- **Live Site:** [RateFlix Live Site](https://movie-rating-postgres.onrender.com)
- **Git Repository:** [RateFlix Git Repository](https://movie-rating-postgres.onrender.com)

Feel free to reach out for any further assistance or clarification regarding the project..
# RateFlix
