# java-DesignPatterns-StockBuilder
## 生成器模式应用
* 目的：所返回的对象并不是基于显示对象的简单派生，而是由显示对象的不同组合而构成的完全不同的**用户界面**。
* 题目：编写一个程序来跟踪投资表现，例如股票、债券和基金。程序能够显示各种投资的持有份额表，以便选择一种或者多种投资，并对它们的相对表现绘制图表。即使事先不能预测在某个给定时刻每种投资各持有多少份额，但仍希望程序对于大量资金（例如股票）或者少量资金（例如基金）能够提供相应的显示。在这些情况下，都希望提供某种多项选择显示，以便可以从中选择一种或者多种资金绘图。如果有大量资金，可以使用**多选列表框**；如果只有少量资金，则可以使用**一组复选框**。生成器类根据要显示的项数生成一个界面，但是对于结果的返回则提供相同的方法。
---
## Generator mode application
* Purpose: the returned object is not a simple derivation based on the display object, but a completely different **user interface** composed of different combinations of display objects.
* Title: write a program to track investment performance, such as stocks, bonds and funds. The program can display the table of holding shares of various investments, so as to select one or more investments and chart their relative performance. Even if it is impossible to predict in advance how many shares each investment will hold at a given time, we still hope that the program can provide corresponding display for a large amount of funds (such as stocks) or a small amount of funds (such as funds). In these cases, it is desirable to provide some kind of multi-choice display from which one or more fund drawings can be selected. If you have a large amount of funds, you can use the **multiple selection list box**; if you have only a small amount of funds, you can use **a set of check boxes**. The generator class generates an interface based on the number of items to display, but provides the same method for the return of results.
