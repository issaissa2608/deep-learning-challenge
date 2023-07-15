# deep-learning-challenge

## Results: Using bulleted lists and images to support your answers, address the following questions:


## Data Preprocessing


   * What variable(s) are the target(s) for your model?

       * IS_SUCCESSFUL is target column
  *  What variable(s) are the features for your model?

       * All other columns are features excludeing
   * What variable(s) should be removed from the input data because they are neither targets nor features?

       * 'EIN' and 'NAME'
   ## Compiling, Training, and Evaluating the Model

   * How many neurons, layers, and activation functions did you select for your neural network model, and why?

       * First layer is 9 neurons and second layer is 18 neurons.
   * Were you able to achieve the target model performance?

       * Not really, accuarcy is only 72%
   * What steps did you take in your attempts to increase model performance?

       * Tried adding another layer and join 'EIN' and 'NAME' back but it does not work.
   ## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
 * In my first model, I used to two layers, first was 80, and second was 30. And I reached the accuracy: 0.7248979806900024
 * In second model, I increased the layers and changed the unit amount. The accuracy reached 0.7268804907798767
 * Third model was applied with new activation function. However, The accuracy was 0.7258309125900269. There was no big change for that.
 * Finally, I exported the third model and saved it as 'AlphabetSoup.h5'
