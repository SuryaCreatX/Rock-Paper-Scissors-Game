# Playing Rock, Paper, Scissors with AI

This repository contains the notebook for "Playing Rock, Paper, Scissors with AI" Tutorial

Rock Paper Scissors is a hand game for two or more players. Participants say “rock, paper, scissors” and then simultaneously form their hands into the shape of a rock (a fist), a piece of paper (palm facing downward), or a pair of scissors (two fingers extended). 
 
The rules are straightforward :

- Rock smashes scissors
- Paper covers rock
- Scissors cut paper

You can access the Tutorial for this [here](https://www.learnopencv.com/playing-rock-paper-scissors-with-ai/).

[Playing Rock, Paper, Scissors with AI](Rock_paper_scissor.ipynb)

You can download the rps3.h5 model from [this link](https://drive.google.com/file/d/1ZAEhMXlAxDkVbVo-1DE2aO_YphDscJLD/view?usp=sharing), although I would strongly suggest to train your own model on your own hands.

- Trained model attached with the repo


# Modified code

```
conda create -n rps Python=3.8
conda activate rps
pip install -r requirements.txt

# To train the model
jupyter-lab 
# Then open Rock_paper_scissor.ipynb

# To play the game
python game.py
```








