---
theme: jekyll-theme-leap-day
title: Peijie Xu
description: Project Detail
---
[Home](../index.html) / [Project List](Projects_index.html) / Multi-Agent DRL
  
## Deep Reinforcement Learning (DRL) - Guided Offshore Wind Farm Voltage Control

_Undergraduate Thesis Project_   
_Supervisor: Prof. Hui Li_  
_Lab: [State Key Laboratory of PES](http://sklpe.cqu.edu.cn/)_

* Applied DRL to minimize the Average Voltage Deviation (AVD) of the offshore wind farm; the work was awarded the outstanding undergraduate thesis of CQU (top 1.5% in the university)

*	Built reactive power-voltage optimization model and formulated it as a Markov Decision Process; established the agents’ actor & critic’s Deep Neural Network and the interactive environment of RL; trained the agents with adapted Deep Deterministic Policy Gradient (DDPG) and Multi-Agent DDPG
   
*	Decreased AVD by 11.48 % after adding the forward difference of active power into observation; decreased AVD to 5.4×10<sup>-4</sup> p.u. and 3.6×10<sup>-4</sup> p.u. using policy trained by DDPG-based and Multi-Agent DDPG-based method respectively, which means the proposed multi-agent-based method improves the control performance by 33.33 %  

* <a href="doc/Brief Intro to Undergraduate Thesis.pdf" target="Peijie Xu" ><font size=4> <b>A Brief Introduction to My Thesis</b> (pdf)</font></a>
* <a href="https://aistudio.baidu.com/aistudio/projectdetail/1811882?lang=en" target="Peijie Xu" ><font size=4> <b>DDPG source code</b> </font></a>
* <a href="https://aistudio.baidu.com/aistudio/projectdetail/1907893?lang=en" target="Peijie Xu" ><font size=4> <b>MADDPG source code</b></font></a>
  
<table><tr>
<td><img src="pic/1_2.png" height="500"  border=0 /></td>
<td><img src="pic/1_3.png" height="500"  border=0 /></td>
</tr></table> 
<p align="center"><i>The structure of the wind farm</i></p><p></p>

<center class="half">
    <img src="pic/1_1.png" height="500"/>
</center>
<p align="center"><i>The multi-agent DDPG-based approach</i></p><p></p>
  
<center class="half">
    <img src="pic/1_4.png" height="500"/><img src="pic/1_5.png" height="400"/>
</center>
<p align="center"><i>Result</i></p><p></p>

<center class="half">
    <img src="pic/1_6.png" height="250"/>
</center>
<p align="center"><i>Comparation of proposed multi-agent approch and normal DDPG</i></p>

  
