# **Report 6: Week of 10/04/2023**

## An new idea

This week, we were informed that we needed to split the previous six-member team into two teams, so I reselected three teammates. After further assessment, we re-evaluated the workload of the cleaning robot, so we decided to make some adjustments to our direction.

This time, we narrowed our focus to rescue in free diving. Because free diving is one of the most dangerous sports in the world. The leading cause of accidents in free diving is blackout, where divers lose consciousness under pressure. Therefore, we believe this is a very innovative field, and we have shifted our attention to this topic.
![Untitled](https://github.com/Berkeley-MDes/tdf-fa23-WeilongGao/assets/48149933/f04cd7be-7550-46dd-827a-be1b4a8dbcf9)


## How to detect?

After extensive research, we found that to detect such blackouts, we can mainly rely on two methods: one is heart rate and the other is blood oxygen level. Therefore, we purchased sensors related to these two aspects and are preparing to conduct tests.

![Untitled 1](https://github.com/Berkeley-MDes/tdf-fa23-WeilongGao/assets/48149933/b5696775-e303-4dbc-8f6d-7da1bc965d6b)


![Untitled 2](https://github.com/Berkeley-MDes/tdf-fa23-WeilongGao/assets/48149933/2fc5aecb-2d22-4ff6-9c0f-19a5adb83e20)



# **Report 5: Week of 09/27/2023**

## IDEATION

I chose the Clean Tech topic, and I have some preliminary ideas about it. I hope to design a desk-top equivalent of a robotic vacuum cleaner. In this way, this small robot can automatically clean the table surface.

## How to use IoT?

In my vision, the home is an excellent setting for utilizing WI-FI communication, which aligns perfectly with IoT. Therefore, I believe this robot can be divided into two parts: one is the robotic part that sweeps, and the other is the camera part responsible for detection. After the camera part detects, it sends the data to the mobile robot. This forms the entire clean tech system.

![IMG_2642](https://github.com/Berkeley-MDes/tdf-fa23-WeilongGao/assets/48149933/d30be9a8-6d39-44bc-897a-d827dcf73e08)

# Report 4: Week of 09/21/2023

I previously only had experience with Arduino, but the photon I need to use this time is an IoT device. Therefore, I need to start from scratch to learn how to use the Photon in a WIFI environment and let them communicate with each other.

## Connection Photon to WIFI

I first registered my own account on Particle.

![Untitled](https://github.com/Berkeley-MDes/tdf-fa23-WeilongGao/assets/48149933/79819614-251c-4ad6-bfb7-667a887b03dc)


I followed the tutorial on GitHub and wrote the corresponding code, and obtained the corresponding MAC address. P.S.: I later asked the teacher why the MAC address is needed. It turns out that Berkley's Wi-Fi needs to protect its own network system, so every connecting device needs to be registered.

![Untitled 1](https://github.com/Berkeley-MDes/tdf-fa23-WeilongGao/assets/48149933/5fe598e4-76af-4754-acbe-84531bc01d4a)

Registering on Berkeley's website.

![Untitled 2](https://github.com/Berkeley-MDes/tdf-fa23-WeilongGao/assets/48149933/716a5b41-b6dc-4b68-816c-dfbf2188bf20)


Successfully connected to WI-FI and conducted simple communication.

![Untitled 3](https://github.com/Berkeley-MDes/tdf-fa23-WeilongGao/assets/48149933/a53d7a4d-b985-4240-9dff-ba6db720f850)


# Report 3: Week of 09/13/2023

## Use Scenario

The most common scenario in which I use a phone stand is when I want to watch videos while eating. In the past, I had to hold the phone in my hand, which was really inconvenient. So I decided to design a phone stand for this purpose.

![IMG_0629.PNG](images/week3_1.png)

I have several requirements for this phone stand. First, it should match the height at which I sit, based on ergonomic design. 

**Second, I want it to not look like a typical phone stand, so I can place it on the table as a decoration.**

## Measurement

So, I measured the dimensions of the table, chair, and my sitting height. 

![IMG_0631.PNG](images/week3_2.png)

I first mocked up a basic scene in Blender to adjust the size and angle of the phone stand. This way, I ensured it met ergonomic standards. 

![Group 52.png](images/week3_3.png)

![Untitled](images/week3_4.png)

## Design in Grasshopper

Then I used Grasshopper and Rhino to design my phone stand. I created an array containing a 3x3 matrix and placed a cube at each coordinate of the matrix.

![Untitled](images/week3_5.png)

 I then modified some cubes in the matrix, reducing the distances between them, to give it a more compelling geometric design.

![Untitled](images/week3_6.png)

![Untitled](images/week3_7.png)

![Untitled](images/week3_8.png)

Now, it works perfectly and I find it incredibly useful for watching videos while I eat.

![IMG_0627.HEIC](images/week3_9.jpg)

![IMG_0637.HEIC](images/week3_10.jpg)
# Report 2: Week of 09/06/2023

## Use grasshopper to design my personal phone stand

### Scenario and Pain points

For me, the most frequent occasion to use a phone stand is when I'm having meals and need to watch videos. However, the current phone stand doesn't meet all of my needs, such as the viewing angle and obstructions in front of the screen. Therefore, I have summarized 4 points that need improvement.

1. No obstructions.
2. Titled more to fit the viewing angle.
3. The center of gravity should be more stable.
4. Easier to put the phone on 

![123123.png](images/week2-01.png)

### Phone stand design

Based on the improvement points, I design the new phone stand which is not that fancy but meet my demands.

![12421414.png](images/week2-02.png)

### Model with grasshopper

I have never used visual coding tools like Grasshopper before, so it took me a while to figure out what the panels meant. However, I soon discovered that it is not that different from programming in Unity. All I needed to do was find the parameter and figure out which part of the model it controls, and then I could adjust the model as desired.

First, I adjust the prism parameter to cut off the top of the stand, which is blocking my view. Then, I change the base width to make the center of gravity more stable. 

![image 16.png](images/week2-03.png)

![image 15.png](images/week2-04.png)

With this step, the phone stand looks like this.

![image 14.png](images/week2-05.png)

The next step is to adjust the viewing angle to make it more ergonomic for me.

![image 12.png](images/week2-06.png)

The final product is like this. I think it's pretty good - simple but solves all my problems.

![image 11.png](images/week2-07.png)

![image 10.png](images/week2-08.png)

### Summarize

My first experience with visual programming tools was pretty good. I didn't need much time to adapt to this different way of programming. It's more intuitive than writing code directly. However, I believe that when the project becomes bigger and more complex, it can be challenging to manage the entire project.

It would be quite interesting to consider how to improve visual programming tools, or whether they are only suitable for small projects. I will search for more information on this topic.

## Reflection

I believe that parametric design is a useful means to explore different possibilities in personality design. However, even with this method, it is still difficult to meet everyone's demands in the way we imagine true personality design. In my opinion, the only way to implement true personality design and provide everyone with the most appropriate product is to combine it with AI. Users really need to simply click a button and receive their ideal product. I am eager to explore this realm further.

# Report 1: Week of 08/29/2023

## First attempt to create a physical prototype.

Due to my background, my previous work primarily focused on the software side, so I have little experience creating physical prototypes. To be honest, I used to avoid this aspect of work because I felt that physical prototypes were limited by the available facilities, whereas software offered more freedom to realize my ideas. However, now that Jacobs Hall has such advanced facilities, it's the perfect time to learn how to create a physical prototype.

### Reflection

Of course, the process wasn't entirely smooth. I made several mistakes while using the laser cutter. The most significant oversight was forgetting to adjust the thickness, resulting in parts of the plywood board not being fully cut through. So, it's quite challenging to separate it from the board.

So it’s like this…

![image1](images/WechatIMG162.jpg)

### Final work

While I encountered some challenges, the final product turned out quite well and fits my phone perfectly. My most notable experience was in the laser cutter room. I wasn't very familiar with everything there, but my peers were immensely helpful. They guided me through the process of using the software and editing the AI file. I'm truly grateful for their assistance.

![image2](images/WechatIMG161.jpg)
