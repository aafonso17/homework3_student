# Homework 3 Starter Code and Data
## **Instructions:**
Read through the following instructions carefully!
### Accessing Class Code and Instructions

1. Create a fork of the class repository in GitHub.

2. Clone this repository into the home directory of your own JupyterHub by running this command:
```git clone your_SSH_URL```

**Our JupyterHub server has trouble remembering the file permissions for our SSH keys. If you get a file permission error with your private ssh key, run the following line of code in your Terminal:**

```chmod 400 ~/.ssh/id_ed25519``` 
<br>

This will change your file permission to the proper permissions that SSH requires.

3. There should now be a "homework_3" directory in the home directory of your JupyterHub. In terminal, change directories into "homework_3". Next, click on the the "homework_3" icon on the filepath hierarchy in the left panel of JupyterHub. If you don't see it, make sure you're in the home folder by clicking the folder icon under the search bar. 

4. Double click the "HW3.ipynb" to open it in a new tab and begin working on the assignment. Read the instructions carefully, and make sure to write your answers in the specified cells. 

5. Make sure to use the answer variable names provided in the starter code. There are autograder tests embedded in the notebook that will check your work when you run the Autograder, and you can which tests you passed/failed after you submit.

6. Edit the **README** file and write your name and UW NetID. Add a paragraph on why the following plots elements (below) are necessary when designing figures (4-5 sentences). (5 points) 

7. As you continue to answer the homework questions and make edits to your code, make sure to regularly update your GitHub repository as well via git add, commit, and push. A good rule of thumb would be to run these git steps anytime you make an addition or change that you don't want to accidentally lose. Generally, you can push once a day to maintain good version control practices. <br>

Also, make sure that your git commands are running without errors before you refresh your GitHub and check your changes. If you are not seeing the updated changes you created in your local JupyterHub directory, check where your status is by this command: <br>
``` git status```

Then, you can see if you made an error with your git add, commit, or push commands.


### _your name and UW net ID_
Write your paragraph on the importance of the required plot elements here.
1) Concise, descriptive title for each figure/subplot
2) Axis labels with units (when possible)
3) Appropriate axis limits (minimum and maximum)
4) Appropriate tick resolution
5) Legend when using different datasets 
6) Appropriate font size (a good range is 12-15)
Having a concise, descriptive title for each figure/subplot on your plot is important because it gives a name to your data and it makes it clear on what you're displaying on your plot/subplot. Axis labels with units (when possible) is important because that allows people looking at your plot/subplot to distinguish the different variables that your data supports. It also helps to see the trends that might go along with the data that you're importing, to see if the two (or more) variables correlate with each other or one specific thing that one variable does causes the other variable to do something. For example, if having a lower or higher temperature in sea water affects its density. Those two varaibles would be temperature and density. Appropriate axis limits (minimum and maximum) is important because your plot *can have a specific range of values for number that coinside with each other.* * If your range of numbers is off, that can affect your plot in having too many values on one side and it being too crammed when you can have a more efficient and spread-out, easier-to-read set of datapoints. *tick resolution* Having a good range for tick resolution is important because if you have too big or too little of a number, it can affect how your data is being plotted on that range of numbers. Legends when using different datasets can help with clarity in your plot/subplot. It can allow for the person looking at it to correspond a color with a function. For example, having a temperature plot with different colors representing cooler or warmer temperatures can help improve your plot; red colors representing hot/warmer temperatures and blue colors representing cold/cooler temperatures. Having appropriate font sizes in your plot can help with making your plot look professional and to make sure if you're presenting it, people can see what you've made. If you have it displayed on a powerpoint, and the font size is too small for people can't see in the back, that wouldn't be good and they couldn't see the data you're presenting.
