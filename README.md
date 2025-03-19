# *Understanding Student Performance* 
![The Hidden Keys to Student Success](https://png.pngtree.com/thumb_back/fh260/background/20241002/pngtree-and-celebrating-academic-success-students-graduating-with-diplomas-tossing-caps-in-image_16306726.jpg)


## *1. Introduction*  
Student success depends on multiple factors, such as study habits, parental involvement, and access to resources. Using data science, we analyze which factors impact academic performance the most and how we can use this information to improve learning outcomes.  

---

## *2. Data Preparation & Exploration*  

### *2.1 Data Cleaning*  
- *Missing Values:* Replaced missing numerical values with the average and categorical values with the most common category.  
- *Categorical Variables:* Converted non-numeric data into numbers (e.g., "Yes" = 1, "No" = 0).  
- *Scaling:* Adjusted all numerical values to a common scale for better model performance.  
- *Outliers:* Removed extreme values that could distort predictions.  

### *2.2 Key Insights from Data*  
- *Attendance & Study Hours* have a strong impact on exam scores.  
- *Parental Support* plays a key role in student success.  
- *Extracurricular Activities & Sleep Hours* show little correlation with performance.  

---

## *3. Machine Learning Models*  

### *3.1 Models Tested*  
We experimented with:  
- *Linear Regression* (predicts scores based on weighted factors)  
- *Decision Tree* (creates rules to predict performance)  
- *Random Forest* (combination of multiple decision trees)  
- *Gradient Boosting* (advanced ensemble learning method)  

### *3.2 Model Comparison*  

| Model               | Mean Squared Error (MSE) | R² Score |
|---------------------|------------------------|----------|
| *Linear Regression*  | 0.084 | 0.873 |
| *Decision Tree*      | 0.213 | 0.679 |
| *Random Forest*      | 0.092 | 0.862 |
| *Gradient Boosting*  | *0.044* | *0.934* |

✅ *Gradient Boosting was the best model*, explaining 93.4% of the variation in student scores.  

---

## *4. What Matters Most? (Feature Importance)*  

*Top Predictors of Student Performance:*  
1. *Attendance* – Students who attend more classes perform better.  
2. *Study Hours* – More time spent studying improves scores.  
3. *Previous Scores* – Past performance is a good indicator of future success.  
4. *Parental Involvement* – Active parental support leads to better academic results.  

---

## *5. Model Evaluation & Interpretation*  

### *Predictions vs Actual Scores*  
Our model’s predictions closely match real student scores:  

![Predictions vs Actual](attachment:image2.png)  

There are small differences in some cases, meaning additional factors (such as motivation or test anxiety) may influence performance.  

---

## *6. Key Takeaways & Recommendations*  

### *What We Learned*  
- *Regular Attendance & Study Habits* are the strongest factors in academic success.  
- *Parental Support & Access to Resources* also play a crucial role.  
- *Machine Learning can accurately predict student performance*, helping educators and parents make better decisions.  

### *How This Can Be Used*  
- *Schools:* Encourage attendance and structured study plans.  
- *Parents:* Be involved in students’ learning routines.  
- *Future Research:* Include psychological and socioeconomic factors for more accurate predictions.  

---

## *7. References*  
- Hanushek, E. A., & Woessmann, L. (2011). "The Economics of International Differences in Educational Achievement."    
- Bishop, J. H. (1997). "The Effect of Curriculum-Based External Exit Exam Systems on Student Achievement."  
- [The Hidden Keys to Student Success: What Really Drives Performance?](https://medium.com/@crispinoigara/the-hidden-keys-to-student-success-what-really-drives-performance-b88b2aef37b3)

---

This project highlights how *data-driven insights can improve education*. By focusing on key success factors, we can better support students and improve academic outcomes.  

---
