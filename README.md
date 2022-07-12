### Introduction.py


    #Personal Details
    name = 'Devendra Parihar'
    print('Name:',name)
    
    #skills
    s1='Python'
    s2='R Programming'
    s3='SQL'
    s4='Machine Learning'
    s5='Data Science'
    s6='Statistics'
    s7='Probability'
    s8='Data Structure & Algorithm'
    s9='Visualization'
    
    #load Prediction model 
    model = PredictionModel()
    
    #fit data into model
    model.fit(skills)
    data=[[s1,s2,s3,s4,s5,s6,s7,s8,s9]]
    
    #prediction
    result=model.predict(data)
    print(f'Result : {name} is a {result}.')
    
###output

    Name : Devendra Parihar
    Result : Devendra Parihar is a Machine Learning Engineer & Beginner Data Scientist.
    


<!--
**Devparihar5/Devparihar5** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
