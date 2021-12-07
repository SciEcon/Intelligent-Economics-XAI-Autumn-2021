# Econ 211: Python Packages for Economics
### Introduction
In this project, we introduce five Python Packages for Economics: Nashpy, QuantEcon, Game Theory Explorer, Gambit and Mesa. All the five packages are useful for modelling and simulations. 

Both Nashpy and QuantEcon are able to solve simple game theory problems. To be specific, Nashpy is a Python library used for the computation of equilibria in 2 player strategic form games while QuantEcon offers additional computational tools for economics, econometrics, and decision making. Game Theory Explorer (GTE) and Gambit are used for simulating and solving extensive games. GTE is an online graphical user interface for small and medium size games while Gambit provides more complete functions. Mesa is a Python framework for agent-based modeling.

We provide files demonstrating the usage of three of the packages, click the link below to see details. A case study of using these five packages is also provided.

### NashPy
[Official Github repo](https://github.com/drvinceknight/Nashpy)

[Official Tutorial](https://nashpy.readthedocs.io/en/stable/)

[Example we provide](https://github.com/SciEcon/Intelligent-Economics/blob/main/project1/Colab%20Notebook%20NashPy%20vs%20QuantEcon.ipynb)
### QuantEcon
[Official Website](https://quantecon.org/)

[Official Tutorial (Python)](https://quantecon.org/quantecon-py/)

[Example we provide](https://github.com/SciEcon/Intelligent-Economics/blob/main/project1/Colab%20Notebook%20NashPy%20vs%20QuantEcon.ipynb)
### Game Theory Explorer
[Official Website](http://www.gametheoryexplorer.org/)

[Official Tutorial](http://www.maths.lse.ac.uk/Personal/stengel/TEXTE/largeongte.pdf)
### Gambit
[Official Website](http://www.gambit-project.org/)

[Official Tutorial (The graphical interface)](http://www.gambit-project.org/gambit15/gui.html)
### Mesa
[Official Github repo](https://github.com/projectmesa/mesa)

[Official Tutorial](https://mesa.readthedocs.io/en/latest/tutorials/intro_tutorial.html)

[Example we provide](https://github.com/SciEcon/Intelligent-Economics/blob/main/project1/Colab%20Notebook%20Mesa.ipynb)

### Case Studies
In this section, we provide a case study for each software mentioned in the first four sections by presenting sample code assignments that utilize the four software packages for solving game theory problems. The assignments consist of three parts: Part I: Normal Form Game;  Part II: Extensive Form Game; Part II: Evolutionary Game. We provide sample questions and answers in two separate colab notebooks （[Colab Notebook Case Study Questions](https://github.com/SciEcon/Intelligent-Economics/blob/main/project1/Colab%20Notebook%20Case%20Study%20Questions.ipynb),[Colab Notebook Case Study Answer](https://github.com/SciEcon/Intelligent-Economics/blob/main/project1/Colab%20Notebook%20Case%20Study%20Answer.ipynb)).
#### Normal Form Game [Part I]
In this part, we provide problem sets for solving two normal form games, one classical game [Battle of sexes](https://drive.google.com/file/d/1hrB5j_zaUfZbsT-ZQk4tzsZqQYkCYa-f/view) (Noam Nisan et. al, 2007, p.7 ), one related to Blockchain application [The miners’ dilemma](https://drive.google.com/file/d/1sB3yaIghyrGv2rPZ7FhSvfO1-prBKCrJ/view) (Ittay, 2015). Students are asked to use NashPy and QuantEcon to get pure equilibrium strategies and mixed equilibrium strategies. 
#### Extensive Form Game [Part II]
In this part, we provide problem sets for solving two extensive form games, one classical [Game of moving](https://drive.google.com/file/d/1hrB5j_zaUfZbsT-ZQk4tzsZqQYkCYa-f/view) (Noam Nisan et. al, 2007, pp. 67-68), one related to the Blockchain [Finite Blockchain game](https://drive.google.com/file/d/11d_DHOEsilm4YC2L5RKg_kaU8vLVV8S1/view) (Ewerhart et al. 2020). Students are asked to use Game Theory Explorer (GTE) to solve the extensive form game with perfect information and Gambit to solve the extensive form game with imperfect Information.
#### Evolutionary Game [Part III]
In this part, we provide problem sets for solving two evolutionary games, one classical [The evolutionary equilibrium of block withholding attack](https://drive.google.com/file/d/1SxFJUtAPWuUHEsQUixkbQTT9lKhzDtNn/view), (Cheng et. al, 2021) and the other related to block chain [Mining Pool Selection](https://drive.google.com/file/d/1W3m9p5OyB3IcHPxIKVFpRkk9Co6Yrztd/view) (Liu et. al, 2018). Students are asked to use Mesa to do agent-based modelling to simulate these two evolutionary games.
