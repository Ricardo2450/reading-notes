# Ten Thousand Game 1

> ## [How to use Random Module](https://www.pythonforbeginners.com/random/how-to-use-the-random-module-in-python)

* Use the random module if you want the computer to pick a random number in a given range, pick a random element from a python list, pick a random card from a deck, flip a coin, etc. Or to create random strings while choosing passwords to make your password database.

* **randint()** function  can be used to create random strings within a range.
  * takes two numbers as its input argument. The first input argument is the start of the range and the second input argument is the end of the range.
  * returns a random number within that range.

* **random()** function is used to generate random numbers between 0 and 1.
  * If you want a larger number, you can multiply it by a larger value. EX. random.random() * 100

* **choice()** function is used to select a random element from a collection object like a list, set, tuple, etc
  * takes a collection object as its input argument and returns a random element.

* The **shuffle()** function shuffles the elements in the list in place.
  * Ex. from random import shuffle
  x = [[i] for i in range(10)]
  shuffle(x)

* **randrange()** function in the python random module is used to select a random element from a given range.

> ## [What is Risk Analysis](https://www.edureka.co/blog/risk-analysis-in-software-testing/)

* The probability of any unwanted incident is defined as Risk.

* **risk analysis** is the process of identifying the risks in applications or software that you built and prioritizing them to test

* risk analysis at the beginning of a project highlights the potential problem areas. It helps the developers and managers to mitigate the risks

* must know there are certain risks that are unavoidable
  * The time that you allocated for testing

  * A defect leakage due to the complexity or size of the application

  * Urgency from the clients to deliver the project

  * Incomplete requirements

* risk magnitude indicators
  * High: means the effect of the risk would be very high and non-tolerable. The company might face loss.

  * Medium: it is tolerable but not desirable. The company may suffer financially but there is a limited risk.

  * Low: it is tolerable. There lies little or no external exposure or no financial loss.

* sets of risks included in the risk identification process
  * Business Risks: This risk is the most common risk associated with our topic. It is the risk that may come from your company or your customer, not from your project.

  * Testing Risks: You should be well acquainted with the platform you are working on, along with the software testing tools being used.

  * Premature Release Risk: a fair amount of knowledge to analyze the risk associated with releasing unsatisfactory or untested software is required

  * Software Risks: You should be well versed with the risks associated with the software development process.  


* Risk Assessment: In the risk analysis process, these steps prove to be the most important one.

* There are three perspectives of Risk Assessment:
  * Effect – To assess risk by Effect. In case you identify a condition, event or action and try to determine its impact.

* Cause – To assess risk by Cause is opposite of by Effect. Initialize scanning the problem and reach to the point that could be the most probable reason behind that.

* Likelihood – To assess risk by Likelihood is to say that there is a probability that a requirement won’t be satisfied.

* There are three steps in preforming risk analysis:
  * Searching the risk

  * Analyzing the impact of each individual risk

  * Measures for the risk identified

> ## [Test Coverage](https://martinfowler.com/bliki/TestCoverage.html)

* Test coverage is a useful tool for finding untested parts of a codebase.

* doing enough testing if the following is true:
  * You rarely get bugs that escape into production, and
  * You are rarely hesitant to change some code for fear it will cause production bugs.

> ### Other good reads and watches
* [Big O Notation](https://www.youtube.com/watch?v=v4cd1O4zkGw)
* [Python Random](https://docs.python.org/3/library/random.html)
* [What is Dependency Injection](https://www.freecodecamp.org/news/a-quick-intro-to-dependency-injection-what-it-is-and-when-to-use-it-7578c84fa88f/)

[Return Home](../README.md)
