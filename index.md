---
layout: home
---
# Course Description
This course provides an introduction to computer vision, including fundamentals of image formation, camera imaging geometry, 
feature detection and matching, stereo, motion estimation and tracking, image classification, scene understanding, and deep learning with neural networks.

# Piazza Group 

[Join the Piazza Group]https://piazza.com/university_of_tabuk/fall2024/computervision)
Access code: 

<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #f9f9f9;
        margin: 0;
        padding: 20px;
    }
    table {
        width: 100%;
        border-collapse: collapse;
        margin-bottom: 20px;
    }
    th, td {
        padding: 10px;
        text-align: left;
    }
    th {
        background-color: #f2f2f2;
        font-weight: bold;
    }
    .project {
        background-color: #fff2cc; /* Light Yellow */
    }
    .exam {
        background-color: #d9e8fb; /* Light Blue */
    }
    .problem-set {
        background-color: #e2efda; /* Light Green */
    }
    .header {
        background-color: #f2f2f2;
        font-weight: bold;
    }
</style>


<h1>Grading Timeline</h1>

<table>
  <tr class="header">
    <th>Week</th>
    <th>Date</th>
    <th>Event</th>
    <th>Description</th>
    <th>Weight</th>
  </tr>

  <!-- Ordered by Timeline -->
  <tr class="project">
    <td>Week 3</td>
    <td>September 9, 2024</td>
    <td>Project Proposal Submission</td>
    <td>Submit your project proposal, selecting a topic and outlining your plan.</td>
    <td>5%</td>
  </tr>
  <tr class="problem-set">
    <td>Week 7</td>
    <td>October 7, 2024</td>
    <td>Problem Set 1 Due</td>
    <td>Covers topics from Lectures 1-5. Submit your solutions.</td>
    <td>5%</td>
  </tr>
  <tr class="exam">
    <td>Week 8</td>
    <td>October 14, 2024</td>
    <td>Midterm Exam</td>
    <td>An in-class exam covering all material up to Lecture 7.</td>
    <td>20%</td>
  </tr>
  <tr class="problem-set">
    <td>Week 12</td>
    <td>November 11, 2024</td>
    <td>Problem Set 2 Due</td>
    <td>Covers topics from Lectures 6-10. Submit your solutions.</td>
    <td>5%</td>
  </tr>
  <tr class="project">
    <td>Week 15</td>
    <td>December 2, 2024</td>
    <td>Project Interim Report Due</td>
    <td>Submit a detailed progress report and preliminary results.</td>
    <td>10%</td>
  </tr>
  <tr class="project">
    <td>Week 19</td>
    <td>December 30, 2024</td>
    <td>Final Project Submission</td>
    <td>Submit your final project report and presentation.</td>
    <td>25%</td>
  </tr>
  <tr class="exam">
    <td>Final Week</td>
    <td>January 5, 2025</td>
    <td>Final Exam</td>
    <td>Comprehensive exam covering the entire course.</td>
    <td>30%</td>
  </tr>
</table>




<style>
  table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
    font-family: Arial, sans-serif;
  }
  th, td {
    padding: 8px;
    text-align: left;
  }
  th {
    background-color: #f2f2f2;
  }
  tr.intro {
    background-color: #d9e8fb;
  }
  tr.image-processing {
    background-color: #fff2cc;
  }
  tr.feature-detection {
    background-color: #ffe6cc;
  }
  tr.geometric-vision {
    background-color: #e2efda;
  }
  tr.deep-learning {
    background-color: #fbe4d5;
  }
  tr.ethics {
    background-color: #e4dfec;
  }
  tr.holiday {
    background-color: #ffffff;
  }



</style>

# Course Schedule

