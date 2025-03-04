# Awesome Information Retrieval [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![Join the chat at https://gitter.im/awesome-information-retrieval/Lobby](https://badges.gitter.im/awesome-information-retrieval/Lobby.svg)](https://gitter.im/awesome-information-retrieval/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Curated list of information retrieval and web search resources from all around the web.
## Introduction
[Information Retrieval](https://en.wikipedia.org/wiki/Information_retrieval) involves finding relevant information for user queries, ranging from simple domain of database search to complicated aspects of web search (Eg - Google, Bing, Yahoo). Currently, researchers are developing algorithms to address [Information Need](https://en.wikipedia.org/wiki/Information_needs) of user(s), by maximizing [User and Topic Relevance](https://en.wikipedia.org/wiki/Relevance_(information_retrieval)) of retrieved results, while minimizing [Information Overload](https://en.wikipedia.org/wiki/Information_overload) and retrieval time.
## Contributing
Please feel free to send me [pull requests](https://github.com/harpribot/awesome-information-retrieval/pulls) or [email] (mailto:harshal.priyadarshi@utexas.edu) me to add new links. I am very open to suggestions and corrections. Please look at the [contributions guide](contributing.md).

## Contents
 - [Books](#books)
 - [Courses](#courses)
 - [Software](#software)
 - [Datasets](#datasets)
 - [Talks](#talks)
 - [Conferences](#conferences)
 - [Blogs](#blogs)
    - [Interesting Reads](#interesting-reads)

## Books
- [Introduction to Information Retrieval](http://www-nlp.stanford.edu/IR-book/) - C.D. Manning, P. Raghavan, H. Schütze. Cambridge UP, 2008. (First book for getting started with Information Retrieval).
- [Search Engines: Information Retrieval in Practice](http://ciir.cs.umass.edu/downloads/SEIRiP.pdf) - Bruce Croft, Don Metzler, and Trevor Strohman. 2009. (Great book for readers interested in knowing how Search Engines work. The book is very detailed).
- [Modern Information Retrieval](http://people.ischool.berkeley.edu/~hearst/irbook/) - R. Baeza-Yates, B. Ribeiro-Neto. Addison-Wesley, 1999.
- [Information Retrieval in Practice](http://www.search-engines-book.com/) - B. Croft, D. Metzler, T. Strohman. Pearson Education, 2009.
- [Mining the Web: Analysis of Hypertext and Semi Structured Data](http://www.cse.iitb.ac.in/%7Esoumen/mining-the-web/) - S. Chakrabarti. Morgan Kaufmann, 2002.
- [Language Modeling for Information Retrieval](http://www.springer.com/prod/b/1-4020-1216-0?referer=www.wkap.nl) - W.B. Croft, J. Lafferty. Springer, 2003. (Handles Language Modeling aspect of Information Retrieval. It also extensively details probabilistic perspective in this domain, which is interesting).
- [Information Retrieval: A Survey](http://www.csee.umbc.edu/cadip/readings/IR.report.120600.book.pdf) - Ed Greengrass, 2000. (Comprehensive survey of Conventional Information Retrieval, before Deep Learning era).
- [Introduction to  Modern Information Retrieval]( https://www.amazon.com/Introduction-Modern-Information-Retrieval-Third/dp/185604694X) - G.G. Chowdhury. Neal-Schuman, 2003. (Intended for students of library and information studies).
- [Text Information Retrieval Systems](https://www.amazon.com/Information-Retrieval-Systems-Library-Hardcover/dp/0123694124) - C.T. Meadow, B.R. Boyce, D.H. Kraft, C.L.  Barry. Academic Press, 2007 (library/information science  perspective).


## Courses
- [INF384H / CS395T / INF350E: Concepts of Information Retrieval (and Web Search)](http://courses.ischool.utexas.edu/Lease_Matt/2016/Fall/INF384H/) - Matthew Lease (University of Texas at Austin).
- [CS 276 / LING 286: Information Retrieval and Web Search](http://web.stanford.edu/class/cs276/) - Chris Manning and Pandu Nayak (Stanford University).
- [CS 371R: Information Retrieval and Web Search](https://www.cs.utexas.edu/~mooney/ir-course/) - Raymond J. Mooney (University of Texas at Austin).
- [CS 172: Introduction to Information Retrieval](http://www.cs.ucr.edu/~vagelis/classes/CS172/) - Vagelis Hristidis (University of California - Riverside).
- [SIMS 240: Principles of Information Retrieval](http://www2.sims.berkeley.edu/academics/courses/is240/s06/) - Ray R. Larson (UC berkeley).
- [11-442 / 11-642: Search Engines](http://boston.lti.cs.cmu.edu/classes/11-642/) - Jamie Callan (CMU).
- [600.466: Information Retrieval and Web Agents](http://www.cs.jhu.edu/%7Eyarowsky/cs466.html) - David Yarowsky (John Hopkins University).
- [CS 435: Information Retrieval, Discovery, and Delivery](http://www.cs.princeton.edu/courses/archive/spring06/cos435/) - Andrea LaPaugh (Princeton University).
- [Information Retrieval and Data Mining](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/teaching/winter-semester-201516/information-retrieval-and-data-mining/) - Dr. Jilles Vreeken , Prof. Dr. Gerhard Weikum (MPI).
- [Coursera - Text Retrieval and Search Engines](https://www.coursera.org/learn/text-retrieval) -  Prof. ChengXiang Zhai (University of Illinois at Urbana-Champaign).

## Software
- [Apache Lucene](http://lucene.apache.org/core/) - Open Source Search Engine that can be used to test Information Retrieval Algorithm. Twitter uses this core for its real-time search.
- [The Lemur Project](http://www.lemurproject.org) - The Lemur Project develops search engines, browser toolbars, text analysis tools, and data resources that support research and development of information retrieval and text mining software.
  - [Indri Search Engine](http://www.lemurproject.org/indri.php) - Another Open Source Search Engine competitor of Apache Lucene.
  - [Lemur Toolkit](http://www.lemurproject.org/lemur.php) - Open Source Toolkit for research in Language Modeling, filtering and categorization.
- [TopK](https://www.topk.io/) - serverless, cloud-native, document database built for powering search applications. Native support for both vector search and keyword search (BM25-style) in a single, unified system. Soon to support document transformation, query understanding, adaptive ranking.

## Datasets
#### Standard IR Collections
- [DBPedia](http://wiki.dbpedia.org/Downloads2015-10) - Linked data web.
- [Cranfield Collections](http://ir.dcs.gla.ac.uk/resources/test_collections/cran/) - This is one of the first collections in IR domain, however the dataset is too small for any statistical significance analysis, but is nevertheless suitable for pilot runs.
- [TREC Collections](http://trec.nist.gov/data.html) - TREC is the benchmark dataset used by most IR and Web search algorithms. It has several tracks, each of which consists of dataset to test for a specific task. The tracks along with suggested use-case are:
  - [Blog](http://trec.nist.gov/data/blog.html) - Explore information seeking behavior in the blogosphere.
  - [Chemical IR](http://trec.nist.gov/data/chem-ir.html) - Address challenges in building large chemical testbeds for chemical IR.
  - [Clinical Decision Support](http://trec.nist.gov/data/clinical.html) - Investigate techniques to link medical cases to information relevant for patient care.
  - [Confusion](http://trec.nist.gov/data/confusion.html) - Study [Known Item Searching](http://trec.nist.gov/data/confusion/t5confusion.ps) problem.
  - [Contextual Suggestion](http://trec.nist.gov/data/context.html) - Investigate search techniques for complex information needs (context and user interests based).
  - [Crowdsourcing](http://trec.nist.gov/data/crowd.html) - Explore crowdsourcing methods for performing and evaluating search.
  - [Enterprise](http://trec.nist.gov/data/enterprise.html) - Study search over the organization data.
  - [Entity](http://trec.nist.gov/data/entity.html) - Perform entity-related search (find entities and their properties) on Web data.
  - [Filtering](http://trec.nist.gov/data/filtering.html) - Binarily decide retrieval of new incoming documents given a stable information need.
  - [Federated Web Search](http://trec.nist.gov/data/federated.html) - Study merge performance for results from various search services.
  - [Genomics](http://trec.nist.gov/data/genomics.html) - Study retrieval efficiency of genomics data and corresponding documentation.
  - [HARD](http://trec.nist.gov/data/hard.html) - Obtain High Accuracy Retrieval from Documents by leveraging searcher's context.
  - [Interactive Track](http://trec.nist.gov/data/interactive.html) - Study user interaction with text retrieval systems.
  - [Knowledge base acceleration](http://trec.nist.gov/data/kba.html) - Study algorithms that improve efficiency of human Knowledge Base.
  - [Legal Track](http://trec.nist.gov/data/legal.html) - Study retrieval systems that have high recall for legal documents use case.
  - [Medical Track](http://trec.nist.gov/data/medical.html) - Explore unstructured search performance over patients record data.
  - [Microblog Track](http://trec.nist.gov/data/microblog.html) - Examine satisfaction of real-time information need for microblogging sites.
  - [Million Query Track](http://trec.nist.gov/data/million.query.html) - Explore ad-hoc retrieval over large set of queries.
  - [Novelty Track](http://trec.nist.gov/data/novelty.html) - Investigate systems' abilities to locate new (non-redundant) information.
  - [Question Answering Track](http://trec.nist.gov/data/qamain.html) - Test systems that scale beyond document retrieval, to retrieve answers to factoid, list and definition type questions.
  - [Relevance Feedback Track](http://trec.nist.gov/data/relevance.feedback.html) - For deep evaluation of relevance feedback processes.
  - [Robust Track](http://trec.nist.gov/data/robust.html) - Study individual topic's effectiveness.
  - [Session Track](http://trec.nist.gov/data/session.html) - Develop methods for measuring multiple-query sessions where information needs drift.
  - [SPAM Track](http://trec.nist.gov/data/spam.html) - Benchmark spam filtering approaches.
  - [Tasks Track](http://trec.nist.gov/data/tasks.html) - Test if systems can induce possible tasks, users might be trying to accomplish for the query.
  - [Temporal Summarization Track](http://trec.nist.gov/data/tempsumm.html) - Develop systems that allow users to efficiently monitor the information associated with an event over time.
  - [Terabyte Track](http://trec.nist.gov/data/terabyte.html) - Test scalability of IR systems to large scale collection.
  - [Web Track](http://trec.nist.gov/data/webmain.html) - Explore information seeking behaviors common in general web search.
- [GOV2 Test Collection](http://ir.dcs.gla.ac.uk/test_collections/gov2-summary.htm) - This is one of the largest Web collection of documents obtained from crawl of government websites by Charlie Clarke and Ian Soboroff, using NIST hardware and network, then formatted by Nick Craswel.
- [NTCIR Test Collection](http://research.nii.ac.jp/ntcir/data/data-en.html) - This is collection of wide variety of dataset ranging from Ad-hoc collection, Chinese IR collection, mobile clickthrough collections to medical collections. The focus of this collection is mostly on east asian languages and cross language information retrieval.
  - [CLIR Test Collections](http://research.nii.ac.jp/ntcir/permission/ntcir-6/perm-en-CLIR.html) - This dataset can be used for cross lingual IR between CJKE (Chinese-Japanese-Korean-English) languages. It is suitable for the following tasks:
    - Multilingual CLIR
    - Bilingual CLIR
    - Single Language CLIR
  - [Cross Language Q&A (CLQA) dataset collection](http://research.nii.ac.jp/ntcir/permission/ntcir-6/perm-en-CLQA.html) - It supports following bi-lingua and mono-lingua:
    - Bi-lingua
      - Japanese to English.
      - Chinese to English.
      - English to Japanese.
      - English to Chinese.
    - Mono-lingua
      - Chinese to Chinese.
      - Japanese to Japanese.
      - English to English.
  - [Advanced Cross Linugal Information Retrieval and Question Answering (ACLIA)](http://research.nii.ac.jp/ntcir/permission/ntcir-8/perm-en-ACLIA.html) - The dataset is used for the task of cross-lingual question answering but the complexity of the task is higher than CLQA dataset.
- [Conference and Labs of the Evaluation Forum (CLEF) dataset](http://www.clef-initiative.eu/dataset/test-collection) - It contains a multi-lingual document collection. The test suite includes:
  - AdHoc - News Test suite.
  - Domain Specific Test Suite - On collections of scientific articles.
  - Question Answering Test Suite.
- [Reuters Corpora](http://trec.nist.gov/data/reuters/reuters.html) - The corpora is now available through NIST. The corpora includes following:
  - RCV1 (Reuter's Corpus Volume 1) - Consists of only English language News stories.
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
- [Extreme Classification: A New Paradigm for Ranking & Recommendation](https://youtu.be/1X71fTx1LKA) - Manik Verma (Microsoft Research)
- [The next web](https://www.ted.com/talks/tim_berners_lee_on_the_next_web) - Tim Berners-Lee (Ted Talk) [Tim Berners-Lee invented the World Wide Web. He leads the World Wide Web Consortium (W3C), overseeing the Web's standards and development].
- [Is Pivot a turning point for web exploration?](https://www.ted.com/talks/gary_flake_is_pivot_a_turning_point_for_web_exploration?utm_source=tedcomshare&utm_medium=referral&utm_campaign=tedspread) - Gary Flake, Technical Fellow at Microsoft (TED Talks).
- [Challenges in Building Large-Scale Information Retrieval Systems](http://videolectures.net/wsdm09_dean_cblirs/) - Jeff Dean (WSDM Conference, 2009).
- [Knowledge-based Information Retrieval with Wikipedia](https://youtu.be/NFCZuzA4cFc) - David Wilne (The University of Waikato, 2008).
- [Music Information Retrieval Using Locality Sensitive Hashing](https://www.youtube.com/watch?v=SghMq1xBJPI&list=PLdktw5AjQqP2gpQNgHRJaSgEkHiaVLfTi&index=24) - Steve Tjoa (RackSpace Developers) [This talk shows that IR is not just text and images].
- [The Functional Web -- The Future of Apps and the Web](https://youtu.be/u6oqr3gMyxk) - Liron Shapira (Box Tech Talk).
- [Information Experience - Solution to Information Overload on Web](https://youtu.be/EnvtsbCfiAI) - Doug Imbruce (Techcrunch Disrupt)[Doug Imbruce is the Founder of Qwiki, Inc, a technology startup in New York, NY, acquired by Yahoo! in 2013].
- [Internet Privacy](https://youtu.be/tnsyhKHalGs) - Dr. Alma Whitten (Google Brussels Tech Talk).


#### Philosophical Talks
- [The moral bias behind your search results](https://www.ted.com/talks/andreas_ekstrom_the_moral_bias_behind_your_search_results) - Andreas Ekström (Swedish Author & Journalist, TED Talk).
- [Beware online "filter bubbles"](https://www.ted.com/talks/eli_pariser_beware_online_filter_bubbles?language=en) - Eli Pariser (Author of the Filter Bubble, TED Talk).
- [Think your email's private? Think again](https://www.ted.com/talks/andy_yen_think_your_email_s_private_think_again) - Andy Yen (CERN, TED Talk) [This talk talks about privacy, which Search Engines intrude into, and how can people protect it].
- [Do we have the right to be forgotten?](https://youtu.be/YO0lbdhF30g) - Michael Douglas [TEDx SouthBank].
- [The case for anonymity online](https://www.ted.com/talks/christopher_m00t_poole_the_case_for_anonymity_online?utm_source=tedcomshare&utm_medium=referral&utm_campaign=tedspread) - Christopher "moot" Poole" (Ted Talks) [Christopher "moot" Poole is founder of 4chan, an online imageboard whose anonymous denizens have spawned the web's most bewildering and influential subculture].

## Conferences
- Web Search and Data Mining Conference - [WSDM](http://www.wsdm-conference.org).
- Special Interests Group on Information Retrieval - [SIGIR](http://sigir.org).
- Text REtrieval Conference - [TREC](http://trec.nist.gov).
- European Conference on Information Retrieval - [ECIR](http://irsg.bcs.org/ecir.php).
- World Wide Web Conference - [WWW](http://www.iw3c2.org).
- Conference on Information and Knowledge Management - [CIKM](http://www.cikmconference.org).
- Forum for Information Retrieval Evaluation - [FIRE](http://fire.irsi.res.in/fire/2016/home).
- Conference and Labs of the Evaluation Forum - [CLEF](http://www.clef-initiative.eu/).
- NII Testsbeds and Community for Information access Research - [NTCIR](http://research.nii.ac.jp/ntcir/index-en.html).

## Blogs
- [Information Retrieval and the Web](http://research.google.com/pubs/InformationRetrievalandtheWeb.html) - Google Research.
- [IR Thoughts](https://irthoughts.wordpress.com) - Dr. Edel Garcia.

#### Interesting Reads 
- [Deep Neural Network Learns to Judge Books by Their Covers](https://www.technologyreview.com/s/602807/deep-neural-network-learns-to-judge-books-by-their-covers/?utm_campaign=socialflow&utm_source=facebook&utm_medium=post) - Information Extraction.
- [Can Deep Learning help solve Deep Learning](http://www.theverge.com/2016/11/7/13551210/ai-deep-learning-lip-reading-accuracy-oxford) - Information Retrieval from Lip Reading.
- [To reduce biases in machine learning start with openly discussing the problem](https://enterprisersproject.com/article/2016/9/reduce-biases-machine-learning-start-openly-discussing-problem?sc_cid=70160000000q8YTAAY) - Bias in Relevance.
- [Whoa, Google’s AI Is Really Good at Pictionary](https://www.wired.com/2016/11/woah-googles-ai-really-good-pictionary/) - Sketch-based search.
- [Neural Network Learns to Identify Criminals by Their Faces](https://www.technologyreview.com/s/602955/neural-network-learns-to-identify-criminals-by-their-faces/?utm_campaign=socialflow&utm_source=facebook&utm_medium=post) - Information Extraction.


## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Harshal Priyadarshi](http://www.harshalpriyadarshi.com) and all the contributors have waived all copyright and related or neighboring rights to this work.
