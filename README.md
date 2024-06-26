# NFL-players-Catch-Rate-and-associated-uncertainity
See how the Empirical Bayes process works with a Sports related application. Learn the catch probability in the National Football League (NFL) and understand of the uncertainty in the performance.

The catch rate is defined as the number of successful receptions (catches) by a player divided by the number of targets (a target corresponds to a pass thrown at the player). You can therefore consider successfully catching a pass as the **event**, and the number of times the player was targeted as the number of **trials**. The probability of catching a pass is therefore the **event probability** we are interested in learning.  

Calculating the catch rate is simple to do. It is also easy to search for and find. For example, [here](https://www.pro-football-reference.com/years/2019/receiving.htm) are the catch rates for all NFL players in the 2019 season. We wishe to move away from simple *point estimates* and get a better understanding of the **uncertainty** in the performance. Understanding the uncertainty is critical when evaluating talent, and making decisions for which players to sign in free agency. 

If we had to select specific players, it would be those identified by red in the figure below. We should look for players with high levels of uncertainty and secondly, we want to identify players with high mean values. In this way, there is a risk the player could do worse than what we expect them to do (a downside), but there is also a chance the player can outperform our expectations.

<img width="1177" alt="Screenshot 2024-06-26 at 3 32 09 PM" src="https://github.com/vedantkan/NFL-players-Catch-Rate-and-associated-uncertrainity/assets/68374993/b856937e-8e0a-4014-a559-272902e92765">
