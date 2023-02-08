# Determining the energy lost during an inelastic collision

*David Wang, Chris Wang, Sam Ni, Yankee Zhu*  
*P2 AP Physics 1 G9*  
*Teacher: Mr. Kim*  
*Submitted at: Feb 9, 2023*

## Objective
The primary goal of this lab experiment is to develop a method to determine the energy lost during an inelastic collision excluding the loss from friction and confirming the method with measured data. To accomplish this, we have to apply our knowledge of inelastic collision, kinetic energy, and conservation of momentum.

## Materials
 - iPad with [Vernier Graphical Analysis](https:/www.vernier.com/product/graphical-analysis/) app
 - Vernier Go Direct Cart and accompanying metal track
 - Electronic scale

![Go Direct carts](https://raw.githubusercontent.com/david-why/inelastic-collision-lab/main/go-direct-carts.jpeg)  
Image 1. Go Direct Carts

![Metal track for carts](https://raw.githubusercontent.com/david-why/inelastic-collision-lab/main/go-direct-track.jpg)  
Image 2. Metal track for carts

## Setup
The primary setup of our experiment is three Vernier carts on a metal track. One Vernier cart will serve as a "launcher" at the end of the rail (0cm to be specific), which would use its extentable pistol to launch Cart 2 into motion. Cart 2 will be positioned at 32cm point right against the launcher. Cart 1 would be positioned on the 100cm point stationary.

![Lab setup diagram](https://raw.githubusercontent.com/david-why/inelastic-collision-lab/main/lab-setup.JPG)  
Image 3. Lab setup diagram

## Procedure
<!-- TODO: Sam -->
1. Lable the cars as Cart 1, Cart 2, and launcher as explained in setup
2. Measure the mass of Cart 1 and Cart 2
3. Connect the two cars to a device with the Vernier Graphical Analysis app
4. Put all cars on the track at positions as indicated in the setup section
5. Start recording the velocity of the two carts using the app
6. Launch Cart 2 toward Cart 1
7. Record velocity data until after Cart 1 and Cart 2 collide
8. Repeat step 4 to 7 serveral times to reduce uncertainty
<!--
I deleted this part since it's redundant
4. put the lancher on one end of a track
5. put the second car next to the launcher
6. put the first car 100cm away from the second car
-->

## Data
<!-- Raw data/graphs/etc. -->
The mass of Cart 1 is $m_1=291\text{ g}$, and the mass of Cart 2 is $m_2=285\text{ g}$.

The raw data table, as recorded by the Vernier Graphical Analysis app, can be found with [this link](https://github.com/david-why/inelastic-collision-lab/blob/main/csv-export.csv).

## Results
<!-- Modified data used in analysis in tables/graphs/etc. -->
This is the modified data table where the times are synchronized, i.e. all carts start moving at $t=0$. The time interval is $0.2$ seconds in this data table. To view the table with intervals of $0.04$ seconds, visit [here](https://github.com/david-why/inelastic-collision-lab/blob/main/modified-table.md).

|      |   1 (Cart 2) |   2 (Cart 2) |   3 (Cart 2) |   4 (Cart 2) |   5 (Cart 2) |   6 (Cart 2) |   1 (Cart 1) |   2 (Cart 1) |   3 (Cart 1) |   4 (Cart 1) |   5 (Cart 1) |   6 (Cart 1) |
|-----:|-------------:|-------------:|-------------:|-------------:|-------------:|-------------:|-------------:|-------------:|-------------:|-------------:|-------------:|-------------:|
| 0    |    0.0670834 |     0.112657 |   0.18396    |   0.0689213  |   0.0609227  |    0.063646  |   0          |   0          |   0          |  0           |  0.00187043  |   0          |
| 0.2  |    0.849521  |     0.844585 |   0.833013   |   0.845946   |   0.837267   |    0.833354  |   0          |   0          |   0          |  0           | -0.000170039 |   0          |
| 0.4  |    0.836416  |     0.830631 |   0.826206   |   0.839309   |   0.830801   |    0.826886  |   0          |   0          |   0          |  0           |  0           |   0          |
| 0.6  |    0.826377  |     0.820761 |   0.82008    |   0.831481   |   0.821782   |    0.82076   |   0          |   0          |   0          |  0           |  0.000170039 |   0          |
| 0.8  |    0.808338  |     0.797446 |   0.793022   |   0.818038   |   0.811231   |    0.807997  |   0.00935959 |   0.0199108  |   0.0325039  |  0.0120825   |  0.00765953  |   0.00901934 |
| 1    |    0.403318  |     0.39651  |   0.397532   |   0.406893   |   0.405191   |    0.40519   |   0.395489   |   0.395319   |   0.398553   |  0.405021    |  0.399915    |   0.398553   |
| 1.2  |    0.392086  |     0.389705 |   0.394979   |   0.400423   |   0.397362   |    0.39583   |   0.393788   |   0.389875   |   0.396681   |  0.402638    |  0.398213    |   0.397362   |
| 1.4  |    0.386129  |     0.383578 |   0.391235   |   0.39583    |   0.392766   |    0.392087  |   0.386811   |   0.385278   |   0.391915   |  0.397362    |  0.394469    |   0.394298   |
| 1.6  |    0.382216  |     0.378983 |   0.386641   |   0.391405   |   0.389022   |    0.386981  |   0.382897   |   0.379834   |   0.388174   |  0.394128    |  0.391235    |   0.390554   |
| 1.8  |    0.37609   |     0.373537 |   0.384427   |   0.388171   |   0.38579    |    0.383747  |   0.37677    |   0.373708   |   0.383576   |  0.390216    |  0.38647     |   0.385959   |
| 2    |    0.370645  |     0.365879 |   0.378983   |   0.382725   |   0.382046   |    0.378302  |   0.372857   |   0.369282   |   0.379665   |  0.384938    |  0.382727    |   0.380005   |
| 2.2  |    0.364518  |     0.359752 |   0.375239   |   0.37677    |   0.37677    |    0.376091  |   0.366731   |   0.363157   |   0.375751   |  0.377453    |  0.378303    |   0.376769   |
| 2.4  |    0.358391  |     0.353117 |   0.369794   |   0.372856   |   0.372856   |    0.370643  |   0.358901   |   0.355329   |   0.370475   |  0.373539    |  0.373539    |   0.371325   |
| 2.6  |    0.352094  |     0.346309 |   0.362135   |   0.367411   |   0.367409   |    0.366729  |   0.352775   |   0.34699    |   0.363837   |  0.367407    |  0.367582    |   0.366901   |
| 2.8  |    0.345969  |     0.340012 |   0.356859   |   0.359074   |   0.362986   |    0.359753  |   0.345458   |   0.340182   |   0.358561   |  0.361284    |  0.361625    |   0.360944   |
| 3    |    0.339161  |     0.333887 |   0.351583   |   0.352946   |   0.355329   |    0.355157  |   0.33848    |   0.333886   |   0.351924   |  0.354651    |  0.355498    |   0.353967   |
| 3.2  |    0.332353  |     0.326398 |   0.344097   |   0.34682    |   0.349201   |    0.349202  |   0.330994   |   0.325377   |   0.346308   |  0.346481    |  0.34937     |   0.34937    |
| 3.4  |    0.324186  |     0.317889 |   0.339502   |   0.33797    |   0.342565   |    0.343075  |   0.324696   |   0.31908    |   0.340013   |  0.340183    |  0.344776    |   0.344776   |
| 3.6  |    0.313976  |     0.309381 |   0.259519   |   0.262072   |   0.310232   |    0.335417  |   0.317719   |   0.309382   |   0.266666   |  0.275175    |  0.30921     |   0.337631   |
| 3.8  |    0.30853   |     0.300361 |  -0.0935958  |   0.114189   |   0.136141   |    0.240119  |   0.310232   |   0.301213   |  -0.088153   |  0.11827     |  0.138693    |   0.26054    |
| 4    |    0.301042  |     0.289385 |  -0.138012   |  -0.00289215 |   0.0178683  |    0.104319  |   0.302234   |   0.290916   |  -0.138523   |  0.000169211 |  0.0231418   |   0.103126   |

Table 1. Modified data table.

![Data graph](https://raw.githubusercontent.com/david-why/inelastic-collision-lab/main/data-graph.PNG)  
Image 4. Data graph

## Analysis
<!-- Calculations for more useful information etc. -->
By analyzing the data table, the collision happened at $t=0.75\text{ s}$ because this is the time when Cart 1 began to accelerate. The velocity of Cart 2 at this time is averagely $v_0=0.818\text{ m/s}$. At time $t=1.04\text{ s}$, the velocities of Cart 1 and Cart 2 are equal, in the range of experimental uncertainty. At this time, the average velocity of the Cart 1-Cart 2 system across all trials is $v_f=0.398\text{ m/s}$.

Calculating the energies before and after the collision, we have

$$
\begin{align*}
K_i &= \frac12m_2v_0^2 \\
    &= \frac12(285\text{ g})(0.818\text{ m/s})^2 \\
    &= 95.4\text{ J}
\end{align*}
$$

and

$$
\begin{align*}
K_f &= \frac12(m_1+m_2)v_f^2 \\
    &= \frac12(291\text{ g} + 285\text{ g})(0.398\text{ m/s})^2 \\
    &= 45.6\text{ J}.
\end{align*}
$$

Therefore, the energy lost in this elastic collision, not including the work done by friction, is $95.4-45.6=49.8\text{ J}$.

## Discussion
<!-- The reasoning that led to the conclusion -->
<!-- TODO: David/Sam -->
Now, we will derive a general equation for the energy lost in a perfectly inelastic collision, given the two objects' masses and initial velocities.

For simplicity, let the two objects be Object A and Object B. Let the masses of Object A and B be $m_A$ and $m_B$, and the initial velocities of the two objects be $v_A$ and $v_B$, respectively. Let the final velocity of the two objects be $v$. The masses and initial velocities are data collected in any experiment in which the two objects inelastically collide with each other.

Then, by the conservation of momentum, $m_Av_A+m_Bv_B=m_Av+m_Bv$. The quantity we are trying to calculate is $\frac12m_Av_A^2 + \frac12m_Bv_B^2 - \frac12(m_A+m_B)v^2$.

We first derive $v$ from the conservation of momentum formula.

$$
\begin{align*}
m_Av + m_Bv &= m_Av_A + m_Bv_B \\
 (m_A+m_B)v &= m_Av_A + m_Bv_B \\
          v &= \frac{m_Av_A + m_Bv_B}{m_A + m_B}
\end{align*}
$$

Then, we will use the derived $v$ to calculate the loss of energy.

$$
\begin{align*}
\Delta E &= \frac12(m_Av_A^2 + m_Bv_B^2 - (m_A + m_B)v^2) \\
         &= \frac12(m_Av_A^2 + m_Bv_B^2 - (m_A + m_B)(\frac{m_Av_A + m_Bv_B}{m_A + m_B})^2) \\
         &= \frac12(m_Av_A^2 + m_Bv_B^2 - \frac{m_A^2v_A^2 + m_B^2v_B^2 + 2m_Am_Bv_Av_B}{m_A + m_B}) \\
         &= \frac12(\frac{m_A^2v_A^2 + m_Am_Bv_A^2 + m_Am_Bv_B^2 + m_B^2v_B^2}{m_A + m_B} - \frac{m_A^2v_A^2 + m_B^2v_B^2 + 2m_Am_Bv_Av_B}{m_A + m_B}) \\
         &= \frac{m_Am_Bv_A^2 + m_Am_Bv_B^2 - 2m_Am_Bv_Av_B}{2(m_A+m_B)} \\
         &= \frac{m_Am_B(v_A^2 + v_B^2 - 2v_Av_B)}{2(m_A+m_B)} \\
         &= \frac{m_Am_B(v_A - v_B)^2}{2(m_A+m_B)}
\end{align*}
$$

The derived equation above will be our method to determine the energy lost during an inelastic collision. To prove experimentally that this equation is correct, we will test it with the values measured in our experiment. We will let Object A be the initially stationary cart and Object B be the initially moving cart.

$$
\begin{align*}
     m_A &= 291\text{ g} \\
     m_B &= 285\text{ g} \\
     v_A &= 0 \\
     v_B &= 0.818\text{ m/s} \\
\Delta E &= \frac{m_Am_B(v_A - v_B)^2}{2(m_A+m_B)} \\
         &= \frac{(291\text{ g})(285\text{ g})(0 - 0.818\text{ m/s})^2}{2(291\text{ g} + 285\text{ g})} \\
         &= 48.2\text{ J}
\end{align*}
$$

As shown, the calculated value of the energy lost during this inelatic collision, 48.2J, is extremely close with the experimental value measured, 49.8J, with only a minor difference of 1.6J, which is within the acceptable range of experimental uncertainty. This proves that the equation we derived to the determine the energy lost in an inelastic collision, $\frac{m_Am_B(v_A - v_B)^2}{2(m_A+m_B)}$, is valid.

Possible reasons for the difference in the measured energy lost and the calculated energy of 1.6J are listed below.

1. The uncertainty of the sensors that measures the velocity of the car. This uncertainty could be ignored as the sensors are advanced enough such that it's safe to not include them.

2. Friction will also cause some uncertainty as it's not included but it will cause some energy lost. However, this is beyond the scope of this lab since the question states that friction should not be considered.

## Conclusion
<!-- Final remarks, summary -->
In this experiment, we calculated and measured the energy lost in an inelastic collision and compared the experimental and theoretical results. We concluded that the energy lost in an inelastic collision is dependent on the mass and initial velocity of both objects involved. We learned that computer analysis can be extremely beneficial and efficient. During this experiment, we became more proficient with operating physics experiments and gained valuable experience of using equipment, such as Vernier carts, to solve real world problems.
<!-- DONE! -->
