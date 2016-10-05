# Flinking With Word2Vec

Check out my [implementation](https://github.com/kalmanchapman/flink/blob/word2vec/flink-libraries/flink-ml/src/main/scala/org/apache/flink/ml/optimization/ContextEmbedder.scala), [presentation](http://bitly.com/flinkingword2vec) and [explanation](https://kalmanchapman.github.io/flinking) 

While a fellow at Insight Data Science, I came across a [feature request](https://issues.apache.org/jira/browse/FLINK-2094) for an implementation of Word2Vec for the [Flink distributed processing platform](http://flink.apache.org/). I hadn't really done much with Flink before, but I had played around with the [Word2Vec implementation from the Spark framework](http://spark.apache.org/docs/latest/api/scala/index.html#org.apache.spark.mllib.feature.Word2Vec) - and as an intrepid engineer with a background in linguistics and an interest in feature learning technologies, this was a perfect reason to dive deeply into understanding this fascinating learning algorithm in the context of a distributed compute framework.
