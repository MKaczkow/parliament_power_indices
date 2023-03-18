# Power indices in POL parliament
Let's apply some game theory metrics to POL parliament...

## Basic info
Basic goal of this repo is to measure real legislative power of political parties in Polish parliament using game theory metrics, such as Shapley-Shubik power index. Obviously, this is just mathematics, so real coalitions, common vales, etc. of parties are not accounted for. For now, only very simple calculations are provided, taking into account only the larger blocks and coalitions - actual parties are members of this blocks.

## About Polish parliament
Polish parliament is bicameral. Lower house (*The Sejm*) is larger, gets more media coverage and acts as the highest legislative power (reference: [wikipedia ENG](https://en.wikipedia.org/wiki/Sejm)). Upper house (*The Senat*) is smaller and has more of an oversight role (reference: [wikipedia ENG](https://en.wikipedia.org/wiki/Senate_of_Poland)). As for now (March 2023) the government coalition has independent majority in lower house, but not in upper house of parliament.

## Further ideas
1. Plot results
2. Be more specific - split coalitions into actual parties
3. Consider some different majorities
4. Auto-scrapping of up-to-date numbers of seats

## Setup
1. Clone repo
2. Create virtual enviroment
3. `pip install -r requirements.txt`