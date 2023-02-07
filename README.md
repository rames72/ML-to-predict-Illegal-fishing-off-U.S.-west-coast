# ML-to-predict-Illegal-fishing-off-U.S.-west-coast
This repo includes the Python code that was used to train and test two machine learning models that could discriminate between fishing trips from federal verse state waters using the catch compositions on the landing records (i.e., fish tickets), as well as the normalized training and testing data files. The landing records for training and testing the models were linked to observer data to create the labels. The labels are binary, where 1 denotes trips where the vessel fished exclusively in Federal waters, and 0 denotes trips where the vessel fished exclusively in state waters. Trips that included fishing in both federal and state waters were excluded. The landing records were from open access fixed gear fishing vessels where the plurality of the species landed were groundfish and where the landings occurred on the U.S. west coast (northern Washington to southern California) between 2002 and 2019. The delivery ports, dates, and vessel ID information has been withheld and some initial data preprocessing was performed to protect confidentiality. The code includes data preparation, variable subset selection strategies, model hyperparameter refinements, model diagnostics and data visualizations.
