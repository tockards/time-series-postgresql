# Notes on storing time series data in PostgreSQL

## What is time series data?

> A time series is a series of data points indexed (or listed or graphed) in time order. Most commonly, a time series is a sequence taken at successive equally spaced points in time. Thus it is a sequence of discrete-time data. Examples of time series are heights of ocean tides, counts of sunspots, and the daily closing value of the Dow Jones Industrial Average.

[Wikipedia](https://en.wikipedia.org/wiki/Time_series)

I suggest reading the blog post [What the heck is time-series data ...](https://blog.timescale.com/what-the-heck-is-time-series-data-and-why-do-i-need-a-time-series-database-dcf3b1b18563) by [timescale database team](https://blog.timescale.com) as it is quite thorough and should suffice as a definition during its absence from this README. 

## What is PostgreSQL?

> The World's Most Advanced Open Source Relational Database

[PostgreSQL Website](https://www.postgresql.org/)


#### Why PostgreSQL?

This repo is focused on techniques, tools, methods and other things that could aid others storing time series data inside PostgreSQL


#### Setup 

This project uses [vagrant][1]. The vagrant image is Ubuntu [18.04](http://releases.ubuntu.com/bionic/) server and [PostgreSQL 10](https://wiki.postgresql.org/wiki/New_in_postgres_10) is installed on it.
To get it running up on your box applyrun the command below after installing [vagrant][1].

```bash
$vagrant up
```

#### Methodology

- explain the reason behind using (Vagrant)[1] over something like [docker](http://docker.com).
- Testing methodologies etc


## Problem Statements

- Are examples to exercise PostgreSQL and Time series data.
- Not all Time-series problems are the same and should therefor be approached differently. 


 
[1]: https://www.vagrantup.com/
