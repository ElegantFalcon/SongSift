Song Sift is a GitHub project that utilizes various technologies and libraries to create a web application for song analysis and recommendation. It combines machine learning, data processing, and APIs to provide a powerful tool for music enthusiasts.

Tech Stacks Used
Intel OneAPI: A set of tools and frameworks for developing high-performance, cross-architecture applications. It is used in this project for optimized machine learning computations.
scikit-learn: A popular machine learning library in Python, used for building and training machine learning models for song analysis.
FastAPI: A modern, fast (high-performance) web framework for building APIs with Python. It is used to create the backend API for the Song Sift application.
SCSS: A popular extension of CSS, used in this project for styling the user interface.
React: A JavaScript library for building user interfaces. It is used in this project to create the frontend of the Song Sift application.
Vite: A fast build tool for modern web applications. It is used in this project for fast development and building of the frontend.
Firebase: A mobile and web application development platform. It is used in this project for authentication, hosting, and database services.
Python: A high-level programming language, used extensively in this project for machine learning model training, data processing, and backend development.
Machine Learning Training Model: The project includes a trained machine learning model for song analysis and recommendation.
Dataset: A curated dataset of songs and their features is used for training and analysis purposes.
Pandas: A Python library used for data manipulation and analysis. It is used in this project for handling datasets.
CSS (SASS): Cascading Style Sheets is used for styling the user interface, and SASS is an extension of CSS that provides additional features.
ShazamCoreAPI: An API for integrating Shazam music recognition functionality into applications.
BardAPI: An API that provides access to a vast music library, allowing developers to retrieve information about songs, artists, albums, and more.
Project Structure
The project follows a typical structure for a Python web application, with separate directories for frontend and backend code. Here's an overview of the project structure:
<br/>
├── frontend<br/>
│   ├── public<br/>
│   ├── src<br/>
│   ├── ...<br/>
├── backend<br/>
│   ├── app<br/>
│   ├── models<br/>
│   ├── ...<br/>
├── dataset<br/>
│   ├── songs.csv<br/>
├── notebooks<br/>
│   ├── data_preparation.ipynb<br/>
│   ├── model_training.ipynb<br/>
├── .gitignore<br/>
├── LICENSE<br/>
├── README.md<br/>
├── requirements.txt<br/>
The frontend directory contains all the code related to the frontend of the Song Sift application, including React components, stylesheets, and asset files.
The backend directory contains the backend API code written in Python using the FastAPI framework. It includes the API routes, models, and other utility functions.
The dataset directory contains the dataset file songs.csv used for training and analysis.<br/>
The notebooks directory contains Jupyter notebooks for data preparation and model training. These notebooks provide a step-by-step guide on how the dataset is prepared and how the machine learning model is trained.<br/>
The .gitignore file specifies which files and directories should be ignored by Git.<br/>
The LICENSE file contains the license information for the project.<br/>
The README.md file is the current file you are reading, which provides an overview of the project and its components.<br/>
The requirements.txt file lists all the Python dependencies required to run the project.<br/>
