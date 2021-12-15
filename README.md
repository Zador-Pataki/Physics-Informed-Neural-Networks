# Physics-Informed-Neural-Networks 
- [Bachelor Thesis PDF](https://github.com/Zador-Pataki/Physics-Informed-Neural-Networks/files/7711682/Physics_Informed_NN.pdf)
- [Presentation PDF](https://github.com/Zador-Pataki/Physics-Informed-Neural-Networks/files/7719785/thesis_presentation.pdf)

Bachelor Thesis on Physics Informed Neural Networks for Identification and Forecasting of Chaotic Dynamics. We investigate the ability of physics informed neural networks
— data-driven neural networks which incorporate laws of physics generally in the form of partial differential equations (PDEs) — to infer the solutions of and to identify a number of nonlinear partial differential equations. A relatively simple physics informed neural network framework was created that can be easily adjusted and applied to solve any of the mentioned problems concerning different partial differential equations. 

## Code
Each of the jupyter notebooks is an end to end application of one of our approaches for different PDEs.
### Burger's Equation
Being a 2nd order PDE, the Burger's equation was a perferct benchmark example for our appraoches
<details><summary>Burgers_Continuous_Inference.ipynb</summary>
Given PDE parameters and low amounts of boundary and initial data, this framework infers the spatio-temporal behaviour of the Burger's equaiton in cotious time. </details>

<details><summary>Burgers_Discrete_Inference.ipynb</summary>
Given PDE parameters and low amounts of boundary and initial data , this framework infers the spatio-temporal behaviour of the Burger's equaiton in discrete time.
</details>
<details><summary>Burgers_Continuous_Identification.ipynb</summary>
Given spatio-temporal data, this framework infers the PDE parameters of the Burger's equaiton in continuous time.
</details>
<details><summary>Burgers_Discrete_Identification.ipynb</summary>
Given spatio-temporal data, this framework infers the PDE parameters of the Burger's equaiton in discrete time.</details>
  
### Nonlinear Schrödinger equation
The Nonlinear Schrödinger equation, a popular equation in theoretical physics, presented us with a new challange: its complex output required our approach to infer a 2D output as opposed to the example in the Burger's equation which was only 1D.
<details><summary>Schrodinger_Continuous.ipynb</summary>
Given PDE parameters and low amounts of boundary and initial data, this framework infers the spatio-temporal behaviour of the Nonlinear Schrödinger equaiton in cotious time. </details>

### Kuramoto-Sivashinsky Equation
The Kuramoto-Sivashinsky equation is a 4th order PDE used to model instabilities in a laminar flame front. Modelling the Kuramoto-Sivashinsky equation is a difficult task due to its chaotic nature.
<details><summary>Kuramoto_Sivashinsky_Continuous_Time_Identification.ipynb</summary>
Given spatio-temporal data, this framework infers the PDE parameters of the Kuramoto-Sivashinsky equaiton in continuous time.
</details>
<details><summary>Kuramoto_sivashinsky_discrete_identification.ipynb</summary>
Given spatio-temporal data, this framework infers the PDE parameters of the Kuramoto-Sivashinsky equaiton in discrete time.
</details>
