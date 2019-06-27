# Run Trained Model
#### To run the pretrained model by loading the parameters use the [main.py](/main.py) file.

# Train Model
### [Seq2SeqModel.py](/Seq2SeqModel.py) trains the model by importing and calling the required predefined functions.
#### The sequence of python files to be followed:
1. [Data_preprocessing.py](/Data_preprocessing.py) : 
source and target words are converted into integer sequence i.e its character is replaced by its corresponding integer index.
2. [Model_Inputs.py](/Model_Inputs.py): 
creates and returns placeholders necessary for further building the model.
3. [Layers.py](/Layers.py): 
encoder and decoder layers are defined here.
4. [Batch_Metrics.py](/Batch_Metrics.py): 
batch generater function is defined here.
