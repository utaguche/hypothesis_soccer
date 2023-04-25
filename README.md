# Hypothesis testing for scores in FIFA World Cup

![A soccer pitch for an international match.](soccer-pitch.jpg)

Suppose that we're working as a sports journalist at a major online sports media company, specializiLng in soccer analysis and reporting. Given the datasets for both men's and women's international soccer matches for a number of years, we want to know in which games more goals are scored, women's matches or those for men. This would yield an interesting investigative article would stimulate the curiosity of the subscribers. For this purpose, we perform a valid statistical hypothesis test.

Over years, there are lots of soccer tournamens. Thus, this time around, we  restrict the datasets to be analyzed only to the ones for `FIFA World Cup` games (not including qualifiers) since the datetime `2002-01-01`.

We start from two CSV files:
- `women_results.csv`
- `men_results.csv`

We are trying to ask the following question: 

> Do men get more scores than women in FIFA World Cup?

Let us set the following null and alternative hypotheses:

$H_0$ : The mean number of goals scored in women's international soccer matches is the same as men's.

$H_A$ : The mean number of goals scored in women's international soccer matches is greater than men's.

Based on a **10% significance level**, we evaluate the p-value.
