# UPC-AML-ArchitectureClassif

## How To Run? 
1. On a Google Drive Account, create an empty directory in which all the Colab Files should be placed. If in any of them the 'project_dir' is requested, specifiy the location to this Directory. 
2. From here on all chunks of all notebooks should be ran in the order that is specified (in numerical order by fe. running '1_1_... ' before '1_2_...'). Each of the notebooks has the necessary instructions included in between chunks. The main functions and possible relevant details are listed for each of the notebooks below:
    - '1_0_data_scraper.ipynb' is used the necessary empty data folder and then scrape and download in images from http://invarquit.cultura.gencat.cat/Cerca/. Note that this will take a long while to download. 
    - '1_1_train_test_split.ipynb' is to create the necessary file structure used later for model training (keras requires specific formats in order to use   'flow_from_directory'-functions. 
    - '2_1_feature_extraction_cnn.ipynb' is used to extract features using pre-trained convolutional neural networks (cnns). The necessary file structure to save the extracted features in is created. 
    - '2_2_feature_extraction_no_cnn.ipynb' is similar to the previous notebook, except for using a non-deep-learning method called SIFT. 
    - 
