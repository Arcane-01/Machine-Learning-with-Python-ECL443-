- The training and the testing set are obtained by splitting the original data in the ratio of 80 to 20 percent. The training set of (40,4) with the labels of (40,1) and the testing set of (11,4) with the labels of (11,1) are obtained. 
    \begin{figure}[H]
    \centering
    \includegraphics[scale=0.9]{Exp1/traintest.PNG}
    \caption{Training and Testing datasets}
    \end{figure}
- Linear regression is implemented with pseudo inverse method. The independent variables are Registered vehicles (thousands),  Fatalities per 100K licensed drivers,  Fatalities involving high blood alcohol, and the dependent variable is Traffic fatalities. The following graphs showing the predicted and actual values were obtained for these three independent variables:
    
    \begin{figure}[H]
    \centering
    \includegraphics[scale=0.75]{Exp1/PI11.PNG}
    \caption{Traffic fatalities vs Registered vehicles (thousands)}
    \end{figure}

    \begin{figure}[H]
    \centering
    \includegraphics[scale=0.75]{Exp1/PI12.PNG}
    \caption{Traffic fatalities vs  Fatalities per 100K licensed drivers}
    \end{figure}

    \begin{figure}[H]
    \centering
    \includegraphics[scale=0.75]{Exp1/PI13.PNG}
    \caption{Traffic fatalities vs Fatalities involving high blood alcohol}
    \end{figure}
    
- Next, when linear regression is implemented with gradient descent, with a learning rate of 0.001 for 1000 iterations, for the same set of dependent and independent variables, the following graphs for the loss over each iteration and actual and predicted values for the three independent variables was obtained.

    \begin{figure}[H]
    \centering
    \includegraphics[scale=0.75]{Exp1/gdloss1.PNG}
    \caption{Gradient Descent Loss}
    \end{figure}

    \begin{figure}[H]
    \centering
    \includegraphics[scale=0.75]{Exp1/gd11.PNG}
    \caption{Traffic fatalities vs Registered vehicles (thousands)}
    \end{figure}

    \begin{figure}[H]
    \centering
    \includegraphics[scale=0.75]{Exp1/gd12.PNG}
    \caption{Traffic fatalities vs  Fatalities per 100K licensed drivers}
    \end{figure}

    \begin{figure}[H]
    \centering
    \includegraphics[scale=0.7]{Exp1/gd13.PNG}
    \caption{Traffic fatalities vs Fatalities involving high blood alcohol}
    \end{figure}
    
- The above steps were repeated for a different set of independent and dependent variables, Licensed drivers (thousands) and Traffic fatalities respectively. The following graphs showing the predicted and actual values of the dependent variables and the gradient descent loss over the iterations were obtained. 

    \begin{figure}[H]
    \centering
    \includegraphics[scale=0.75]{Exp1/PI2.PNG}
    \caption{Traffic fatalities vs  Licensed drivers (thousands)}
    \end{figure}

    \begin{figure}[H]
    \centering
    \includegraphics[scale=0.75]{Exp1/gdloss2.PNG}
    \caption{Gradient Descent loss}
    \end{figure}

        \begin{figure}[H]
    \centering
    \includegraphics[scale=0.75]{Exp1/gd2.PNG}
    \caption{Traffic fatalities vs  Licensed drivers (thousands)}
    \end{figure}
