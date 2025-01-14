# Stroke-Prediction

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths. A stroke happens when the blood supply inside the brain is disrupted, killing brain cells. If this happens in a part of the brain that controls the body's automatic 'life support' systems like breathing and heartbeat, it can be life-threatening.

The aim of this project is to develop predictive models to help prevening from people at risk of stroke, using data from various research articles depending on parameters such as age and gender and more precise health one such as hypertension, body mass index and smoking status.

This dataset is large and has the particularity that the target variable used in the models, namely stroke, is highly unbalanced (only 5% of people have already had a stroke). To solve this problem, I chose to randomly resize the dataset to achieve a stroke / no stroke ratio of 38 / 62%. There is therefore less data but the set is more balanced.
