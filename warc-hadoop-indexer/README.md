WARC Hadoop Indexer
===================

This project contains those classes used to run text-extraction jobs on Hadoop using Tika. (W)ARC records are mapped to SolrInputDocument (WritableSolrRecord) before being passed directly to a SolrServer in the reduce phase.

Additional bespoke metadata are too added from the Web Curator Tool (WctEnricher), per ID, in the reduce stage.

