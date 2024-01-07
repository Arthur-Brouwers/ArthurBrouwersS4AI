## Data Preparation & Analysis
<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You are able to aggregate and prepare given datasets as well as other (open) datasets and use them in data analysis and identify opportunities for predictive analytics."</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Proficient</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        <p>
        I have worked on cleaning my data to use it in models and visualise it. I also added postcode to my data since it was not present in the dataset. I explain what my data contains by visualising it and I can explain strange data. 
</br>
Anna Kadurina peer reviewed me and gave me the following feedback: "Before you do any changes such as the Postcode, or the other Data Preparation steps, you need to explore the data a bit. See what you have already, so create a Data Understanding chapter, and then make all the changes. (Novemebr 29th)".
  </br>
  Before I got her feedback, my data exploration was very small and I have made more visualisations to understand the data.
  </tr>
</table>

## Model Engineering
<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You are able to use findings from data analysis to preprocess data, apply machine learning algorithms and evaluate the quality and usefulness of produced models, for a defined domain."</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Proficient</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        <p>
          <h2>Nearest Neighbours</h2>
          I used four models to try to make the best possible prediction. I started with nearest neighbours, however the accuracy was only ~5%. 
          </br>
  </br>
  <h2>Linear Regression</h2>
          Then I tried linear regression as I thought the relation between the features and price could have been linear. The model gave me an R2 of 65 which is decent, but I defined in my analytic approach that I want to aim for 70-80% accurate so I wanted to see if there was another model that has a higher accuracy.
          </br>
  </br>
  <h2>Clustering</h2>
          I got the idea from Niek to cluster the data and then use a model to make a more accurate prediction using the cluster's data. Since location is the most important feature for determining the house price, I tried to make clusters based on postcode since they are the best indicator for location. The count of unique postcodes in my dataset is around 1800 and the amount of rows is around 5000. I visualised that some of the postcodes only had one datarow, so it has no data to relate to. Although I believe this would be a good way to make more accurate predictions, it did not work in my project, most likely due to the size of the dataset. 
  </br>
  </br>
  <h2>Random Forest</h2>
  Then I tried random forest. Random forest gave me the best accuracy with an R2 of 79. The mean percentage error is 15%, while the margin for home appraisers is 10%. My stakeholder did some inference with his houses for sale. The errors in the predictions were within the margin for home appraisers (<10%), since my stakeholder is active in the middle class houses. The mean percentage error is influenced by the outliers as well, so in the middle class houses the error would be smaller. 
  </tr>
</table>

## Explainable AI
<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You deliver AI projects that follow the three 'Explainable AI' principles of transparency, interpretability, and explainability."</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Beginning</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        <p>
          I explain what I am doing in my personal challenge by adding comments with explanations and how to interpet the data. Temuulen Munkh-Erdene had to peer review me and he agreed: "The model makes sense and has comments, so they are clear. (November 30th)"
</br>
  </br>
I could have explained better how the models work, but overall I think I explain the most important aspects in the project
        </p>
    </td>
  </tr>
</table>

## Professional Standard
<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You show that you conduct work in accordance with an industry supported methodological approach (AI Project Methodology) in terms of your project's goals, stakeholder involvement, applied research, decision making and reporting."</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Proficient</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        <p>
         I worked on the project according to the AI methodology. I tried to follow the phases to make the process go as smooth as possible. Sometimes I did something in a different order, but I followed the general lines of the AI methodology. 
        </br>
        </br>
  In involved my stakholder by interviewing him and in the end, showed him the final project by letting him do inference in the frontend. He was very pleasant with the outcome of the project. Nick Welman agrees on me having involved the stakeholder in a good way: "the stakeholder is involved in a constructive way (November 28th)". 
  </br>
    </br>
I also played the moral design game where I made nuanced choices based on the character I had to play. 
        </p>
    </td>
  </tr>
</table>

## Personal Leadership
<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You are aware of your strengths and pitfalls in ICT as well as your personal development. To nurture personal growth you are able to engage in actions that align with your core values, in a way that suits you. "</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Proficient</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        <p>          
          I did the exercise on Personal Leadership. By doing this exercise, I was more aware of my qualities and what I love to do. 
            </br>
            </br>
          I asked feedback frequently and implemented the given feedback. I also talked to fellow students about issues I had and that way we helped eachother. When I missed the day where the exercise for personal leadership was done, me and my groupmembers decided to catch up by doing the exercise our self.
        </p>
    </td>
  </tr>
</table>

## Internship Preparation
<table>
  <tr>
    <th><strong>Learning Outcome</strong></th>
    <td>"You create chances to acquire and define an internship assignment based on a match between your ambitions, the school’s requirements and the field of expertise related to your profile or specialisation."</td>
  </tr>
  <tr>
    <th><strong>Proficiency Rating</strong></th>
    <td>Proficient</td>
  </tr>
  <tr>
    <th><strong>Explanation</strong></th>
    <td>
        <p>          
          I aquired an internship at Squadra in Oss, but the actual assignment is yet to be determined. It would be something with webscraping for PowerEnrich where I would work on the front- and backend.
        </p>
    </td>
  </tr>
</table>
