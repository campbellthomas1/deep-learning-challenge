Overview: 
    The purpose of this analysis is to try to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

Results:

    Data Preprocessing:

        What variable(s) are the target(s) for your model?
        
        The target vraiable for my model was the 'IS_SUCCESSFUL' data column from the given dataset.

        What variable(s) are the features for your model?

        The feature variables are the columns that did not get dropped along with the 'IS_SUCCESSFUL' column. Although more did get fropped for optimization later on.

        What variable(s) should be removed from the input data because they are neither targets nor features?

        I removed the 'EIN' and 'NAME' columns.


    Compiling, Training, and Evaluating the Model:

        How many neurons, layers, and activation functions did you select for your neural network model, and why?

        I used 10 for 1 and then 5 for 2 just trying to figure out where I was at and what could work.

        Were you able to achieve the target model performance?

        I was not and I'm sure with more practice I would be able to. I seemed to not be able to gety past 75% and that was kind of frustrating but oh well. Idid some research on  tensorflow's website and on stack overflow as well to try and improve the accuracy.

        What steps did you take in your attempts to increase model performance?

        I got rid of another column which didnt seam to do much and then I used 'sigmoid' in different spots and 'relu' in others. I also changed the nuerons as well.


