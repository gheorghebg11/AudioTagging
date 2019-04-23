# AudioTagging
This notebook has to be opened with Google Colab. It is set-up to upload the Kaggle dataset, from my own personal Google Drive. In order to use it with your own dataset you will have to upload the files from Kaggle on your google drive, and change the files addresses to your link to your own google drive. The files get deleted after 12h (or less), so you will need to save back on your google drive any file that you create during runtime. Also, don't forget to select the GPU accelerator under Runtime -> Change runtime type.

The current structure is the following:

1) Load the files into Colab
Run all the cells in order to copy the load the dataframes and upload the Kaggle dataset into the Colab environment

2) Data Visualization and Basic Cleaning (can skip and go to Model directly)
Optional section in which you will see some data exploration and a little bit of cleaning. You can skip this section as the new dataframe is also saved and can be directly loaded in the next section.

3) Construct The Model
Contains the class Config with the configuration of the model, the class DataGenerator which constructs the generator, as well as different classes for different CNN models.

4) Run The Model!
This is where the magic happens. Setup the directories, create a config object, create a model and compile it, and then finally run it. You will also see cells for predictions, as well as for saving those predictions out of the Google Colab environemnt.
