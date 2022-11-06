# elasticsearch-rest-high-level-client-7.17

Documentation


https://www.elastic.co/guide/en/elasticsearch/client/java-api/current/java-api.html


While congfig. of elasticSearch client make sure you use this..

    public static RestHighLevelClient create() {
        return new RestHighLevelClient(RestClient.builder(
                new HttpHost(elasticSearchHost, elasticSearchPort, elasticSearchScheme)
        ));
    }
