# Predicting Depression Disorder
<br/>
<h3> Predicting the presence of individual Depression </h3>
Depression and anxiety disorders are the most prevalent mental health conditions worldwide. In general‚ about 1 out of every 6 adults will have depression at some time in their life. 
In this study we will use the data collected by an on-line version of  <a href='https://www.psytoolkit.org/survey-library/depression-anxiety-stress-dass.html'>Depression Anxiety Stress Scales (DASS) </a> , along with The Ten Item Personality Inventory (TIPI) questionnaire and some personal features to predict depression.
  <h3>Design</h3>
  The project will show whether an individual has Depression disorder. The Depression Scaling in DASS was categorized into High and Normal, so each indiviual will  be classified as Normal or High Depression.  Data cleansing and Exploration were done before testing and evaluating models.
  <h3>Dataset</h3>
 Dataset was obtained from  <a href='https://www.kaggle.com/yamqwe/depression-anxiety-stress-scales'>kaggle </a> in form (.csv). 
  <br/> dataset contains 172 columns and 39,775 rows:
  <ul>
    <li>(DASS) Research survey's answers by individuals </li>
    <li>TIPI Questionaries</li>
    <li>Peronal Information</li>
  <li>Device Related data</li>
  </ul>
  The features that will be focused on, are depression, anixety and stress (calculated from DASS) as well as (TIPI) Five personality dimensions: (1) Extraversion, (2) Agreeableness, (3) Conscientiousness, (4) Emotional Stability, and (5) Openness to Experience. 
  <h3>Model Evaluation and selecting</h3>
  Before working with model, some feature engineering were applied. Some features were dropped, other recategorized and encoded.
  A scaling was also done.
    A few classification models were chosen to predict and classify depression,
      <ul>
    <li> k-nearest neighbors algorithm (k-NN) </li>
    <li>logistic regression(LR)</li>
    <li>support-vector machines SVM</li>
  <li><random forest (RF)</li>
  </ul>
    All the models show an approximitely the same accuracy with mean 75%. To optimize accuracy, some hyper parameters were changed, corss-validation was done but result didn't chnage much.
  <h3>Tools</h3>
  jupyter nootbook with some DS libraries such as pandas and numpy to maipulate the data, matplotlib and seaborn to visulalize the data and
scikit learn for model for realted libraries. 
