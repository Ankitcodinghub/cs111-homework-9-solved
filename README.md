# cs111-homework-9-solved
**TO GET THIS SOLUTION VISIT:** [CS111 Homework 9 Solved](https://www.ankitcodinghub.com/product/cs111-submit-your-paper-as-one-pdf-file-and-tell-gradescope-which-pages-each-problem-is-on-if-you-worked-with-a-partner-you-must-each-separately-write-up-and-turn-in-your-own-homework-paper-an/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115140&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS111 Homework 9 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
√

1. Newton’s method is often used with n = 1 to compute values of nonlinear functions like a. To solve x2− a = 0, we integrate x2− a and see that if we define

f(x) = x3/3 − ax,

then at x = argminf(x) (subject to x ≥ 0, where f is convex), we have x2−a = f′(x) = ∇f(x) = 0,

so minimizing f(x) computes x = √a. In the case n = 1 the Hessian matrix H is just f′′(x) = 2x, and the Newton iteration is

) (1)

) (2)

) (3)

(4)

√

1.1 Compute 4 by Newton’s method, starting with x0 = 1. Display a table of k, xk, and x2k for k = 0,1,2,…. As always, show your python code. How many iterations does it take to get 4 correct digits? 8 correct digits? 16 correct digits?

√

1.2 Repeat for 2, displaying the same table and answering the same questions.

2.1 Suppose the East Beach shoreline is the x-axis, so the beach is all points (x,y) with y ≥ 0 and the ocean is all points with y &lt; 0. A lifeguard is positioned at (x,y) = (0,20), that is, 20 meters north of the beach on the line x = 0. The lifeguard sees a swimmer in distress at (x,y) = (80,−40), that is, 40 meters out to sea and 80 meters east of the lifeguard.

1

Figure 1: Straight beach (2.1) Figure 2: Curved beach (2.2)

or cs111.gradient descent with some hand-tuning of the learning rate. In any case, report what you find and explain in detail how you arrived at the optimal value of x.

Draw a diagram showing the beach, the lifeguard, the swimmer, and the optimal path, with the various distances labelled. You can make the drawing either by hand or with matplotlib. Using the optimal path, how many seconds will it take the lifeguard to reach the swimmer?

2.2 Same problem as above, but now the shoreline is curved: Instead of the line y = 0, the shoreline

is the partial ellipse y = −p1000 − x2/10. Again, formulate a 1-dimensional optimization problem that minimizes the time to reach the swimmer over all possible x coordinates at which the lifeguard could enter the water. (Now, of course, for any given x, the lifeguard will enter the water at the point (x,y).) Solve the optimization problem for x using any of the solvers we demoed in class (feel free to try any of them), and report on what you find.

At what point (x,y) does the lifeguard enter the water? How many seconds does it take the lifeguard to reach the swimmer? Draw a diagram as before.

3. Recall the definition of a convex function: A function f from Rn to R is convex if, for all x and y in Rn and all 0 ≤ α ≤ 1,

αf(x) + (1 − α)f(y) ≥ f(αx + (1 − α)y),

that is, every chord is above the function values.

3.1. Assume that functions f and g are both convex. Prove that the function h(x) = max(f(x),g(x)) is convex by starting with the definition of convexity for f and g and giving a rigorous mathematical argument to show that h satisfies the definition as well.

3.2. Give an example of two convex functions f and g for which the function min(f,g) is not convex. Give values of x, y, and α for which the definition is not satisfied, and show the computation that proves it is not.

2
