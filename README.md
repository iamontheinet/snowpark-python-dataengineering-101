# Snowpark for Python -- Data Engineering 101

## Overview

The repo covers the basics of working with Snowpark for Python for Data Engineering.

* Import Python Libraries
* Estabish Secure Connetion to Snowflake using AWS Secrets Manager
* Load Data into Snowpark DataFrames
  * Movies and TV reviews
  * Musical Instruments Reviews
* Snowpark DataFrame Actions and Transformations
  * Access Semi-structured Data using Snowpark DataFrame API
  * Combine Movies & TV with Musical Instruments Reviews
  * Replace Missing Values for REVIEWTEXT column with "Not available"
* Snowpark Python User-Defined Function (UDF)
  * (Simple) Create and Register UDF named "to_lowercase"
  * Call "to_lowercase" UDF on "SUMMARY" column in Snowpark DataFrame
  * (Complex) Create and Register Natural Language Processing (NLP) UDF using spaCy and BeautifulSoup
  * Call NLP UDF on column "REVIEWTEXT" in Snowpark DataFrame to tokenize Amazon Reviews
* (Scaling) Snowpark Python Stored Procedure
  * Create Python Function to Transform Data
  * Register Python Function as Snowpark Stored Procedure to Deploy Code to Snowflake
  * Execute Snowpark Stored Procedure to Transform Data on Snowflake
  * Examine Results - Reviews and Tokens
