# Deep Learning project
## Initial for a platform of mechanical tools sharing  -- Tools Image Classification

### Question/Need:

- What is the question behind your analysis or model and what practical impact will your work have?

  Many DIY experts probably face very similar dilemmas: Should I spend money to buy this fancy tool for my next project? If yes, where I am going to store this extra tool, besides my tons of other? They may also share same hope or dream: It would be awesome I can just borrow from someone nearby who has this tool for a few days! And I would love to share with others my tool who loves DIYs too. My husband is one of those DIY fan, he has been hoping that there is a platform exists from which can borrow tool to save money and also share his tools with others. So I am trying to use this deep learning project opportunity to accomplish a basic functionality of a tool sharing platform: mechanical tool image classification. Tool sharers can just take a picture of his tool and upload to the platform, the platform can automatically classify the tools.


- Who is your client and how will that client benefits from exploring this question or building this model/system?
  My husband. If possible, all DIY experts and mechanical tool fans. The tool image classification functionality will make the platform user friendly and encourage more people to share and use the platfrom.



### Data Description:

- What dataset(s) do you plan to use, and how will you obtain the data? Please include a link! (The link can be to the dataset you’re downloading, the site you’re scraping, etc.)
The dataset used in this project is downloaded from [Kaggle](https://www.kaggle.com/salmaneunus/mechanical-tools-dataset?select=hammer.csv.csv).

- What is an individual sample/unit of analysis in this project? In other words, what does one row or observation of the data represent?What characteristics/features do you expect to work with? In other words, what are your columns of interest?    

Each individual unit of the dataset is a picture of tool. There are 8 categories: Gasoline can, hammer, pebbles, rope, screw driver, tool box, wrench, pliers. I am not sure why pebble is one of those categories, which suppose to be all tools. But I will investigate more later and decide if I will use pebble pictures or not in the project.

- If modeling, what will you predict as your target?

The target of project is to predict which category a picture belongs to.

###  Tools:
- How do you intend to meet the tools requirement of the project?
  - Python neural network libraries/tools: Tensorflow, Keras
  - other libraries handling data wrangling and visualization


- Are you planning in advance to need or use additional tools beyond those required?
To be decided.

### MVP Goal:
- What would a minimum viable product (MVP) look like for this project?
A basic CNN model.
