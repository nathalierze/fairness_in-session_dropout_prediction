Evaluation of Fairness of the In-session dropout prediction model

The increasing use of machine learning models in education is accompanied by some concerns about their
fairness. While most research on the fairness of machine learning models in education focuses on
discrimination by gender or race, other variables such as parental educational background or home literacy
environment are known to impact children's literacy skills too. This paper, therefore, evaluates three different
implementations of in-session dropout prediction models used in a learning platform to accompany German
school classes with respect to their fairness based on four different fairness measures. We evaluate the models
for discrimination of gender, migration background, parental education, and home literacy environment.
While predictive parity and equal opportunity are rarely above the defined threshold, predictive equality and
slicing analysis indicate that model quality is slightly better for boys, users with higher parental education,
users with less than ten books, and users with a migrant background. Furthermore, our analysis of the temporal
prediction shows that with increasing accuracy of the model, the fairness decreases. In conclusion, we see that
the fairness of a model depends on 1) the fairness measure, 2) the evaluated demographic group and 3) the
data with which the model is trained. A random state is not set, thus, results might differ marginally.

Further details described in:
N. Rzepka, K. Simbeck, H.-G. Müller, and N. Pinkwart
Fairness of In-session Dropout Prediction
Proceedings of the 14th International Conference on Computer Supported Education - Volume 2: CSEDU,
SciTePress, 2022, ISBN 978-989-758-562-3 

Dropout Prediction Model Described in: 
N. Rzepka, K. Simbeck, H.-G. Müller, and N. Pinkwart
Keep It Up: In-session Dropout Prediction to Support Blended Classroom Scenarios
Proceedings of the 14th International Conference on Computer Supported Education - Volume 2: CSEDU,
SciTePress, 2022, ISBN 978-989-758-562-3 

The repository of the prediction model can be found at:
10.5281/zenodo.7744533

How to use:
The data files can not be made publicly available due to GDPR contraints. However, a metadata schema and data dictionary can be found in the folder 00_metadata