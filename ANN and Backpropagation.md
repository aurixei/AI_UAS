# Artificial Neural Network and Backpropagation

### Problem Example:
![image](https://github.com/user-attachments/assets/ac422c3a-e56e-4ce2-a073-3dbe887efeb8)
Diketahui:

W1: 0.15

W2: 0.4

W3: 0.6

W4: 0.1

W5: 0.21

W6: 0.31

B1: 1

B2: 1

B3: 1

- Hitunglah output akhir jika input 1 = 1 dan input 2 = 0
- Hitunglah Error dengan target error = 1
- Hitunglah Backpropagation dengan target 1


## **Hitung Output Akhir**

### **Step 1: Understand the Structure of the Network**
- **Inputs:** In1 = 1, In2 = 0 
- **Weights:** W1, W2, W3, W4, W5, W6
- **Biases:** B1, B2, B3
- **Hidden layer nodes:** X1, X2
- **Output node:** Y

![image](https://github.com/user-attachments/assets/03e42488-1f6c-4a41-a5ea-31395281f20a)

### Step 3: Apply Activation Function
![image](https://github.com/user-attachments/assets/c19562f9-d791-4ff0-a3a6-74271ecb0021)
_(e ada di kalkulator, biasanya sebelah pi)_

![image](https://github.com/user-attachments/assets/d58dd7ba-e4cf-4632-8548-cc02229cfa61)

![image](https://github.com/user-attachments/assets/310171fd-409c-43e3-80a1-84b657db3459)

### Step 4: Continue the steps earlier with the next weights until Output.
`Y output = (X1 × W5) + (X2 × W6) + B3`

`Y output = (0.75991 × 0.21) + (0.832018 × 0.31) + 1`

`Y output = 1.41781658`

Activation function for Y:

![image](https://github.com/user-attachments/assets/d9ff0ad6-34dd-4dda-97a7-ee8315c494ab)

## **Hitung Error:**

![image](https://github.com/user-attachments/assets/5a360acd-d1e2-4537-bec7-e78976858f62)

- Y predicted = Output tadi
- Y target = Target error (from soal, dlm case ini 1)

![image](https://github.com/user-attachments/assets/88bc4096-e7a2-4e35-833a-ae617b99d184)

![image](https://github.com/user-attachments/assets/4b2db703-1e5f-47d6-84ca-77b58354186d)

## Hitung Backpropagation:

![image](https://github.com/user-attachments/assets/881ffc60-3b43-471d-aae0-e6db31f68bd9)

- Y predicted = Y output tadi (Yang pertama diitung diatas)
- Y target = target value (dr soal, dlm case ini 1)

![image](https://github.com/user-attachments/assets/dba1eab5-92a8-460c-af93-9f552580e0f9)

_Yes, dikurangin doang. Depannya sama dengan is ga guna idk_

the rest? idk yet ga ngerti jir

## OK so, different source here (Still Backpropagation):

Here's the soal and the already calculated outputs (this case asks for a target of 0,5):

![image](https://github.com/user-attachments/assets/08bfb416-805e-4226-b379-318220b75edd)

### Here are the formulas and the explanations:

![image](https://github.com/user-attachments/assets/56f48d57-ed11-4f94-83fd-a348140e41b4)

![image](https://github.com/user-attachments/assets/f61174e4-dada-4599-bebe-b142bcff8553) 

gw cape jing dahlah lu nonton 
[ini aj](https://www.youtube.com/watch?v=tUoUdOdTkRw)
