datemath
========

Date math evaluator. [godoc](http://godoc.org/github.com/lytics/datemath)

Based on ElasticSearch's date math:

* [docs](http://www.elasticsearch.org/guide/en/elasticsearch/reference/current/mapping-date-format.html#date-math)
* [code](https://github.com/elasticsearch/elasticsearch/blob/master/src/main/java/org/elasticsearch/common/joda/DateMathParser.java)

Syntax
------

```
[ operator ] [ number ] [ unit ]
```
 ``operator`` is either `+` or `-`. ``number`` must be an integer. The units
supported are:

* ``y`` (year)
* ``M`` (month)
* ``w`` (week)
* ``d`` (date)
* ``h`` (hour)
* ``m`` (minute)
* ``s`` (second)
