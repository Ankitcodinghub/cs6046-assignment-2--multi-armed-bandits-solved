# cs6046-assignment-2--multi-armed-bandits-solved
**TO GET THIS SOLUTION VISIT:** [CS6046 Assignment 2- Multi-Armed Bandits Solved](https://www.ankitcodinghub.com/product/cs6046-multi-armed-bandits-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117437&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6046 Assignment 2- Multi-Armed Bandits Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
SCORING: There are 4 question in this assignment which contributes to 10 points towards your final grade. Each question carries equal points.

WHAT SHOULD YOU SUBMIT? You should submit a zip file titled ’Solutions rollnumber.zip’ Your assignment will NOT be graded if it does not contain all of the following:

• A PDF file which includes explanations regarding each of the solution as required in the question. Title this file as ‘Report.pdf’

• Source code for all the programs that you write for the assignment clearly named.

CODE LIBRARY: You are expected to code all algorithms from scratch. You cannot use standard inbuilt libraries for the algorithms. You are free to use inbuilt libraries for plots. You can code using either Python or Matlab or C.

GUIDELINES: Keep the below points in mind before submission.

• Any graph that you plot is unacceptable for grading unless it labels the x-axis and y-axis clearly.

• Don’t be vague in your explanations. The clearer your answer is, the more chance it will be scored higher.

Q1: Randomizing the Leader: Consider the problem of online learning on the simplex ∆d where d = 1000; At round t, you predict pt and receive a vector zt and suffer a loss of pTt zt. Assume the adversary picks the vector zt as the t-th row in the dataset Dataset Z. Implement FTRL with quadratic and entropic regularization for this problem and plot the regret over time.

Now, consider the following algorithm which first picks and fixes a random 1000 dimensional vector R sampled uniformly from [0,1/η]d and uses the following rule for prediction

t

i=1

How would you choose η for this problem? For the value chosen, plot the regret bound for this algorithm as well. How does the regret bound compare with the previous two algorithms for this problem?

Q2: Mean Wise Variance Foolish?

The goal of this question is to study the variance of the EXP3 algorithm that was discussed in class. Let the number of arms be 10. At each iteration, generate a 10 dimensional loss vector where each component is chosen iid from a Beta distribution with both parameters equal to 5 for all arms except the 10th arm. For the 10th arm, let the parameters be α = 5,β = 10. Implement the algorithm and run it for 1000 times for 10,000 iterations each and plot the regret along with error bars. Comment on the variance of the algorithm. What happens to the variance when you play around with the shape parameters?. (Bonus:

Can you come up with an algorithm which has a better variance than EXP3?)

Q3:

An epsilon-greedy strategy for the stochastic multi-armed bandits set up exploits the current best arm with probability (1 ) and explores with a small probability . Consider a problem instance with 10 arms where the reward for the i-th (i = 1,…,10) arm is Beta distributed with parameters αi = 5,βi = 5∗i. Implement the epsilon-greedy algorithm (by trying out various values)and compare it with the performance of the EXP-3 algorithm and an algorithm that chooses an arm in a greedy fashion at every round (i.e., = 0) after playing each arm once in a round robin fashion. Plot the regret bounds and comment on your observations. (Bonus: Can you formally show a regret guarantee for the epsilon-greedy algorithm?)
