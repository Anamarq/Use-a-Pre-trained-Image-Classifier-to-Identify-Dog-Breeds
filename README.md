# Dog Bred Classifier

## Program Outline

This capstone project required us to accomplish the following tasks:

### Timing the Program
- **Measure program runtime**: We measured the program's execution time using the `time` module.

### Program Input
- **Get user inputs**: Collected inputs directly from the user via the command line.
- **Command line arguments**: Used command line arguments to receive user inputs.

### Creating Pet Image Labels
- **Generate labels from filenames**: Created labels for pet images based on their filenames.
- **Store image labels**: Stored the generated labels in a data structure (e.g., a dictionary).

### Classifying and Comparing Labels
- **Create classifier labels**: Used a classifier function to analyze the images and generate classification labels.
- **Compare labels**: Compared the classifier labels with the original pet image labels.
- **Store labels and comparisons**: Stored the pet image labels, classifier labels, and their comparisons in a complex data structure (e.g., a dictionary of lists).

### Classifying Labels as 'Dogs' or 'Not Dogs'
- **Binary classification**: Classified all labels as 'dogs' or 'not dogs' using a `dognames.txt` file.
- **Store new classifications**: Stored the new classifications in the complex data structure (e.g., a dictionary of lists).

### Calculating Results
- **Evaluate performance**: Used the labels and their classifications to assess how well the algorithm performed in classifying images.
- **Print results**: Displayed the evaluation results.

  ## Running the Project

To run the project, use the following commands:
### Requirements
Install needed requirements id needed
- **Command:**  
  ```bash
  pip install -r requirements.txt

### Running a Specific Architecture and Pet Image Folder
- **Command:**  
  ```bash
  python check_images.py --dir <dog images folder path> --arch <architecture vgg | alexnet | resnet> --dogfile <textfile that contains dog names>
- **Example:**
To run the project with the VGG model, use the following command:
  ```bash
  python check_images.py --dir pet_images/ --arch vgg --dogfile dognames.txt

### Running the 3 models (resnet, alexnet and vgg) and store results in their corresponding files
- **Command:**  
  ```bash
  sh run_models_batch.sh

In Linux, The task could be performed using the command sh run_models_batch_uploaded.sh, which created three text files with the results for each architecture: vgg_uploaded-images.txt, alexnet_uploaded-images.txt, and resnet_uploaded-images.txt.

## Refrences:
https://www.udacity.com/course/ai-programming-python-nanodegree--nd089
