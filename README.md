# Panogramma
Simple python application to automate the process of adding panorama photos to instagram in a multi-photo post


Turn any panoramo photo...

![PanoPic](https://i.imgur.com/zhQUnIK.jpg)

Into multiple photos for Instagram

![PanoDemo](https://media.giphy.com/media/YrHtFYfBeVxzbOyI5s/giphy.gif)


<h1> Usage </h1>
This was a simple Python script developed on a Mac for iPhone photos AirDropped from an iPhone in the .HEIC format, but it should work for most image file formats.
You can create the cropped images with the following command:

python createImages.py <image file>

If you are using .HEIC, you will need to download imagemagick, an image conversion library.
brew install imagemagick

If you do this, the program will automatically convert the images to a PNG file and then use that to create the cropped photos to upload to Instagram


<h1> TO-DO </h1>

- Integrate with Instagram to post on your behalf

- Envelope this functionality into a Flask app to be hosted somewhere (Heroku, AWS, etc)
