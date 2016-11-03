## Awesome Information Retrieval [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![Join the chat at https://gitter.im/awesome-information-retrieval/Lobby](https://badges.gitter.im/awesome-information-retrieval/Lobby.svg)](https://gitter.im/awesome-information-retrieval/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
* A curated list of information retrieval and web search resources from all around the web.

## Contributing
please feel free to send me [pull requests](https://github.com/harpribot/awesome-information-retrieval/pulls) or email(harshal.priyadarshi@utexas.edu) to add new links. I am very open to suggestions and corrections.

## Table of Contents
 - [Books](#books)
 - [Courses](#courses)
 - [Software](#software)
 - [Datasets](#datasets)
 - [Talks](#talks)
 - [Conferences](#conference)
 - [Blogs](#blogs)

## Books
- [Introduction to Information Retrieval](http://www-nlp.stanford.edu/IR-book/) - C.D. Manning, P. Raghavan, H. Schütze. Cambridge UP, 2008
- [Search Engines: Information Retrieval in Practice](http://ciir.cs.umass.edu/downloads/SEIRiP.pdf) - Bruce Croft, Don Metzler, and Trevor Strohman. 2009
- [Modern Information Retrieval](http://people.ischool.berkeley.edu/~hearst/irbook/) - R. Baeza-Yates, B. Ribeiro-Neto. Addison-Wesley, 1999
- [Information Retrieval in Practice](http://www.search-engines-book.com/) - B. Croft, D. Metzler, T. Strohman. Pearson Education, 2009
- [Mining the Web: Analysis of Hypertext and Semi Structured Data](http://www.cse.iitb.ac.in/%7Esoumen/mining-the-web/) - S. Chakrabarti. Morgan Kaufmann, 2002
- [Language Modeling for Information Retrieval](http://www.springer.com/prod/b/1-4020-1216-0?referer=www.wkap.nl) - W.B. Croft, J. Lafferty. Springer, 2003
- [Information Retrieval: A Survey](http://www.csee.umbc.edu/cadip/readings/IR.report.120600.book.pdf) - Ed Greengrass, 2000

## Courses
- [INF384H / CS395T / INF350E: Concepts of Information Retrieval (and Web Search)](http://courses.ischool.utexas.edu/Lease_Matt/2016/Fall/INF384H/) - Matthew Lease (University of Texas at Austin)
- [CS 276 / LING 286: Information Retrieval and Web Search](http://web.stanford.edu/class/cs276/) - Chris Manning and Pandu Nayak (Stanford University)
- [CS 371R: Information Retrieval and Web Search](https://www.cs.utexas.edu/~mooney/ir-course/) - Raymond J. Mooney (University of Texas at Austin)
- [CS 172: Introduction to Information Retrieval](http://www.cs.ucr.edu/~vagelis/classes/CS172/) - Vagelis Hristidis (University of California - Riverside)
- [SIMS 240: Principles of Information Retrieval](http://www2.sims.berkeley.edu/academics/courses/is240/s06/) - Ray R. Larson (UC berkeley)
- [11-442 / 11-642: Search Engines](http://boston.lti.cs.cmu.edu/classes/11-642/) - Jamie Callan (CMU)
- [600.466: Information Retrieval and Web Agents](http://www.cs.jhu.edu/%7Eyarowsky/cs466.html) - David Yarowsky (John Hopkins University)
- [CS 435: Information Retrieval, Discovery, and Delivery](http://www.cs.princeton.edu/courses/archive/spring06/cos435/) - Andrea LaPaugh (Princeton University)
- [Information Retrieval and Data Mining](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/teaching/winter-semester-201516/information-retrieval-and-data-mining/) - Dr. Jilles Vreeken , Prof. Dr. Gerhard Weikum (MPI)

## Software
- [Apache Lucene](http://lucene.apache.org/core/)
- [The Lemur Project](http://www.lemurproject.org)
  - [Indri](http://www.lemurproject.org/indri.php)

## Datasets
#### Standard IR Collections
- [Cranfield Collections](http://ir.dcs.gla.ac.uk/resources/test_collections/cran/) - This is one of the first collections in IR domain, however the dataset is too small for any statistical significane analysis, but is nevertheless suitable for pilot runs.
- [TREC Collections](http://trec.nist.gov/data.html) - TREC is the benchmark dataset used by most IR and Web search algorithm. It has several tracks, each of which consists dataset to test for a specific task. The tracks are:
  - [Blog](http://trec.nist.gov/data/blog.html)
  - [Chemical IR](http://trec.nist.gov/data/chem-ir.html)
  - [Clinical Decision Support](http://trec.nist.gov/data/clinical.html)
  - [Confusion](http://trec.nist.gov/data/confusion.html)
  - [Contextual Suggestion](http://trec.nist.gov/data/context.html)
  - [Crowdsourcing](http://trec.nist.gov/data/crowd.html)
  - [Enterprise](http://trec.nist.gov/data/enterprise.html)
  - [Entity](http://trec.nist.gov/data/entity.html)
  - [Filtering](http://trec.nist.gov/data/filtering.html)
  - [Federated Web Search](http://trec.nist.gov/data/federated.html)
  - [Genomics](http://trec.nist.gov/data/genomics.html)
  - [High Accuracy Retrieval from Documents (HARD)](http://trec.nist.gov/data/hard.html)
  - [Interactive Track](http://trec.nist.gov/data/interactive.html)
  - [Knowledge base acceleration](http://trec.nist.gov/data/kba.html)
  - [Legal Track](http://trec.nist.gov/data/legal.html)
  - [Medical Track](http://trec.nist.gov/data/medical.html)
  - [Microblog Track](http://trec.nist.gov/data/microblog.html)
  - [Million Query Track](http://trec.nist.gov/data/million.query.html)
  - [Novelty Track](http://trec.nist.gov/data/novelty.html)
  - [Query Track](http://trec.nist.gov/data/query.html)
  - [Question Answering Track](http://trec.nist.gov/data/qamain.html)
  - [Relevance Feedback Track](http://trec.nist.gov/data/relevance.feedback.html)
  - [Robust Track](http://trec.nist.gov/data/robust.html)
  - [Session Track](http://trec.nist.gov/data/session.html)
  - [SPAM Track](http://trec.nist.gov/data/spam.html)
  - [Spoken Document Retrieval Track](http://www.itl.nist.gov/iad/mig//tests/sdr/)
  - [Tasks Track](http://trec.nist.gov/data/tasks.html)
  - [Temporal Summarization Track](http://trec.nist.gov/data/tempsumm.html)
  - [Terabyte Track](http://trec.nist.gov/data/terabyte.html)
  - [Web Track](http://trec.nist.gov/data/webmain.html)
- [GOV2 Test Collection](http://ir.dcs.gla.ac.uk/test_collections/gov2-summary.htm) - This is one of the largest Web collection of documents obtained from crawl of government websites by Charlie Clarke and Ian Soboroff, using NIST hardware and network, then formatted by Nick Craswel
- [NTCIR Test Collection](http://research.nii.ac.jp/ntcir/data/data-en.html) - This is a collection of wide variety of dataset ranging from adhoc collection, chinese IR collection, mobile clickthrough collections to medical collections. The focus of this collection is mostly on east asian languages and cross language information retrieval.
  - [CLIR Test Collections](http://research.nii.ac.jp/ntcir/permission/ntcir-6/perm-en-CLIR.html) - This dataset can be used for cross lingual IR between CJKE (Chinese-Japanese-Korean-English) languages. It is suitable for the following tasks:
    - Multilingual CLIR
    - Bilingual CLIR
    - Single Language CLIR
  - [Cross Language Q&A (CLQA) dataset collection](http://research.nii.ac.jp/ntcir/permission/ntcir-6/perm-en-CLQA.html) - It supports following bi-lingua and mono-lingua:
    - Bi-lingua
      - Japanese to English
      - Chinese to English
      - English to Japanese
      - English to Chinese
    - Mono-lingua
      - Chinese to Chinese
      - Japanese to Japanese
      - English to English
  - [Advanced Cross Linugal Information Retrieval and Question Answering (ACLIA)](http://research.nii.ac.jp/ntcir/permission/ntcir-8/perm-en-ACLIA.html) - The dataset is used for the task of cross-linugal question answering but the complexity of the task is higher than CLQA dataset.
- [Conference and Labs of the Evaluation Forum (CLEF) dataset](http://www.clef-initiative.eu/dataset/test-collection) - It contains a multi-linugal document collection. The test suite includes:
  - AdHoc - News Test suite
  - Domain Specific Test Suite - On collections of scientific articles
  - Question Answering Test Suite
- [Reuters Corpora](http://trec.nist.gov/data/reuters/reuters.html) - The corpora is now available through NIST. The corpora includes following:
  - RCV1 (Reuter's Corpus Volume 1) - Consists of only English language News stories
  - RCV2 (Reuter's Corpus Volume 2) - Consists of stories in 13 languages (Dutch, French, German, Chinese, Japanese, Russian, Portuguese, Spanish, Latin American Spanish, Italian, Danish, Norwegian, and Swedish). Note that the stories are not parallel.
  - TRC (Thomson Reuters Text Research Collection) - This is a fairly recent corpus consisting of 1,800,370 news stories covering the period from 2008-01-01 00:00:03 to 2009-02-28 23:54:14.
- [20 Newsgroup dataset](https://kdd.ics.uci.edu/databases/20newsgroups/20newsgroups.html) - This data set consists of 20000 newsgroup messages.posts taken from 20 newsgroup topics.
- [English Gigaword Fifth Edition](https://catalog.ldc.upenn.edu/LDC2011T07) -  This data set is a comprehensive archive of English newswire text data including headlines, datelines and articles. 
- [Document Understanding Conference (DUC) datasets](http://www-nlpir.nist.gov/projects/duc/data.html) - Past newswire/paper datasets (DUC 2001 - DUC 2007) are available upon request. 

#### External Curation Links
- [CMU List](http://boston.lti.cs.cmu.edu/callan/Data/#DIR)
- [Stanford List](http://nlp.stanford.edu/IR-book/html/htmledition/standard-test-collections-1.html)
- [University of Tennesse Knoxville](http://web.eecs.utk.edu/research/lsi/corpa.html)


## Talks
#### Technical Talks
- [Challenges in Building Large-Scale Information Retrieval Systems](http://videolectures.net/wsdm09_dean_cblirs/) - Jeff Dean (WSDM Conference, 2009)
- [Knowledge-based Information Retrieval with Wikipedia](https://www.youtube.com/watch?v=NFCZuzA4cFc) - David Wilne (The University of Waikato, 2008)
- [Music Information Retrieval Using Locality Sensitive Hashing](https://www.youtube.com/watch?v=SghMq1xBJPI&list=PLdktw5AjQqP2gpQNgHRJaSgEkHiaVLfTi&index=24) - Steve Tjoa (Rackspace Developers) [This talk shows that IR is not just text and images]

#### Philosophical Talks
- [he moral bias behind your search results](https://www.ted.com/talks/andreas_ekstrom_the_moral_bias_behind_your_search_results) - Andreas Ekström (Swedish Author & Journalist, TED Talk)
- [Beware online "filter bubbles"](https://www.ted.com/talks/eli_pariser_beware_online_filter_bubbles?language=en) - Eli Pariser (Author of the Filter Bubble, TED Talk)
- [Think your email's private? Think again](https://www.ted.com/talks/andy_yen_think_your_email_s_private_think_again) - Andy Yen (CERN, TED Talk) [This talk talks about privacy, which Search Engines intrude into, and how can people protect it]

## Conferences
- Web Search and Data Mining Conference - [WSDM](http://www.wsdm-conference.org)
- Special Interests Group on Information Retrieval - [SIGIR](http://sigir.org)
- Text REtrieval Conference - [TREC](http://trec.nist.gov)
- European Conference on Information Retrieval - [ECIR](http://irsg.bcs.org/ecir.php)
- World Wide Web Conference - [WWW](http://www.iw3c2.org)
- Conference on Information and Knowledge Management[CIKM](http://www.cikmconference.org)

## Blogs
- [Information Retrieval and the Web](http://research.google.com/pubs/InformationRetrievalandtheWeb.html) - Google Research
- [IR Thoughts](https://irthoughts.wordpress.com) - Dr. Edel Garcia

## License
[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Harshal Priyadarshi](http://www.harshalpriyadarshi.com) has waived all copyright and related or neighboring rights to this work.
