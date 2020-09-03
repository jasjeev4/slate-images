# slate-images

## Prerequistes:

*  Ensure you have Python 3.7 or greater installed. You can opt to set up a virutal environment or a conda enviroment.
*  Make sure pip works with the python installation 

This is a version of the [slate](https://github.com/ianstormtaylor/slate) rich text editor with the ability to add images added in.

The steps to run this project are as follows:

1. Add the project directory to the PYTHONPATH environment variable on your local system. (Instructions for Windows: [here](https://stackoverflow.com/questions/3701646/how-to-add-to-the-pythonpath-in-windows-so-it-finds-my-modules-packages))

2. Run 'pip install -r requirements.txt' from the project root directory
  
3. Use ‘django-admin runserver --settings=slate.settings’ from the project root directory to run the server
  

That&#39;s it! You should now be able to navate to your localhost via the following link in your browser:

http://127.0.0.1:8000/

A screenshot of a prototype is provided:

![slatepreviewpng](https://i.ibb.co/PC6d36T/slate-preview.png)