<table>
  <tr class="header-row">
    <th>Week</th>
    <th>Date</th>
    <th>Type</th>
    <th>Title</th>
    <th>Description</th>
    <th>Readings/Links</th>
  </tr>
  <tr class="intro">
    <td>1</td>
    <td>August 26, 2024</td>
    <td>Lecture</td>
    <td><strong>Introduction and Overview</strong></td>
    <td>Szeliski (2nd Edition) Chapter 1</td>
    <td>Deep dive into foundational concepts</td>
  </tr>
  <tr class="image-processing">
    <td>2</td>
    <td>September 2, 2024</td>
    <td>Lecture</td>
    <td><strong>Image Filtering and Edge Detection</strong></td>
    <td>Image Filtering - Szeliski Chapter 3.1 - 3.3</td>
    <td>Edge Detection - Szeliski Chapter 7.2</td>
  </tr>
  <tr class="image-processing">
    <td>3</td>
    <td>September 9, 2024</td>
    <td>Lecture</td>
    <td><strong>Image Resampling</strong></td>
    <td>Basic Concepts - Szeliski Chapter 2.3.1</td>
    <td>Advanced Techniques - Szeliski Chapter 3.4-3.5</td>
  </tr>
  <tr class="feature-detection">
    <td>4</td>
    <td>September 16, 2024</td>
    <td>Lecture</td>
    <td><strong>Feature Detection and Invariance</strong></td>
    <td>Feature Detection - Szeliski Chapter 7.1</td>
    <td>Feature Invariance - Szeliski Chapter 7.1</td>
  </tr>
  <tr class="holiday">
    <td>5</td>
    <td>September 23, 2024</td>
    <td>Holiday</td>
    <td><strong>National Day Holiday</strong></td>
    <td>No class</td>
    <td>No class</td>
  </tr>
  <tr class="feature-detection">
    <td>6</td>
    <td>September 30, 2024</td>
    <td>Lecture</td>
    <td><strong>Feature Descriptors, Matching, and Image Transformations</strong></td>
    <td>Feature Descriptors & Matching - Szeliski Chapter 7.1</td>
    <td>Image Transformations - Szeliski Chapter 3.6</td>
  </tr>
  <tr class="geometric-vision">
    <td>7</td>
    <td>October 7, 2024</td>
    <td>Lecture</td>
    <td><strong>Image Alignment and RANSAC</strong></td>
    <td>Image Alignment - Szeliski Chapter 6.1</td>
    <td>RANSAC - Szeliski Chapter 6.1</td>
  </tr>
  <tr class="geometric-vision">
    <td>8</td>
    <td>October 14, 2024</td>
    <td>Lecture</td>
    <td><strong>Cameras and Panoramas</strong></td>
    <td>Cameras - Szeliski Chapter 2.1.3-2.1.6</td>
    <td>Panoramas - Szeliski Chapter 8</td>
  </tr>
  <tr class="geometric-vision">
    <td>9</td>
    <td>October 21, 2024</td>
    <td>Lecture</td>
    <td><strong>Single-view Modeling and Stereo</strong></td>
    <td>Single-view Modeling - Szeliski Chapter 11.1</td>
    <td>Stereo - Szeliski Chapter 12.3-12.5</td>
  </tr>
  <tr class="geometric-vision">
    <td>10</td>
    <td>October 28, 2024</td>
    <td>Lecture</td>
    <td><strong>Light, Perception, and Photometric Stereo</strong></td>
    <td>Light & Perception - Szeliski Chapter 2.2</td>
    <td>Photometric Stereo - Szeliski Chapter 13.1</td>
  </tr>
  <tr class="geometric-vision">
    <td>11</td>
    <td>November 4, 2024</td>
    <td>Lecture</td>
    <td><strong>Multiview Stereo and Two-view Geometry</strong></td>
    <td>Multiview Stereo - Szeliski Chapter 12.7</td>
    <td>Two-view Geometry - Szeliski Chapter 11.3 and 12.1</td>
  </tr>
  <tr class="holiday">
    <td>12</td>
    <td>November 11, 2024</td>
    <td>Holiday</td>
    <td><strong>Holiday</strong></td>
    <td>No class</td>
    <td>No class</td>
  </tr>
  <tr class="geometric-vision">
    <td>13</td>
    <td>November 18, 2024</td>
    <td>Lecture</td>
    <td><strong>Structure from Motion</strong></td>
    <td>Introduction to Structure from Motion - Szeliski Chapter 11.4</td>
    <td>Advanced Concepts - Szeliski Chapter 11.4</td>
  </tr>
  <tr class="deep-learning">
    <td>14</td>
    <td>November 25, 2024</td>
    <td>Lecture</td>
    <td><strong>Introduction to Recognition and Image Classification</strong></td>
    <td>Introduction to Recognition - Szeliski Chapter 5.1</td>
    <td>Image Classification - Szeliski Chapter 5.1, 5.3, 6.2</td>
  </tr>
  <tr class="deep-learning">
    <td>15</td>
    <td>December 2, 2024</td>
    <td>Lecture</td>
    <td><strong>Convolutional Neural Networks I</strong></td>
    <td>Introduction to CNNs - Szeliski Chapter 5.3</td>
    <td>Advanced CNN Concepts - Szeliski Chapter 5.4</td>
  </tr>
  <tr class="deep-learning">
    <td>16</td>
    <td>December 9, 2024</td>
    <td>Lecture</td>
    <td><strong>Inverse Graphics and Neural Radiance Fields</strong></td>
    <td>Inverse Graphics - Szeliski Chapter 14.6</td>
    <td>Neural Radiance Fields - Szeliski Chapter 14.6</td>
  </tr>
  <tr class="deep-learning">
    <td>17</td>
    <td>December 16, 2024</td>
    <td>Lecture</td>
    <td><strong>Training Deep Networks</strong></td>
    <td>Introduction to Deep Network Training - CS 231N</td>
    <td>Advanced Training Techniques - CS 231N</td>
  </tr>
  <tr class="ethics">
    <td>18</td>
    <td>December 23, 2024</td>
    <td>Lecture</td>
    <td><strong>Computer Vision, Ethics, and Society</strong></td>
    <td>Ethical Considerations - FATE Tutorial</td>
    <td>Societal Impacts - FATE Tutorial</td>
  </tr>
  <tr class="deep-learning">
    <td>19</td>
    <td>December 30, 2024</td>
    <td>Lecture</td>
    <td><strong>Image Generation and Diffusion Models, Course Review</strong></td>
    <td>Image Generation Concepts</td>
    <td>Diffusion Models & Course Review</td>
  </tr>
</table>
