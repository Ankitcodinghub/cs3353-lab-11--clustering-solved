# cs3353-lab-11--clustering-solved
**TO GET THIS SOLUTION VISIT:** [CS3353 Lab 11- Clustering Solved](https://www.ankitcodinghub.com/product/aiml-cs-335-solved-17/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124350&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3353 Lab 11- Clustering Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Lab 11: Clustering

Important: Please read the instructions mentioned in the questions carefully. We have NOT provided any boilerplate code however some utility scripts have been provided to make your job easier. In this lab, you will be graded based on your algorithm’s final performance.

1 K-Means

For the first question of this assignment, you are provided with a json file points_4D.json. This file contains a list of points in 4-dimensions. It is known that these points mostly lie in a 2-dimensional subspace of the 4-dimensional real space. For this part, you are free to use library implementations of techniques whenever available.

1.1 Dimensionality Reduction and Visualization (project.py)

Your first task is to find this subspace and project these points on it. Use a suitable technique to make this transformation and store the resultant 2-D points in points_2D.json. A helper function for this is available in utils.py.

The helper script visualize.py will plot a scatter plot of these transformed points for you and store it in scatter_2D.jpeg.

1.2 Kernel Selection and KMeans (cluster.py)

If you have completed your first task succesfully, you will easily observe k different clusters in scatter_2D.jpeg. Note the value of k – you will perform K-Means clustering with this k later.

Although, the clusters might NOT be linearly seperable. Your next task is to project these points further into a finite kernel space where they will be linearly seperable. Use K-Means clustering in this kernel space to assign labels to the points.

Finally, output the value of k and the labels obtained (which should be 0 &lt;= label[i] &lt;= k−1) in labels.json. A helper function for this is available in utils.py. Make sure that you use this function because it disambiguates permutations of label assignments.

We will use scatter_2D.jpeg and labels.json to grade your implementation.

1

2 Latent Clusters

In this question, you are provided with latent representations of 1000 MNIST digits, which were created using an auto-encoder. These 1000 images were randomly sampled from the MNIST dataset, and their labels are unknown to us. The only information provided to you is that the sampled images contained digits from all the 10 classes, i.e., we do not know how many images from a particular class were sampled. Your task is to cluster the representations of similar digits together. For this part, you are not to use library clustering functions.

The latent space representations of the points are provided in mnist_samples.csv. Code up a clustering algorithm in main.py and store the resulting labels using the helper function store_labels() from utils.py. Once again, we will use a suitable performance metric to grade your submission.

3 Submission instructions

You should write code only in the files specified. You should not create any new files or folders. After you are done, perform the following two operations :

mv rollno_L11 &lt;ROLL_NUMBER&gt;_L11

tar -zcvf &lt;ROLL_NUMBER&gt;_L11.tar.gz &lt;ROLL_NUMBER&gt;_L11

Replace &lt;ROLL_NUMBER&gt; with your own roll number. If your roll number has alphabets, they should be in “small” letters. Submit the tar file on Moodle. Happy coding and happy Diwali!

2
