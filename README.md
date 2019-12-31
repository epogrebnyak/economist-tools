![](https://img.shields.io/badge/dataset-3-blue)
![](https://img.shields.io/badge/learning-4-orange)
![](https://img.shields.io/badge/replication-2-brightgreen)


# Dataset access

You can migrate your data analysis from Excel to R/pandas or use 
R/pandas to prepare sunsets of data and work back on it in Excel.

I developed several tools that allow access to useful country and corporate datasets. 

- [weo](https://github.com/epogrebnyak/weo-reader) - IMF World Economic Outlook python client (`pip install weo`)
- [boo](https://github.com/ru-corporate/boo) - Rosstat annual corporate reports (`pip install boo`)
- [comtrade](https://github.com/ru-corporate/comtrade) - utilities to query UN Comtrade database for goods export

`weo` and `comtrade` wrap already good datasets, and `comtrade` API is nearly perfect. `boo` makes use of raw data, which is otherwise unaccessible.

# On the radar 

Here are some code projects by and for economists (to be annotatted):

- https://www.hse.ru/edu/courses/302789733
- https://github.com/WLM1ke/poptimizer
- https://github.com/lnsongxf?tab=stars
  
Please [send in](https://epogrebnyak.github.io/#about) your own similar projects for listing.

<!-- 
https://github.com/WLM1ke/poptimizer
-->

# Reference and learning

I maintain a website with open-source textbooks and guides in  
econometrics and statistics, [Econometrics Navigator](https://trics.me).

# Programming and IT skills

- [learn/python](https://github.com/epogrebnyak/learn/blob/master/python.md) - top 3 resources I recommend as quick intro to python
- [haskell-intro](http://tinyurl.com/haskell-intro) - a starter guide into functional programming with Haskell
- [superhero](https://github.com/epogrebnyak/superhero) - business analyst-to-developper learning curriculum (in Russian)

# Replication and reproducibility

Economic analysis is not terribly advanced in replication and reproducibility. Required skills taught in fragments and there are powerful incentives to keep your work to yourself, but hope things are changing (open access publishing, literate programming, data APIs, etc.).

I contributed some code to the following open source tools:

- [manubot](https://manubot.org) - changes to citation management submodule
- [handout](https://github.com/danijar/handout) - minor fixes

# Mantras and opinion

- [Analysis is a DAG](https://drivendata.github.io/cookiecutter-data-science/#analysis-is-a-dag) - try eliminate manual work parts or undocumented operations 
  from your our data transformations.
- [No silver bullet](http://worrydream.com/refs/Brooks-NoSilverBullet.pdf) - whatever 
  you try does not solve 100% of your problems.

# My other pages

- [Blog](https://epogrebnyak.github.io)
- [CV](https://epogrebnyak.github.io/cv/)
