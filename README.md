# PCR Analytics

Producer-Consumer Ratio is a threat hunting technique whereby a node's behaviour may be profiled to be that of either producer, consumer or normal.  Mathematically, this can be expressed as 

$$ PCR = \frac{SrcAppBytes - DstAppBytes}{SrcAppBytes + DstAppBytes} $$

A positive PCR value indicates data being pushed and conversely a negative PCR value indicates data being pulled.

#

## Notebook Scope
This notebook is an attempt at:
* Implementing PCR Analysis on a variety of data sources.
* Produce repeatable, and easily digestable visualisations to accompany PCR.

In future, a PCR may be calculated across a 10 minute sample size and attached to timeseries data.  This added dimension would allow us to profile behaviour based on time and enable timeseries analysis.

