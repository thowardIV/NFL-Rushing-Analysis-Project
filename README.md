# NFL-Rushing-Analysis-Project

## Project Overview
In this project, I analyzed NFL rushing data from 2016-2022 using Python. The key libraries I used were seaborn, statsmodels, and matplotlib. I used multiple regression to see what factors affected rushing yards.

## Dataset
The dataset used for this analysis was retrieved using Python's nfl_data_py library.

## Key Findings
Field position ('yardline_100') greatly impacts average rushing output.
Rushing yards decrease when inside the red zone as there is limited distance to the redzone and the defensive depth compresses.

## Top RYOE Single Season Performances

| Season | Rusher | Rushes ($n$) | Total RYOE | RYOE / Carry | YPC |
| :---: | :--- | :---: | :---: | :---: | :---: |
| **2021** | **J. Taylor** | 332 | **+471.37** | +1.42 | 5.45 |
| **2020** | **D. Henry** | 395 | **+346.03** | +0.88 | 5.23 |
| **2019** | **L. Jackson** | 126 | **+328.58** | +2.61 | 6.88 |
| **2019** | **D. Henry** | 386 | **+311.73** | +0.81 | 5.15 |
| **2020** | **A. Jones** | 221 | **+301.83** | +1.37 | 5.57 |

<br>

<p align="center">
  <img src="output_12_0.png" alt="Rushing Yards vs Ball Position Binned" width="85%"/>
  <br>
  <i>Figure 1: Average Rushing Yards by Ball Position showing boundary constraints near the endzone.</i>
</p>

## Feature Analysis

<table>
  <tr>
    <td width="50%">
      <img src="output_6_0.png" alt="Rushing Yards by Down" width="100%"/>
      <p align="center"><b>Distribution by Down</b></p>
    </td>
    <td width="50%">
      <img src="output_7_0.png" alt="Rushing Yards with 10 Yds to Go" width="100%"/>
      <p align="center"><b>Downs with 10 Yards to Go</b></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="output_13_0.png" alt="Rushing Yards by Location" width="100%"/>
      <p align="center"><b>Run Location Breakdown</b></p>
    </td>
    <td width="50%">
      <img src="output_17_0.png" alt="Rushing Yards by Score Differential" width="100%"/>
      <p align="center"><b>Score Differential Impact</b></p>
    </td>
  </tr>
</table>


