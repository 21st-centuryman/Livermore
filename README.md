<div align="center">

# Livermore
##### Fetch, process, and analyse stock data!

[![Rust](https://img.shields.io/badge/Livermore\-Fetch-orange.svg?style=for-the-badge&logo=rust)](https://www.rust-lang.org/)
[![Python](https://img.shields.io/badge/Livermore\-Analyze-blue.svg?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
</div>

## ⇁  Introduction
Welcome to Livermore, This is my attempt to get into AI in ways that I enjoy, meaning having a goal in mind and falling over every step on the way; hopefully learning something while during it. In Livermore's case I will try to fetch stock information and then use an AI to predict day to day stock prices. Named after the stock broker Jessie Livermore, the inspiration for "Reminicense of a Stock Operator", the author of "How to trade in stocks", and the Great Grandfather of adult film actess Brandi Love.

## ⇁  Structure
Livermore is structured in two git submodules, Livermore-fetch will fetch and process the data, and Livermore-Aaalyze the data using an AI.

## ⇁  Dependencies
Annoyingly I decided to write these two projects in two languages. 

Fetch is written in Rust using both [polars](https://www.pola.rs/) and the [yahoo-finance-api](https://docs.rs/yahoo_finance_api/latest/yahoo_finance_api/) crate. This is because I am actively learning rust and it would be a shame to stop that tend now. 

Analyse will be written in Python using the [Tinygrad](https://github.com/geohot/tinygrad) framework by George Hotz. This is because I actually want to learn the basic math and functions used in AI instead of using blind functions I found online. 

## ⇁  Current status
This is still a major work in progress please see the submodules for more detail. Cherio.

## ⇁  NOTE
Please know this is my own introduction to AI. I bet everything I am doing is wrong and stupid. However maybe this kindles an interest, who knows. 🤷‍♂️
