# cs115-homework-3-giving-change-solved
**TO GET THIS SOLUTION VISIT:** [CS115 Homework 3-Giving Change Solved](https://mantutor.com/product/cs-115-hw-3-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113719&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS115 Homework 3-Giving Change Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Just knowing the minimum number of coins is not as useful as getting the actual list of coins. Next, write another version of the change function called giveChange that takes the same kind of input as change but returns a list whose first item is the minimum number of coins and whose second item is a list of the coins in that optimal solution. Here’s an example:

&gt;&gt;&gt; giveChange(48, [1, 5, 10, 25, 50])

[6, [25, 10, 10, 1, 1, 1]]

&gt;&gt;&gt; giveChange(48, [1, 7, 24, 42])

[2, [24, 24]]

&gt;&gt;&gt; giveChange(35, [1, 3, 16, 30, 50])

[3, [16, 16, 3]]

The order in which the coins are presented in the input list doesn’t really matter and, similarly, the order in which your solution reports the coins to use is also unimportant: In other words the solution [3, [16,

16, 3]] is the same to us as [3, [3, 16, 16] ] or [3, [16, 3, 16]]. All of these solutions use the same 3 coins after all!

that giveChange will always return a list of the form [numberOfCoins, listOfCoins], you can modify your change function relatively modestly to get the giveChange function. First, your base cases must observe the convention and return such a list of the form [numberOfCoins, listOfCoins]. Then, when you call giveChange recursively, remember that it is returning a list of this form. Your function will need to pick apart that list to get at the number of coins and the list of coins in that solution. Finally, after deciding whether the use-it or lose-it solution is better, you can prepare your list of the form [numberOfCoins, listOfCoins] and return that list.
