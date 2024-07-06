# Website-Classification
This is my first real project. Where I have to predict the intent of website from the screenshot of the home page of a website that in which category it falls. </br>
1. Educational Website <br>
2. E-commerce Website <br>
3. Job Website <br>
The project inlcude the following step
<li>
  <ol>Data Gathering: I first gather the data which was taking screen from the whole home page of the website and saving in the pc. I gather the data in three categories <br> 1.Education
    <br>2.Job <br> 3.E-commerce</ol>
  <ol>The File name Text Extraction from Images do extract the text the from the images with help <b>pytersseract</b>. It contain the code the how to extract text from the image and store in the csv file</ol>
  <ol>I then store the data from the output.csv to X, y and do some preprocessing</ol>
  <ol>Tfidf Vectorizer is to convert the text to embedding to then apply model on it</ol>
  <ol>A model is train on the data from which I gather and get an accuracy 90.01 something</ol>
</li>

The Model is Complete and have accurately predict the other Websites. 
If you need any help contact me at (pirzadahasnain.18@gmail.com)
