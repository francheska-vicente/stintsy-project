# You're Toxic, I'm Slippin' Under: Toxic Comment Classification Challenge
In digital communities and forums on the internet, users often choose to remain anonymous as real names are not required when conversing with strangers online. With this anonymity comes the freedom to express one's thoughts without fear of being judged or recognized, yet this might also mean that users are free to say abusive sentiments with little to no repercussions. While most online forums and social media sites have various ways to moderate (e.g. moderators and staff that manually review posts and comments, a report button under messages, voting for comments and posts), these methods are not enough to combat the significant number of toxic comments made.

With this, ways to automate checking for toxicity in online text should be improved to foster a safe and respectful online environment.

The [`Toxic Comment Classification Challenge`](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/overview) is a Kaggle challenge by the [`Conversation AI team`](https://conversationai.github.io/), which is composed of researchers from both [`Jigsaw`](https://jigsaw.google.com/) and `Google`. This challenge invites participants to build a multi-headed model that can accurately detect the types of toxicity (i.e.,toxic, severe toxic, obscene, threat, insult, and identity hate) better than Perspective’s [`current models`](https://github.com/conversationai/unintended-ml-bias-analysis). Thus, the dataset given contains a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. 

This project's best model received a private ROC AUC score of **0.97559**, and public ROC AUC score of **0.97622**.

## Project Files and Folders
This Github Repository contains three folders, and two main files.

#### Folders
| Folders                        | Description                                                        |
|--------------------------------|--------------------------------------------------------------------|
| [`cleaned_data`](cleaned_data) | Folder that holds the cleaned version of the train and test data   |
| [`data`](data)                 | Folder that holds the original data from the Kaggle challenge      |
| [`results`](results)           | Folder that holds the prediction of the different algorithms tried |

#### Jupyter Notebooks
| Files                                                                                        | Description                                                 |
|----------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| [`ToxicComment_S13_Group8.ipynb`](ToxicComment_S13_Group8.ipynb)                             | Main notebook that also holds the Data Cleaning and Pre-processing, and EDA |
| [`ToxicComment_S13_Group8_Supplementary.ipynb`](ToxicComment_S13_Group8_Supplementary.ipynb) | Other solutions tried to solve the Challenge      |

## How to set up and run the project locally through JupyterNotebook or JupyterLab
1. Extract the folder from the zipped file that you can download through this DownGit [link](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/francheska-vicente/stintsy-project).
2. Launch `Jupyter notebook` or `JupyterLab`.
3. Navigate to the project folder containing `ToxicComment_S13_Group8.ipynb`.
4. Open `ToxicComment_S13_Group8.ipynb`.

## Authors
- **Francheska Josefa Vicente**  <br/>
francheska_vicente@dlsu.edu.ph
- **Sophia Danielle S. Vista** <br/>
sophia_danielle_vista@dlsu.edu.ph
