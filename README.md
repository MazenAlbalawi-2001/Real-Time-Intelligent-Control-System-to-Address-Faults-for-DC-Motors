# **Abstract**

This project focuses on enhancing the modeling of Permanent Magnet DC (PMDC) motors
through the application of advanced machine learning techniques. The primary objective is to
develop accurate predictive models for key motor parameters, which are essential for efficient
motor control and performance optimization.
Initially, we developed models to predict motor velocity based on voltage inputs. This involved
training machine learning algorithms on a dataset comprising various voltage inputs and their
corresponding motor velocities. Additionally, we created models to estimate rotor angular
velocity from pulse width modulation (PWM) signals. These models were trained using data that
mapped PWM signals to the resulting angular velocities of the rotor.
The predictive models for motor velocity and rotor angular velocity were then integrated to
estimate rotor temperature. Rotor temperature is a critical parameter that significantly affects
motor efficiency and longevity, yet it is challenging to measure directly due to the nonlinear
behavior of PMDC motors. By combining the outputs of the velocity and angular velocity
models, we developed a comprehensive approach to estimate rotor temperature accurately.
Our approach aims to improve motor control and efficiency in practical applications by
providing more accurate predictions of these key parameters. This enhanced modeling can lead
to better performance, reduced energy consumption, and extended lifespan of PMDC motors.
Future work will focus on applying these models to actively control rotor temperature, further
improving motor performance and longevity. This project demonstrates the potential of machine
learning to overcome the limitations of traditional methods, offering significant advancements in
the field of motor control and efficiency.

# **Challenges**

Accurately predicting key parameters of Permanent Magnet DC (PMDC) motors, such as motor
velocity, rotor angular velocity, and rotor temperature, presents significant challenges due to the
inherent nonlinear behavior of these systems. PMDC motors exhibit complex dynamics that are
influenced by various factors, including electrical inputs, mechanical properties, and thermal
effects. Traditional modeling methods, which often rely on linear approximations or simplified
assumptions, struggle to capture these intricate relationships, leading to suboptimal predictions
and control strategies.
One of the most critical parameters to estimate is rotor temperature. Rotor temperature directly
impacts motor efficiency, performance, and longevity. High temperatures can lead to increased
resistance, reduced magnetic properties, and potential damage to motor components. However,
measuring rotor temperature directly is difficult due to the rotating nature of the rotor and the
harsh operating environment. Traditional methods, such as using thermocouples or infrared
sensors, are either impractical or provide limited accuracy.
To illustrate these challenges, Figure 1 shows the nonlinear relationship between velocity and
pulse-width modulation (PWM), highlighting the limitations of traditional linear models. Figure
2 depicts the relationship between velocity and motor voltage, emphasizing the need for
advanced modeling techniques to capture the initial steep increase and subsequent plateau in
motor voltage as velocity increases. Figure 3 demonstrates the nonlinear behavior of motor
speed and temperature, showing that temperature remains relatively stable at lower speeds but
increases sharply at higher speeds, indicating the complexity of predicting temperature based on
velocity.
This project addresses these challenges by leveraging machine learning techniques to develop
predictive models that can accurately estimate motor velocity, rotor angular velocity, and rotor
temperature. By training machine learning algorithms on extensive datasets that capture the
complex interactions within PMDC motors, we aim to create models that can generalize well to
6
various operating conditions. These models are designed to improve the accuracy of parameter
predictions, thereby enhancing motor control and performance in practical applications.
The integration of machine learning models allows for a more comprehensive understanding of
the motor’s behavior, enabling better control strategies that can adapt to changing conditions.
This approach not only improves the immediate performance of the motor but also contributes to
its long-term reliability and efficiency. By addressing the limitations of traditional methods, our
project aims to provide a robust solution for the accurate prediction and control of key
parameters in PMDC motors, ultimately leading to more efficient and reliable motor systems.

<br><br>
<img width="586" alt="‏لقطة الشاشة ١٤٤٦-٠٢-١٨ في ٤ ٥٢ ٠٣ م" src="https://github.com/user-attachments/assets/6d3e3a86-73a4-48fb-883b-e339615a45e5">
<br><be>
<br><br>
<img width="757" alt="‏لقطة الشاشة ١٤٤٦-٠٢-١٨ في ٤ ٥٢ ٤٠ م" src="https://github.com/user-attachments/assets/185db65f-3dbc-4ff7-90fb-ef5457409f66">
<br><be>
<br><br>
<img width="771" alt="‏لقطة الشاشة ١٤٤٦-٠٢-١٨ في ٤ ٥٣ ١٥ م" src="https://github.com/user-attachments/assets/739a4aa0-d6e1-4c9d-bdf3-36eebd54895a">
<br><br>
<br><br>



# **Methodology**


<img width="586" alt="Methdolagy with RL" src="https://github.com/user-attachments/assets/9e8e75eb-fa79-4ed1-8bd9-647a3dabab51">


# **Future work**

By addressing the challenges in accurately modeling Permanent
Magnet DC (PMDC) motors, this project demonstrates the
potential of machine learning to enhance motor performance
significantly. We have achieved outstanding results, showcasing
substantial improvements in motor control, efficiency, and
reliability, paving the way for more effective use of PMDC
motors in various practical applications. Future work will focus
on developing a real-time controller for temperature, further
enhancing the motor’s performance and longevity.






