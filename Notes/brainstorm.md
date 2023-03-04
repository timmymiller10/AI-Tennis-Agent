# Initial Brainstorming for AI Agent


* Describe PEAS
    * **Problem** = Consistently play a game of tennis by making predictions on the best possible spot to hit the ball, given the data that is being perceived by computer vision.
    * **Environment** = Simulation?
        * Search for existing tennis simulator to test AI
        * May have to create a simple simulation software
    * **Actuators** = Code to spit out the best possible shot in a scenario. This could be coordinates, ball speed, ball spin, etc. This will become more clear as the specifics of our AI is built.
    * **Sensors** = Image-based computer vision
* Characteristics of Tennis Environment:
    * **Fully-observable**
        * Agent can observe position of ball, the score, other info such as other players skill level and physical condition
    * **Single-Agent** or **Multi-Agent**
        * One AI agent designed to 'play' tennis against another player
        * Can be single agent if the match is singles, or multi-agent in a doubles match (2 AI agents playing together against two other players)
    * **Deterministic**
        * AI would be based on programmed rules / heuristics
        * External factors also need to be considered (may cause unpredictability)
            * Weather (wind speed)
                * Could eliminate this with simply playing indoor tennis
            * Court Surface 
                * clay / grass could be more difficult to predict ball trajectory than a hard court
        * AI could also be programmed with randomized decision-making algorithm, which could make it less predictable and therefore more challenging to the opponent. 
    * **Sequential**
        * System would need to observe ball position, score, position of other players on court, then decide on an action to take, like hitting the ball in a particular location on the court. 
    * **Dynamic**
        * Environment of a tennis match is constantly changing in response to the actions of other players
    * **Continuous**
        * State of the game can take on a large number of possible values within a continuous space.
    * **Known** or **Unknown**
        * Depends on the specific implementation
        * Known if we are programming model with a pre-defined set of rules, which would need to be laid on in specific terms (may be difficult for tennis match)
        * Unknown if AI system uses machine learning algorithms to learn from examples of gameplay and develop its own set of rules / algorithms for decision making

Interesting References to look into:

[TennisAI - Possible Example](https://hackaday.io/project/180423-tennis-ai)