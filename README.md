## Integrated Decision Gradients (IDG)
**Integrated Decision Gradients (IDG)** is an extension to the traditional **Integrated Gradients (IG)** method.  
Unlike IG, which treats each interpolated step equally, IDG weighs the gradients based on how much the model's prediction (logit) changes between steps.  
This allows IDG to highlight steps that are more critical to the model's decision-making process.
