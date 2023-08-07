# Segmenting-Retinal-Blood-Vessels-With-AI
Detection of the retinal fundus vessels.

This project is being developed in order to recognize the vessels of the eye by different methods.

The first method is an algorithmic method that operates on the principle of algorithms and filters, it does not use AI.

The second method is a method using AI.

Algorithmic method
------

In the end, we will compare the 2 results and see which method specifically turned out to be more effective in my case.

Method one (colors may vary, but the main thing is the statistics that remain unchanged depending on the color, everyone can choose the color that they like).

### Theoretical description:

1.	At the beginning we use The Sato filter which is taken from the library.
2.	We adjust the intensity of the colors to make our eyes more readable and friendly (you can play with the numbers inside because they affect the quality).
3.	In addition, we do a filter that allows you to divide the brighter pixels and the darker which again increases the readability as if it imposes markers on these pixels which works independently of the filtration in Step 1 and 2, that is, separately dodtkowo increase the contrast of the photo of the eye.


| Image | Information |
| ----- | ----------- |
| ![image](https://github.com/MaksimLik/Segmenting-Retinal-Blood-Vessels-With-AI/assets/72620745/db676fb1-0d30-46dd-9cbe-434d01077ba1) | <ul><li>Accuracy score: 96.71</li><li>Sensitivity score: 74.32</li><li>Specificity score: 98</li></ul> |
| ![image](https://github.com/MaksimLik/Segmenting-Retinal-Blood-Vessels-With-AI/assets/72620745/85048983-7dd9-46aa-af81-eac02c051083) | <ul><li>Accuracy score: 96.7</li><li>Sensitivity score: 77.14</li><li>Specificity score: 98</li></ul> |
| ![image](https://github.com/MaksimLik/Segmenting-Retinal-Blood-Vessels-With-AI/assets/72620745/07fe94f2-c94e-43dd-8ee8-f76b7855133a) | <ul><li>Accuracy score: 96.93</li><li>Sensitivity score: 72.87</li><li>Specificity score: 98.6</li></ul> |
(7,8,9)

As you can see, the results were not perfect, and average 74%. This is the accuracy of vessel recognition in the filtering method.

AI method
------

### Theoretical description:


| Image | Information |
| ----- | ----------- |
| ![image](https://github.com/MaksimLik/Segmenting-Retinal-Blood-Vessels-With-AI/assets/72620745/de5b02ef-5d59-45bd-b66a-10b2a5d387df) | <ul><li>Accuracy: 92.50</li><li>Sensitivity: 38.72</li><li>Specificity: 98.43</li></ul> |
| ![image](https://github.com/MaksimLik/Segmenting-Retinal-Blood-Vessels-With-AI/assets/72620745/4e967ad7-6c8e-4ec3-b47b-61332463ac39) | <ul><li>Accuracy: 91.42</li><li>Sensitivity: 44.73</li><li>Specificity: 97.31</li></ul> |
| ![image](https://github.com/MaksimLik/Segmenting-Retinal-Blood-Vessels-With-AI/assets/72620745/e4826485-dfe6-4f7a-ac2d-fa382d71806c) | <ul><li>Accuracy: 93.22</li><li>Sensitivity: 45.82</li><li>Specificity: 97.81</li></ul> |
(7,8,9)
