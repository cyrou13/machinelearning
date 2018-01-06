# machinelearning
Machine learning toolkit

Main problems to solve:
- Find Data: create a tool to 
    * connect to the PACS or another DICOM source and retrieve interesting data
    * connect to a RIS and retrieve interesting data
    * connect to another medical system and retrive interesting data
==> add meta information such as Orientation / Sequence / Modality / Fat sat ....
- Clean the Data :
    * Images: normalize pixel data, pixel representation, etc...
    * Non images: remove NaNs and infinites, should that be a string? could I categorize it? hot encoding ?
- Data augmentation:
    * Images: rotation, flip, shear, crop, etc...
    * Non images: don't know yet
- Choose and tune the algorithm:
    * WYSIWYG tool to create the netwok, editing the layers parameters and check the tensors shapes
    * expose hyper parameters, loss functions, number of layers if possible, etc...
    * create a banch of training sesssion, collect results and be able to compare it
- Visualize results:
    * predict on new data,
    * identify data that doesn't work within the training set,
- What's next ? compression of the model, encrypt of the inference ?


6 months program:
- Learn the math (2 - 3 months)
- Learn the programming language (1 month)
- Machine learning tutorials and test projects (1 - 2 months)
- Short term passion projects (1+ month)

METIS: Data science and machine learning classes/bootcamps



Optimization of models:
   Compression:
      - Pruning 
      - Weight Sharing
      - Quantization
      - Low Rank Approximation
      - Binary / Ternary Net
      - Winograd Transformation
   Acceleration:
      
   

    
