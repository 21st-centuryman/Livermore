<div align="center">

# Livermore
##### Fetch, process, and analyse stock data!

[![Rust](https://img.shields.io/badge/Livermore--Fetch-orange.svg?style=for-the-badge&logo=rust)](https://github.com/21st-centuryman/Livermore-fetch/tree/main)
[![Python](https://img.shields.io/badge/Livermore--Analyze-3776AB.svg?style=for-the-badge&logo=python&logoColor=white)](https://github.com/21st-centuryman/Livermore-analyze)

<i>Click on these buttons to go to project</i>
</div>

## ⇁  Introduction
Welcome to Livermore, This is my attempt to get into AI in ways that I enjoy, meaning having a goal in mind and falling over every step on the way; hopefully learning something while during it. In Livermore's case I will try to fetch stock information and then use an AI to trade day to day stock prices. Named after the stock broker Jessie Livermore, the inspiration for "Reminicense of a Stock Operator", the author of "How to trade in stocks".

## ⇁  Structure
Livermore is structured in two git submodules, Livermore-fetch will fetch and process the data, and Livermore-Analyze is my AI and gym environment.

## ⇁  Dependencies
Annoyingly I decided to write these two projects in two languages. 

Fetch is written in Rust using both [polars](https://www.pola.rs/) and the [yahoo-finance-api](https://docs.rs/yahoo_finance_api/latest/yahoo_finance_api/) crate. This is because I am actively learning rust and it would be a shame to stop that tend now. 

Analyse is written in Python using [Stable baselines3](https://github.com/DLR-RM/stable-baselines3) and [gymnasium](https://gymnasium.farama.org/).
