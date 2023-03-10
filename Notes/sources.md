# Notes on Previous Sources


## Predicting Shot Location in Tennis Using Spatiotemporal Data

* Given the speed, location, angle of the shot, with respect to the relative position and movement of the player's involved - a top player will anticipate where the next shot will come based on these previous shot factors

* Players and broadcasters have developed perceptual expertise and pattern recognition skills that are akin to a **"Biological Probabilistic Engine"**

* To emulate the *game intelligence* of a player, a **Dynamic Bayesian Network (DBN)** is used to model and predict short-term behavior

Specific Contributions

1. Show that a combination of shot factors, especially the relative short-term player positions and velocities are the most predictive of future shot location
2. To gain a specific *x*,*y* shot location, the output space of **DBN** is augmented to include local regions to enrich the probability estimate
3. Developed an online model adaptation that method which incorporates adversarial player behavior as well as court conditions