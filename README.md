# home_sales_challenge

## Overview

This challenge was all about exploring and testing our knowledge of SparkSQL through the use of a home sales data set. We created temporary views of uncached, cached, and parquet partitioned data, comparing the runtimes speeds. The cached data had the fastest queries, then the parquet partition, and finally the uncached data. For this example, the dataset was small so we are talking about fractions of a second, but when multiplied on millions of rows and distributed computing power this can have a huge and costly effect.

## Contents

* Home_Sales.ipynb
* this README