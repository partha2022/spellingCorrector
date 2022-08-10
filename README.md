
# SPELLING CORRECTOR

### PROBLEM STAEMENT
In this project we will be using deep learning approaches to build a spelling corrector.

### DESCRIPTION OVERVIEW
A word needs to be checked for spelling correctness and corrected if necessary, many a time in the contextof the surrounding words. A spellchecker points to spelling errors and possibly suggests alternatives. An autocorrector usually goes a step further and automatically picks the most likely word. In case of the correct word already having been typed, the same is retained.

There are different types of spelling errors.

1. Non-word Errors: These are the most common type of errors. You either miss a few keystrokes or let your fingers hurtle a bit longer. E.g., typing langage when you meant language; or hurryu when you meant hurry.
2. Real Word Errors: If you have fat fingers, sometimes instead of creating a non-word, you end up creating a real word, but one you didn’t intend. E.g, typing buckled when you meant bucked. Or your fingers are a tad wonky, and you type in three when you meant there.
3. Cognitive Errors: The previous two types of errors result not from ignorance of a word or its correct spelling. Cognitive errors can occur due to those factors. The words piece and peace are homophones (sound the same). So you are not sure which one is which. Sometimes your damn sure about your spellings despite a few grammar nazis claim you’re not.
4. Short forms/Slang/Lingo: These are possibly not even spelling errors. May be u r just being kewl. Or you are trying hard to fit in everything within a text message or a tweet and must commit a spelling sin. We mention them here for the sake of completeness.

### TECHNOLOGY USE
Here we will be using  Anaconda Python 3.6 , Keras 2.2.4 using TensorFlow GPU 1.14.0 backend CUDA 10 with CuDNN 10 

### INSTALLATION
Installation of this project is pretty easy. Please do follow the following steps to create a virtual environment and then install the necessary packages in the following environment.

#### In Pycharm

1. Create a new project.
2. Navigate to the directory of the project
3. Select the option to create a new new virtual environment using conda with python3.6
4. Finally create the project using used resources.
5. After the project has been created, install the necessary packages from requirements.txt file using the command 
    pip install -r requirements.txt

#### In Conda

1. Create a new virtual environment using the command
    conda create -n your_env_name python=3.6
2. Navigate to the project directory.
3. Install the necessary packages from requirements.txt file using the command         
    pip install -r requirements.txt




## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/partha2022/spellingCorrector/blob/master/README.md)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Authors

- [@partha](https://github.com/partha2022)


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Deployment

To deploy this project run

```bash
  heroku login
  heroku create
  git init
  git status
  git add .
  git commit -am "commit by partha"
  git push heroku master

  After deployment, heroku gives you the URL to hit the web API
```


## Features

- Light/dark mode toggle
- Live previews
- Fullscreen mode
- Cross platform


## 🚀 About Me
I'm a full stack Data Scientist...

I'm a Data Engineer/Big Data/Hadoop Developer...


# Hi, I'm Partha! 👋


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/partha2022)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/parthass/)


## Other Common Github Profile Sections
👩‍💻 I'm currently working on...

🧠 I'm currently learning...

👯‍♀️ I'm looking to collaborate on...

🤔 I'm looking for help with...

💬 Ask me about...

📫 How to reach me...

😄 Pronouns...

⚡️ Fun fact...


## 🛠 Skills
Python, Spark, Pyspark, Java, Scala, Machine Learning, Deep Learning, Natural Language Processing (NLP), Image Processing/Computer Vision, OpenCV, Numpy, Pandas, Scikit-learn, SciPy, NLTK, Word2Vec, TensorFlow, Keras, PyTorch, Matplotlib, Seaborn, BeautifulSoup, EDA (exploratory data analysis), AWS, Heroku, GIT, Hadoop, HDFS, Hive, Cassandra, Stream sets, SQL, Flask, Web scraping, Control-M, HTML ...


#### INSTALLATION

Install project with pip

```bash
  pip install -r requirements.txt
```
    
#### CONCLUSION

Here we have successfully built a spelling checker and corrector which can be used to correct spelling if the user gives misspelled words.


## Tech Stack

**Client:** Python, Machine Learning, NLP, Nltk, Cassandra, Stream sets, Flask, Webscraping

**Server:**  AWS, Elastic Beanstalk


## Run Locally

Clone the project

```bash
  git clone https://github.com/partha2022/spellingCorrector.git
```

Go to the project directory

```bash
  cd spellingCorrector
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server

```bash
  python clientApp.py
```


## Running Tests

To run tests, run the following command

```bash
  http://localhost:7000/ 
```

