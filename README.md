# Age-and-Gender-Detection
This project focuses on predicting the age and gender of individuals using deep learning techniques. A convolutional neural network (CNN) is implemented using TensorFlow and Keras. The model is trained on the UTKFace dataset, a large-scale face dataset with annotations of age, gender.
# UTKFace Dataset
The UTKFace dataset is a comprehensive resource for face-related tasks, providing the following attributes for over 20,000 face images:
                      
Age: Spanning from 0 to 116 years old                                                                                                                                                
Gender: Categorized as Male or Female                                                                                                                                              
Ethnicity: Detailed information about the ethnic background                                                                                                                          
# Overview
The project includes:

• Exploratory Data Analysis (EDA) to understand dataset characteristics                                                                                                              
• Preprocessing steps for cleaning and preparing facial images                                                                                                                       
• Model creation using a CNN architecture for age and gender prediction                                                                                                              
• Training and evaluation of the model on the UTKFace dataset                                                                                                                        
• Results visualization, including accuracy and loss graphs                                                                                                                          
• Prediction examples on new facial images                                                                                                                                           

# Download and Prepare the UTKFace Dataset:
Obtain the UTKFace dataset and place it in the ./UTKFace/ directory                                                                                                                  
                                                                                                                                               
# Libraries and Technologies Used
• NumPy - For numerical computing
• Pandas - For data manipulation and analysis
• Matplotlib - For data visualization
• Seaborn - For statistical data visualization
• TensorFlow - Deep learning framework
• Keras - High-level neural networks API
• TQDM - For adding progress bars to loops
• PIL - Python Imaging Library for image processing



Results
Accuracy Graph

Loss Graph

Prediction Examples
Original Gender: Female, Original Age: 32
Predicted Gender: Female, Predicted Age: 31

Original Gender: Male, Original Age: 42
Predicted Gender: Male, Predicted Age: 38

Original Gender: Female, Original Age: 28
Predicted Gender: Female, Predicted Age: 28
