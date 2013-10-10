Morfologik (Polish) Analysis for ElasticSearch
==================================

The Morfologik (Polish) Analysis plugin integrates Lucene Morfologik (polish) analysis module into elasticsearch.

Installation
------------

Simply run at the root of your ElasticSearch according to the version you use:

- v0.90+
  `bin/plugin -install com.github.chytreg/elasticsearch-analysis-morfologik/2.0.0`

- v0.20.2+
   `bin/plugin -install com.github.chytreg/elasticsearch-analysis-morfologik/1.0.0`

- v0.20.1 and below:
   `bin/plugin -url http://bit.ly/17nO1Pq install analysis-morfologik`
	
In order to declare this plugin as a dependency, add the following to your `pom.xml`:

	<dependency>
	    <groupId>com.github.chytreg</groupId>
	    <artifactId>elasticsearch-analysis-morfologik</artifactId>
	    <version>$PLUGIN_VERSION</version>
	</dependency>


The plugin includes `morfologik` analyzer and `morfologik_stem` token filter.

License
-------

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2009-2012 Shay Banon and ElasticSearch <http://www.elasticsearch.org>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
