## Answers

[Endophytic Fungi as a Promising Biocontrol Agent to Protect Wheat from
Fusarium graminearum Head
Blight](https://apsjournals.apsnet.org/doi/10.1094/PDIS-06-21-1253-RE)

### 1. 4 pts. Explain the following

**a. YAML header**

A YAML header is a block of metadata placed at the top of markdown
documents. It defines settings and parameters such as title, author,
date and default output format.

**b. Literate programming**

Is basically a way of documenting a pipeline treating code as logic
chunks where each one goes along a paragraph of text explaining the
functioning and purpose inside the whole script.

### 2. 6 pts. Take the code you wrote for coding challenge 3, question 5, and incorporate it into your R markdown file. Some of you have already been doing this, which is great! Your final R markdown file should have the following elements.

**a. At the top of the document, make a clickable link to the manuscript
where these data are published. The link is here:**

[Check link up there
^](https://apsjournals.apsnet.org/doi/10.1094/PDIS-06-21-1253-RE)

**b. Read the data using a relative file path with na.strings option set
to “na”. This means you need to put the Mycotoxin.csv file we have used
for the past two weeks into your directory, which git tracks.**

``` r
dataset <- read.csv("MycotoxinData.csv")
```

**c. Make a separate code chunk for the figures plotting the DON data,
15ADON, and Seedmass, and one for the three combined using ggarrange.**

![](CodingChallenge4_ans_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->![](CodingChallenge4_ans_files/figure-gfm/unnamed-chunk-2-2.png)<!-- -->![](CodingChallenge4_ans_files/figure-gfm/unnamed-chunk-2-3.png)<!-- -->

- In a separate chunk (echo is set to false for space)
  ![](CodingChallenge4_ans_files/figure-gfm/unnamed-chunk-3-1.png)<!-- -->
