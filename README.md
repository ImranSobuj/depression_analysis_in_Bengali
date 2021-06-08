# depression_analysis_in_Bengali
Bengali Depression Analysis. 
Depression is a crucial factor in suicide. However, there are few works on  depression analysis in the Bengali language based on social media data. In this  paper, we proposed a Facebook users depression extraction model using Recurrent  Neural Network. This work aims to analyze Facebook user status updates over time  to see whether the user is depressed or not. 

# Introduction
Every suicide is a tragedy and to some degree a mystery. Suicide often stems from a deep feeling of hopelessness. Suicide is the 10th leading cause of death worldwide [1]. According to the World Health Organization (WHO), approximately 8,00,000 people die due to suicide every year, which is one person every 40 seconds. While high-income countries had the highest incidence of 11.5 per 1,00,000.00, in low and middle-income countries 79 % of the world's suicides occurred.  Rates of completed suicide are higher in men than women globally. 

Depression is a key factor in suicide. Although Facebook is undoubtedly a good platform to communicate with each other, Mamun & Griffiths (2019) examined the association between Facebook addiction and depression which shows 39.7% of Bangladeshi students are ‘Facebook Addicted’. In Bangladesh, undergraduate fresher students are prone to suffering from 52.5% depression and 57.8% anxiety [2]. These can lead to suicide and suicidal behaviors among students in serious cases [3].  However, these statistics are all survey-based, and they didn’t analyze the social media data which is one of the most recently used platforms by Bangladeshi young people to express their thoughts and daily feelings. 

Though depression analysis using paper-and-pencil has been studied for a long time, the acceptance of depression analysis through technology as a valid and reliable way is not yet established. There are very few research works on depression analysis based on social media data. However, most of those research works are dealt with the English language. Ayah Zirikly et al.[4] proposed an assessment of a suicide risk system based on social media data. 

Victor Leiva et al.[5] introduced early depression detection of social media users to prevent suicide occurrences. They used two time-aware classification measures: ERDE5 and ERDE50; they validate their results by applying different machine learning algorithms, and combinations of them. They had a sufficient dataset to use the deep learning model to compare their result, however, they did not use that for comparison purposes.

Recently, A. A. Choudhury et al utilized three machine learning algorithms to analyze depression among Bangladeshi Undergraduates [6]. However, their dataset was small and the highest accuracy was 75%. Masum Billah et al. introduced ‘Depression detection from Bangla Facebook status’ using machine learning [7]. They achieved the highest 77.96 % accuracy for SGDC with unigram + emoticons as a feature. 

One recent study, however, applied Long Short Term Memory (LSTM) Recurrent Neural Network technique to evaluate depression in Bangla language [8]. They tried different hyperparameter tuning to get the best working model; the best accuracy was 86.3% for 5 layered LSTM with size 128, batch size 25, and learning rate 0.0001 over 20 epochs. Yet their dataset to train the model was small and inefficient. 

The researcher who developed Bangla depression detection system did not consider multiple levels for their datasets which is very important for recommending online resources. Because, if the tag of the dataset is only either depressed or non-depressed, then the users may get anti-depressed online resources; although the users are not depressed. Therefore, the individual may get annoyed at the system or may not be optimistic to use the system. Furthermore, they did not consider timestamp i.e.,  
when the post is published. As time is an important factor to be considered whether the user is depressed or not for prediction in the future.


Thus, our research aim is to develop Facebook users’ depression extraction model for suicide risk prediction in the Bengali language using Recurrent Neural Network that will overcome the previously studied limitations and we expect to improve the RNN model. The goal of this research work is to develop a state-of-the-art depression extraction model 


[1]	World Health Organization, “Suicide Prevention.” [Online]. Available: https://www.who.int/mental_health/prevention/suicide/suicideprevent/en.
[2]	M. A. Al Mamun and M. D. Griffiths, “The association between Facebook addiction and depression: A pilot survey study among Bangladeshi students,” Psychiatry Res., vol. 271, pp. 628–633, Jan. 2019, doi: 10.1016/j.psychres.2018.12.039.
[3]	S. M. Y. Arafat and M. A. Al Mamun, “Repeated suicides in the University of Dhaka (November 2018): Strategies to identify risky individuals,” Asian Journal of Psychiatry, vol. 39. Elsevier B.V., pp. 84–85, Jan. 01, 2019, doi: 10.1016/j.ajp.2018.12.014.
[4]	A. Zirikly, P. Resnik, Ö. Uzuner, and K. Hollingshead, “<title/>,” in Proceedings of the Sixth Workshop on Computational Linguistics and Clinical Psychology, 2019, pp. 24–33, doi: 10.18653/v1/W19-3003.
[5]	V. Leiva and A. Freire, “Towards suicide prevention: Early detection of depression on social media,” in Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics), Nov. 2017, vol. 10673 LNCS, pp. 428–436, doi: 10.1007/978-3-319-70284-1_34.
[6]	A. A. Choudhury, M. R. H. Khan, N. Z. Nahim, S. R. Tulon, S. Islam, and A. Chakrabarty, “Predicting Depression in Bangladeshi Undergraduates using Machine Learning,” in Proceedings of 2019 IEEE Region 10 Symposium, TENSYMP 2019, Jun. 2019, pp. 789–794, doi: 10.1109/TENSYMP46218.2019.8971369.
[7]	M. Billah and E. Hassan, “Depression Detection from Bangla Facebook Status using Machine Learning Approach,” Int. J. Comput. Appl., vol. 178, no. 43, pp. 9–14, Aug. 2019, doi: 10.5120/ijca2019919314.
[8]	A. H. Uddin, D. Bapery, and A. S. M. Arif, “Depression Analysis from Social Media Data in Bangla Language using Long Short Term Memory (LSTM) Recurrent Neural Network Technique,” Jul. 2019, doi: 10.1109/IC4ME247184.2019.9036528.


