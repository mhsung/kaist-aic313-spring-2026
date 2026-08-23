---
hide:
  - navigation
---

# AIC313/CS378: Introduction to Generative Models

<h3><b>
<a href="http://mhsung.github.io/" target="_blank">Minhyuk Sung</a>, <a href="https://www.kaist.ac.kr/" target="_blank">KAIST</a>, Fall 2026
</b></h3>
<br />

![Teaser](assets/teaser.png){ width=97.5% }[^1]

[^1]: AI-generated using GPT<br>


## Time & Location
**Time**: Mon/Wed 10:30 a.m. - 11:45 a.m. (KST)   
**Location**: E3-5 Room 210

<!-- [Zoom Link](https://kaist.zoom.us/j/83695846631){:target="_blank" .md-button} -->


## Description
Generative models aim to learn complex data distributions and generate new samples, providing the foundation for a wide range of applications in computer vision, computer graphics, natural language processing, and scientific discovery. With the rapid development of deep learning, diverse generative modeling approaches have emerged, each offering distinct perspectives on learning and sampling from data distributions. In this course, we will cover the fundamental principles and recent advances in generative models, including autoregressive models, variational autoencoders, generative adversarial networks, normalizing flows, diffusion and score-based models, and flow matching. We will also discuss conditional generation, inference-time guidance, practical applications, and remaining challenges in the field.


## Prerequisites
- Solid background in machine learning and deep learning
- Hands-on experience with neural network implementation
- Recommended prior courses:
    - MAS.20050 Probability and Statistics
    - MAS.20001 Differential Equations and Applications
    - CS.30701 Introduction to Deep Learning


## Course Staff
**Instructor**: [Minhyuk Sung](https://mhsung.github.io/){:target="_blank"} ([mhsung@kaist.ac.kr](mailto:mhsung@kaist.ac.kr))

**Course Assistants:**

- Mingue Park ([kicikicik@kaist.ac.kr](mailto:kicikicik@kaist.ac.kr))
- Yunhong Min ([dbsghd363@kaist.ac.kr](mailto:dbsghd363@kaist.ac.kr))
- Prin Phunyaphibarn ([prin10517@kaist.ac.kr](mailto:prin10517@kaist.ac.kr))
- Yunjae Jeong ([frogjj@kaist.ac.kr](mailto:frogjj@kaist.ac.kr))



## Textbook
The main reference for this course is:

**Kevin P. Murphy, _Probabilistic Machine Learning: Advanced Topics_, MIT Press.**  
[**[Download Link]**](https://probml.github.io/pml-book/book2.html){:target="_blank"}

We will mainly use selected material from **Part I: Fundamentals** and **Part IV: Generation**, supplemented with recent papers and lecture notes where appropriate.


## Related Courses Offered in Previous Years
- [CS492(D): Diffusion Models and Their Applications](https://diffusion.kaist.ac.kr/){:target="_blank"}
- [CS492(D): Diffusion Models and Their Applications](https://mhsung.github.io/kaist-cs492d-fall-2024/){:target="_blank"}


## Grading
- Participation & Quizzes: 15%
- Exams: 45%
- FastGen Challenge: 20%
- CreativeGen Challenge: 20%


<!--
## Paper List
[Paper List](https://docs.google.com/spreadsheets/d/1j7amDru9bRQsQgp2pfm1a8GrZ6K0HWwCDORGq-sj7dQ/edit?usp=sharing){:target="_blank" .md-button}


## Useful Resources
- [Fall 2024 Course Webpage](https://mhsung.github.io/kaist-cs492d-fall-2024/){:target="_blank"}
- [SIGGRAPH 2025 Course: Diffusion Models for Image and Video Generation: From Foundations to Emerging Directions](https://geometry.cs.ucl.ac.uk/courses/diffusion_ImageVideo_sigg25/){:target="_blank"}
- [SIGGRAPH 2024 Course: Diffusion Models for Visual Content Generation](https://geometry.cs.ucl.ac.uk/courses/diffusion4ContentCreation_sigg24/){:target="_blank"}
- [CVPR 2023 Tutorial: Denoising Diffusion Models: A Generative Learning Big Bang](https://cvpr2023-tutorial-diffusion-models.github.io/){:target="_blank"}
- ["Generative Modeling by Estimating Gradients of the Data Distribution", Yang Song.](https://yang-song.net/blog/2021/score/){:target="_blank"}
- ["What are Diffusion Models?", Lilian Weng.](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/){:target="_blank"}
- ["Understanding Diffusion Models: A Unified Perspective". Calvin Luo.](https://arxiv.org/abs/2208.11970){:target="_blank"}
- ["Tutorial on Diffusion Models for Imaging and Vision". Stanley H. Chan.](https://arxiv.org/abs/2403.18103){:target="_blank"}
- ["Step-by-Step Diffusion: An Elementary Tutorial". Preetum Nakkiran, Arwen Bradley, Hattie Zhou, and Madhu Advani.](https://arxiv.org/abs/2406.08929){:target="_blank"}
-->


## Important Dates
ALL ASSIGNMENTS ARE DUE 23:59 KST.  

(Subject to Change)  

- Project Team Sign-Up: ==Due Sep 28 (Mon)==  
- FastGen Challenge Submission: ==Due Nov 14 (Sat)== 
- CreativeGen Challenge Submission: ==Due Dec 06 (Sat)== 


## Schedule
(Subject to Change) 

<table>
  <thead>
    <tr>
      <th>Week</th>
      <th>Date</th>
      <th>Topic</th>
      <th>Related Sections</th>
      <th>Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2" align="center">1</td>
      <td>Aug 31</td>
      <td><strong>Course Introduction</strong></td>
      <td>Ch. 20.1–20.4</td>
      <td></td>
    </tr>
    <tr>
      <td>Sep 02</td>
      <td><strong>Probability Background</strong></td>
      <td>
        Ch. 2.1.2–2.1.3, 2.1.5–2.1.6;<br>
        Ch. 2.2.1.2, 2.2.2.1; Ch. 2.3.1.1;<br>
        Ch. 3.2.1.1
      </td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">2</td>
      <td>Sep 07</td>
      <td><strong>Autoregressive Models</strong></td>
      <td>Ch. 22.1–22.4</td>
      <td></td>
    </tr>
    <tr>
      <td>Sep 09</td>
      <td><strong>Variational Autoencoders 1</strong></td>
      <td>Ch. 21.1–21.2.2</td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">3</td>
      <td>Sep 14</td>
      <td><strong>Variational Autoencoders 2</strong></td>
      <td>Ch. 21.2.3–21.2.4</td>
      <td></td>
    </tr>
    <tr>
      <td>Sep 16</td>
      <td><strong>Normalizing Flows 1</strong></td>
      <td>Ch. 23.1–23.2.3</td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">4</td>
      <td>Sep 21</td>
      <td><mark><strong>FastGen / KCloud Session</strong></mark></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sep 23</td>
      <td>No Class (Break)</td>
      <td>—</td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">5</td>
      <td>Sep 28</td>
      <td><strong>Normalizing Flows 2</strong></td>
      <td>Ch. 23.2.4 and 23.3</td>
      <td></td>
    </tr>
    <tr>
      <td>Sep 30</td>
      <td><strong>Generative Adversarial Networks</strong></td>
      <td>Ch. 26.1–26.3.3</td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">6</td>
      <td>Oct 05</td>
      <td>No Class (Substitute Holiday for National Foundation Day)</td>
      <td>—</td>
      <td></td>
    </tr>
    <tr>
      <td>Oct 07</td>
      <td><strong>Energy-Based Models 1</strong></td>
      <td>Ch. 24.1–24.2</td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">7</td>
      <td>Oct 12</td>
      <td><strong>Energy-Based Models 2</strong></td>
      <td>Ch. 24.3–24.4</td>
      <td></td>
    </tr>
    <tr>
      <td>Oct 14</td>
      <td><strong>Midterm Wrap-Up</strong></td>
      <td>
      </td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">8</td>
      <td>Oct 19</td>
      <td>No Class (Midterm Week)</td>
      <td>—</td>
      <td></td>
    </tr>
    <tr>
      <td>Oct 21</td>
      <td>No Class (Midterm Week)</td>
      <td>—</td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">9</td>
      <td>Oct 26</td>
      <td><strong>Diffusion Models 1</strong></td>
      <td>Ch. 25.1–25.2.2</td>
      <td></td>
    </tr>
    <tr>
      <td>Oct 28</td>
      <td><strong>Diffusion Models 2</strong></td>
      <td>Ch. 25.2.3–25.3.3</td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">10</td>
      <td>Nov 02</td>
      <td><strong>Diffusion Models 3</strong></td>
      <td>Ch. 25.4–25.5.3</td>
      <td></td>
    </tr>
    <tr>
      <td>Nov 04</td>
      <td><strong>Conditional Generation / Latent Diffusion</strong></td>
      <td>Ch. 25.5.4 and 25.6</td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">11</td>
      <td>Nov 09</td>
      <td><strong>Flow Matching 1</strong></td>
      <td>
        Ch. 23.2.6 and 25.4</td>
      <td></td>
    </tr>
    <tr>
      <td>Nov 11</td>
      <td><mark><strong>FastGen Recap / CreativeGen</strong></mark></td>
      <td>
      </td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">12</td>
      <td>Nov 16</td>
      <td><strong>Flow Matching 2</strong></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nov 18</td>
      <td><strong>Inference-Time Guidance</strong></td>
      <td>
      </td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">13</td>
      <td>Nov 23</td>
      <td><strong>Discrete Diffusion</strong></td>
      <td>
      </td>
      <td></td>
    </tr>
    <tr>
      <td>Nov 25</td>
      <td><strong>Course Wrap-Up</strong></td>
      <td>
      </td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">14</td>
      <td>Nov 30</td>
      <td><strong>Guest Lecture 1</strong></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dec 02</td>
      <td><strong>Guest Lecture 2</strong></td>
      <td></td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">15</td>
      <td>Dec 07</td>
      <td><mark><strong>Project Presentations 1</strong></mark></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dec 09</td>
      <td><mark><strong>Project Presentations 2</strong></mark></td>
      <td></td>
      <td></td>
    </tr>

    <tr>
      <td rowspan="2" align="center">16</td>
      <td>Dec 14</td>
      <td>No Class (Final Week)</td>
      <td>—</td>
      <td></td>
    </tr>
    <tr>
      <td>Dec 16</td>
      <td>No Class (Final Week)</td>
      <td>—</td>
      <td></td>
    </tr>
  </tbody>
</table>


## AI Coding Assistant Tool Policy
**You are allowed (and even encouraged) to utilize AI coding assistant tools**, such as ChatGPT, Copilot, Codex, and Code Intelligence, for your programming assignments and projects. Utilizing AI coding assistant tools will not be deemed as plagiarism. However, it is still **strictly prohibited to directly copy code from the Internet or from someone else**. Doing so will lead to a score of zero and a report to the university.

<br />
