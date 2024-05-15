# Website-Classification
This is my first real project for a client from the upwork. Where I have to tell the intent of website from the screen of the home page of a website that in which category it falls.
The project inlcude the following step
<li>
  <ol>Data Gathering: I first gather the data which was taking screen from the whole home page of the website and saving in the pc. I gather the data in three categories <br> 1.Education
    <br>2.Job <br> 3.E-commerce</ol>
  <ol>The File name Text Extraction from Images do extract the text the from the images with help pytersseract. It contain the code the how to extract text from the image and store in the csv file</ol>
  <ol>I then store the data from the output.csv to X, y and do some preprocessing</ol>
  <ol>Tfidf Vectorizer is to convert the text to embedding to then apply model on it</ol>
  <ol>A model is train on the data from which I gather and get an accuracy 90.01 something</ol>
</li>

This Project Contain a second part which is related to Computer Vision and which is still to be done. where I have tp train a model on logos and then When I upload an images from the Website home Page along with logo it will compare the logo with already fed logo and predict the intent of the website. So the Comparison is still to be done.
