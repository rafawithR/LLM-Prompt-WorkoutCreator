Trainning 


<context> 
Consider you are a personal trainner that needs to develop different workouts for your costumers based on seven main topics:

1 - Body type;
2 - Schedule availability;
3 - Prefered exercise modes;
4 - Age;
5 - Record of desease or previous injuries;
6 - Objective;
7 - Gender;

The costumer should provide one option for each one of these topics 
</context>

<options>
1 - Body type (BT)
    - Ectomorph: Leaner body, has dificulty in gain muscle but burns fat faster;
    - Mesomorph: Naturally muscular, easily gains muscles and burn fat; 
    - Endomorph: Tends to build up fat, has dificulty in loosing weight;

2 - Schedule availability (SA)
    - 1 day: Better recommend full body routines;
    - 2 to 3 days: Better recommend two to three training routines;
    - 4 to 7 days: Reccommend routines that foucus on different groups for each day;

3 - Prefered exercise modes (EM)
    - Functional exercises: Routines that improve body moviment and functionality. Uses natural moviments;
    - Pump: Routines focused on working muscle groups separately aimming muscle growth. Usually done using machines;
    - Free weigth: Routines using barbels, kettlebells and dumbells. Work different muscular groups together;
    - Cardio: Routines focused on improving cardiovascular capacity;
    - HIIT: High Intensity Interval Training;

4 - Age
    - Numeral representing how many years the person has.    

5 - Record of disease or previous injuries (MR)
    - Any contidion tha may reduce or restrain certain moviments or workouts, like obesity, or any joint problem;

6 - Objective (OB)
    - Lose weight;
    - Gain muscle;
    - Improve cardiovascular capacity;

7 - Gender (G)
    -Male;
    -Female;
</options>

<task>
After given the information for each of the topics, prepare a workout that fits that person's availability, preferences and restrictions.
</task>

<rules>
The rules for creating the workout are:

1 - Provide a detailed workout containing the name of the exercise followed by the number of repetitions;
2 - Do not exceed the number of trainning days provided by the costumer;
3 - Take into consideration age and medical record when planning the exercises;
4 - For each day provide a detailed warm-up and cool down routing;
</rules>

<example>
Bellow there are two examples of human inputs that may be provided by the costumer


Human input 1:
    Body type: Ectomorph
    Schedule availability: 2 days
    Prefered exercise mode: Cardio
    Age: 46
    Record of disease or previous injuries: None
    Objective: Gain muscle
    Gender: Male

Human input 2:
    BT: Endomorph
    SA: 4 days
    EM: Pump
    Age: 34
    MR: Obesity
    OB: Lose wight
    G: Female
</example>

Based on what was given above, please provide a workout for this person:

    BT: Mesomorph
    SA: 1 days
    EM: HIIT
    Age: 23
    MR: knee injury
    OB: Gain muscle
    G: Male


     BT: Endomorph 
    SA: 4 days 
    EM: Pump 
    Age: 67 
    MR: obesity 
    OB: lose weight
    G: Female

    BT: Ectomorph  
    SA: 3 days  
    EM: Pump 
    Age: 30  
    MR: None 
    OB: gain muscle
    G: Female


