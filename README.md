Korean Analysis for ElasticSearch
==================================

The Korean Analysis plugin integrates Lucene Korean analysis module into elasticsearch.

In order to install the plugin, simply run: 
2.2.1
`bin/plugin install https://github.com/mckennajp/elasticsearch-analysis-korean/releases/download/2.2.1/elasticsearch-analysis-korean-2.2.1.zip`

2.1.1
`bin/plugin install https://github.com/mckennajp/elasticsearch-analysis-korean/releases/download/2.1.1/elasticsearch-analysis-korean-2.1.1.zip`


Or you can clone this git repository, set correct version, build and just copy the jar file to `plugins/analysis-korean/` directory.

    --------------------------------------------------
    | Korean Analysis Plugin      | ElasticSearch    |
    --------------------------------------------------
    | master                      | 2.x -> master    |
    --------------------------------------------------
    | 1.3.0                       | 0.90.1           |
    --------------------------------------------------
    | 1.2.0                       | 0.90.0           |
    --------------------------------------------------
    | 1.1.0                       | 0.19.9           |
    --------------------------------------------------
    | 1.0.0                       | 0.19.2           |
    --------------------------------------------------

The plugin includes the `kr_analyzer` analyzer, `kr_tokenizer` tokenizer, and `kr_filter` token filter.


Lucene Korean Analysis Module
==============================

http://cafe.naver.com/korlucene
