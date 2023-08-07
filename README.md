# Anki Card Generator from PDF Files

This code can generate Anki flashcards; the prompt can be changed depending on your specific needs, but this was made for sentence mining.

# Environment Setup
In order to set your environment up to run the code here, first install all requirements:

```shell
pip install -r requirements.txt
```

## Generate Flash Cards. 

Simply put your PDF files in the `SOURCE_DOCUMENTS` folder. 

Run the following command to process your data.

```shell
python Anki_flashcards_creator.py
```

It will generated a flashcards.txt file that you can import into Anki. 

#### Things to Remember. 
This will order words based on frequency, in the prompt you can tell chatGPT to ignore common articles such as a/an. You may also explicitly state which words to ignore. a .txt file will be output, hover over the .txt file > open > open with Anki. The limit is at 2500 credits, this is per letter. 

In order to bypass ChatGPT API-Key, look into training your own model; check this video out by Andrej Karpathy: https://youtu.be/kCc8FmEb1nY?si=_l0XEZQnauKrLl5q



