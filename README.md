# Intro
A tidier approach to ad-hoc analysis.

<img width="335" alt="image" src="https://user-images.githubusercontent.com/47161914/186163542-c00f80e8-569a-4643-ae26-c2c689fe04c1.png">


Data Analysis doesn't need to be hard. You can keep things very simple and still
achieve all of the insights you need while moving fast.

This app serves as a simple demo of a lightweight approach to this. Add in
DBT and Dagster and you really do have all you need. pip installable business
analysis.

This is a one database analytics tool, whatever CSV you upload will end up in
the same SQLite file behind the scenes.

## Features
- [ ] Connect to Snowflake.
- [ ] Way to delete queries.
- [ ] Integrate DBT / smoothly work with it
- [x] Save and load queries.
- [ ] SSO with facebook / google / azure login
- [x] Remove the select y axis and x axis in favour of using 1st for X etc.
- [x] Create API endpoint to return query results
- [ ] Open-source a way to create forms with streamlit
- [ ] Apply the same process / system to your QDrant UI
- [ ] Submit to Analytics Vidhya
- [ ] Should have table name as query to follow single entity convention.
- [ ] Add method to save chart config (e.g. bar vs line vs scatter)
- [ ] Do the same for a Vector Database with json queries!
- [ ] Integrate Git API, e.g. a structure to your branches, branch per graph with the name of the graph, auto-merged but labelled as "unverified". Basically just have one branch which takes everything, and one for accepted content post Pull Request. Find a way to just have a PR with each individual graph as well (same for the transformations). You want to isolate the smallest reasonable change.
- [ ] Hosted DBT catalogue + UI for the input. 

A self-serve API. Written up in more depth here https://medium.com/p/cd6a9ba8a48f

```
uvicorn api:app --reload
```

Strict frameworks lead to greater productivity. Transformations in SQL,
plotting in plotly.

Filling the gap between jupyter notebooks and BI solutions.

Call it AdHoc or UntitledNine

Everyone qualified to use this tool is qualified to contribute.
The code is extremely simple.

Built by engineers for engineers.
