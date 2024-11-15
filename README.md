# Objectives
This exercise illustrates how to access web-hosted APIs, get back a response in JSONLinks to an external site. format, and extract the information we need from the JSON. Accessing APIs is a key skill for data analysts. We can use web APIs to get stock data, weather data, and much more. We'll use an API to access song lyrics or poems in this exercise. We don't care which API - there are many and they change. The skill skills are being able to (a) make an API request and (b) find the information we need in the returned response. 
<br>
Helpful Hint: You can make a simple API request directly in your browser to test it BEFORE making the same request from your notebook or script.
<br>

# Before Starting: Install SpaCy (Multi-Step Process) 
## First - Read
Read about spaCy and spaCy NLP pipelines - the installation process is not easy. Read first. 

1. spaCy is a library for natural language processing.

See: https://spacy.io/Links to an external site.
spaCy 101: https://spacy.io/usage/spacy-101Links to an external site.
installation: https://spacy.io/usageLinks to an external site.

2. spaCy provides pre-trained pipelines to process text. For example, the "en_core_web_sm" package is a small English pipeline that supports all core capabilities and is trained on web text.

3. spacytextblob is a pipeline component that enables sentiment analysis using the TextBlobLinks to an external site. library.  

See https://spacy.io/universe/project/spacy-textblobLinks to an external site.

## Second - Install
1. Install  spaCy and its pipeline.  You must select your options first and it will provide the necessary commands for your type of system.

2. Verify: Select your options - then take a screenshot and post it along with the commands provided. 

3. Install spaCyTextBlob

## Third - Document Results of each Command
1. You will need to open a terminal and run each command.

2. Verify: Run each command one at a time and verify each step completes successfully before continuing. Use screenshots and post any error messages as you proceed. 

## Fourth - Get Help as Needed
1. We need the above information to help solve any Why doesn't my spaCy work?" issues.  You can post your screenshots by themselves if you like - before your submission.

2. Save time by verifying these common issues:  Use the correct kernel (with all your installed dependencies) and in the pyvenv.cfg file change 'include-system-site-packages' to 'true' .

# Requests, JSON, and basic NLP with spaCy

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

## Rubric

* (Question 1) Lyrics printed: 1 pt
* (Question 1) File created and submitted with notebook: 1 pt
* (Question 2) Correct polarity reported: 1 pt
* (Question 2) Question answered thoughtfully: 1 pt
* (Question 3) Function defined as specified: 1 pt
* (Question 3) Song lyrics retrieved and stored in separate files (0.5 pts/song): 2 pts
* (Question 4) Polarity scores printed (with appropriate label containing song title, .25 pts/song): 1 pt
* (Question 4) Questions answered thoughtfully: 2 pts


## Reference: https://github.com/wmnlp-materials/json-sentiment