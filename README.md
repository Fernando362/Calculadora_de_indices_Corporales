# Calculadora_de_indices_Corporales
 Body Index Calculator

This project was developed using the Spyder (Anaconda) environment and contains several Python scripts that calculate different health-related indicators such as Body Mass Iandndex (BMI), body fat percentage, resting calories, activity-based calories,  recommended daily calories for weight loss.

 Project Structure

The project is composed of several files:

1. calculadora_indices.py

This is the main module containing all mathematical functions used by the other scripts:

calcular_IMC(peso, altura) – Calculate BMI

calcular_porcentaje_grasa(peso, altura, edad, valor_genero) – Calculate body fat percentage

calcular_calorias_en_reposo(peso, altura, edad, valor_genero) – Calculate calories burned at rest (BMR)

calcular_calorias_en_actividad(peso, altura, edad, valor_genero, valor_actividad) – Calculate calories burned based on activity level

consumo_calorias_recomendado_para_adelgazar(peso, altura, edad, valor_genero) – Recommended caloric intake for weight loss

2. consola_calculo_imc.py

Calculates BMI by requesting:

Weight (kg)

Height (m)

3. consola_calculo_porcentaje_grasa.py

Calculates body fat percentage using:

Weight (kg)

Height (m)

Age

Gender (H/M)

4. consola_calculo_calorias_reposo.py

Calculates Basal Metabolic Rate (BMR) using:

Weight (kg)

Height (cm)

Age

Gender (H/M)

5. consola_calculo_calorias_actividad.py

Calculates daily caloric expenditure based on activity level:

Weight (kg)

Height (cm)

Age

Gender (H/M)

Activity level (1.2, 1.55, 1.9, etc.)

6. consola_calculo_calorias_adelgazar.py

Provides a recommended daily caloric range for weight loss based on BMR.

How to Run the Project

Make sure Python 3 is installed.

Place all .py files in the same folder.

Run any script from the console or directly in Spyder:

python consola_calculo_imc.py


Or any of the others

python consola_calculo_porcentaje_grasa.py
python consola_calculo_calorias_reposo.py
python consola_calculo_calorias_actividad.py
python consola_calculo_calorias_adelgazar.py

Requirements

This project does not require external libraries.
It only requires:

Python 3.x

All files in the same directory so the calculadora_indices import works properly

Project Objective

To provide simple console-based tools for calculating basic health indicators, using well-organized and independent scripts, developed within the Spyder environment.