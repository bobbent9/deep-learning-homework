# deep-learning-homework

This assignment uses a RNN model to predict Bitcoin closing prices using a previous closing prices. The instructions also state that a FNG index would be used for comparison, but the starter file was an exact copy of the vlosing prices model. 

Which window size works best for the model?
I prefered the larger window size of 10 when testing the model. The lower the window, the more the predictions appeared to track the actual performance, however this was more a reflection of only having one day's change to predict. The larger window provided a smoother prediction track and would help minimize the guesswork on larger volatility swings. 