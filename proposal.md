# **MIS3640 Spring 2021 - Project Proposal**
## **Abegail Santos**

### **The Big Idea: What is the main idea of your project? What topics will you explore and what will you generate? What is your minimum viable product? What is a stretch goal?**

My goal for this project is to build an interactive website where users can check harmful ingredients in cosmetics at Sephora.
I chose to explore the products in Sephora because it is one of the most popular shops in the United States that offers a wide range of beauty products.

My program will be identifying products that include one or more of the following ingredients in [this list](https://cscpsearch.cdph.ca.gov/search/reportedIngredients). Long term exposure to these toxic ingredients may lead to health problems such as cancer, birth defects, or other developmental or reproductive harm. Therefore, in building this project, I hope to help avid makeup users like me to make informed decisions when purchasing cosmetics. 

In my web app, users will be able to filter or search by brands, products, and family of ingredients.

I envision my web app to display the following results (data visualization): 
- the most commonly used harmful ingredients
- all products that contain one or more harmful ingredients 
- top categories of cosmetics containing the most number of harmful ingredients
- top brands that produce the most number of products containing one or more harmful ingredients 

I will also create a page that contains information about each of the toxic ingredients and their potential side effects to educate or guide the user. 

### **Learning Goals: Since this is a team project, you may want to articulate both shared and individual learning goals.**

Learning goals 
- Learn the basics of webscraping and data visualization in Python, and data analysis techniques 
- Familiarize myself with libraries such as Scrapy, pandas, or matplotlib. 
- Learn how to create an interactive web app using Flask
- Apart from the technical skillset that I seek to develop, I am also looking forward to learn more about my chosen topic which is about the product safety in the cosmetics industry. 

### **Implementation Plan: this will probably be pretty vague initially. Perhaps at this early juncture you will have identified a library or a framework that you think will be useful for your project. If you don't have any idea how you will implement your project, provide a rough plan for how you will determine this information.**

To build my project, I believe that I will need to do the following: 

Scrape information from all the products in the makeup section listed on www.sephora.com.
- I would need to extract the following data from each product: product ID, product name, brand name, category, ingredients -- list. 
- I will use Scrapy, a package in Python.

After collecting the data, I would need to evaluate it against the list of undesirable ingredients reported to [California Safe Cosmetics Program](https://cscpsearch.cdph.ca.gov/search/reportedIngredients). 

Ingredients analysis 
- Data visualization using pandas/matplotlib
- I  still need to look into how I will approach this step. 

Build web app
- From my current research, it seems that I would need to use Flask in order to build an interactive web app.
- I  still need to look into how I will approach this step. 


### **Project schedule: You have 8 weeks (roughly) to finish the project. Sketch out a rough schedule for completing the project. Depending on your project, you may be able to do this in great specificity or you may only be able to give a broad outline. Additionally, longer projects come with increased uncertainty, and this schedule will likely need to be refined along the way.** 

1. 2/26 - Submit project proposal 
2. Week 1 - Research and learn about the skills I need to use for this project. Possibly interview 1-2 people that fall under my target market and ask for feedback.
3. Week 2, 3 - Try webscraping Sephora (data collection); data cleaning
5. Week 4, 5 - Data visualization and analysis
6. Week 6, 7, 8 - Build interactive website; try out program  
7. 4/26 - Submit code 

Note: This project timeline is tentative considering that I am still quite unfamiliar with the amount of effort or time that each phase requires.

### **Collaboration plan: How do you plan to collaborate with your teammates on this project? Will you split tasks up, complete them independently, and then integrate? Will you pair program the entire thing? Make sure to articulate your plan for successfully working together as a team. This might also include information about any software development methodologies you plan to use (e.g. agile development). Make sure to make clear why you are choosing this particular organizational structure.**

I will be working on this project alone given my difficulties in working with others remotely. 

### **Risks: What do you view as the biggest risks to the success of this project?**

Risks:
- Time management: Learning the topics from scratch; and I will be working on this project while delivering on my other academic commitments. 
- Debugging problems: not being able to identify or approach the problem. 
- This project might be too ambitious for my current skill level. Therefore there will be more potential challenges that I am not aware of as of this moment.  

To overcome these obstacles, I will do the following:
- Doing my due diligence: research as much as I can and learn from resources such as YouTube videos, online thread discussions, articles, data science websites, etc.
- Dedicate a certain amount of hours per week to work on this project
- Ask for professor's help and guidance when I feel stuck

### **Additional Course Content: What are some topics that we might cover in class that you think would be especially helpful for your project?**

- building a web app; introduction to flask 
- introduction to webscraping
- matplotlib/pandas library
- API?  

