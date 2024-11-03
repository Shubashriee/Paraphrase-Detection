# Paraphrase Detector

An application using Flask that utilizes **TF-IDF** and **cosine similarity** to determine if a piece of input text is paraphrased based on reference text data provided in the `database1.txt` file.


## Instructions

1. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

2. Add your reference text in `database1.txt`. (This is the text against which paraphrasing will be checked.)

3. Run the application:
   ```bash
   python plag.py
   ```

4. Open the web page in your browser. Enter text in the input field and click on the **"Check Test Results"** button.

5. Input text gets processed by converting to lowercase, removing punctuations and performing calculations.

6. The paraphrase percentage is then displayed on the web page.
