# German-NLP

Curated list of open-access/open-source/off-the-shelf resources and tools developed with a particular focus on German [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Resources and tools which can be used either off-the-shelf or with minor adjustments and which are currently maintained are primarily chosen for this list. It is deliberately biased in terms of usability and user-friendliness.

Pull requests and suggestions are welcome! See [contributing guidelines](contributing.md).


## Table of Contents

- [Corpora](#Corpora)
   - [General-purpose](#General-purpose)
   - [Historical](#Historical)
   - [Specialized](#Specialized)
   - [Lists](#Lists)
   - [Data acquisition](#Data-acquisition)
- [Generic resources](#Generic-resources)
   - [Frameworks](#Frameworks)
   - [Treebanks](#Treebanks)
   - [Annotation](#Annotation)
   - [Standards](#Standards)
- [Linguistic processing](#Linguistic-processing)
   - [Tokenization](#Tokenization)
   - [Stemming](#Stemming)
   - [Lemmatization](#Lemmatization)
   - [Morphological analysis](#Morphological-analysis)
   - [Normalization](#Normalization)
   - [POS-tagging](#POS-tagging)
   - [Syntactical parsing](#Syntactical-parsing)
   - [Named Entity Recognition](#Named-Entity-Recognition)
   - [Industry/Applications](#industryapplications)
   - [Evaluation](#Evaluation)
- [Semantic analysis](#Semantic-analysis)
   - [Datasets](#Datasets)
   - [Word embeddings and senses](#Word-embeddings-and-senses)
   - [Sentiment analysis datasets / polarity clues](#sentiment-analysis-datasets--polarity-clues)
   - [Sentiment detection](#Sentiment-detection)
   - [GermEval](#GermEval)
   - [Coreference resolution](#Coreference-resolution)
   - [Summarization](#Summarization)
   - [Psycholinguistics](#Psycholinguistics)
- [Speech NLP](#Speech-NLP)
- [Machine Translation](#Machine-Translation)
- [Teaching resources and tutorials](#Teaching-resources-and-tutorials)
- [More lists](#More-lists)
   - [German](#German)
   - [General](#General)
   - [Comparable lists](#Comparable-lists)
   - [Larger institutional GitHub groups](#Larger-institutional-GitHub-groups)


## Corpora

### General-purpose

* [Araneum Germanicum](http://aranea.juls.savba.sk/aranea_about/_germanicum.html)
* [COW](http://corporafromtheweb.org/category/corpora/german/)
* [Digitales Wörterbuch der deutschen Sprache (DWDS)](https://dwds.de)
* [IDS Corpora](http://www1.ids-mannheim.de/kl/projekte/korpora)
* [Leipzig Corpora Collection](http://wortschatz.uni-leipzig.de/en/download/)
* [SdeWaC](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/sdewac.en.html)


### Historical

* [Deutsches Textarchiv](https://deutschestextarchiv.de/)
* [Elektronische Texte (Thomas Gloning)](http://www.staff.uni-giessen.de/gloning/etexte.htm)
* [German Drama Corpus](https://github.com/dracor-org/gerdracor)
* [Referenzkorpus Mittelhochdeutsch (1050-1350)](https://www.ruhr-uni-bochum.de/wegera/rem/index.htm)
* [Referenzkorpus Mittelniederdeutsch/Niederrheinisch (1200-1650)](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/text-corpus:ren-0.6)
* [Referenzkorpus Frühneuhochdeutsch (1350-1650)](https://www.ruhr-uni-bochum.de/wegera/ref/index.htm)


### Specialized

* [arg-microtexts](http://angcl.ling.uni-potsdam.de/resources/argmicro.html)
* [auto-hMDS (multi-document summarization)](https://github.com/AIPHES/auto-hMDS)
* [Dortmunder Chat Korpus](http://www.chatkorpus.tu-dortmund.de/)
* [German Political Speeches Corpus](http://purl.org/corpus/german-speeches)
* [GermaParl (Bundestag)](https://github.com/PolMine/GermaParlTEI)
* [One Million Posts Corpus](https://ofai.github.io/million-post-corpus/)
* [Open Speech Data Corpus](http://voxforge.org/home/forums/other-languages/german/open-speech-data-corpus-for-german)
* [Potsdam Commentary Corpus (PCC)](http://angcl.ling.uni-potsdam.de/resources/pcc.html)
* [TTLab StadtWiki Corpus](https://vlo.clarin.eu/?7&fq=collection:CEDIFOR.Corpus.StadtWikis&fqType=collection:or)


#### Swiss German

* [ArchiMob Corpus](https://www.spur.uzh.ch/en/departments/research/textgroup/ArchiMob.html)
* [NOAH's Corpus of Swiss German Dialects](http://kitt.cl.uzh.ch/kitt/noah/NOAHsCorpusOfSwissGermanDialects_Release2.1.zip)
* [SpinningBytes Swiss German Sentiment Corpus](https://github.com/spinningbytes/SB-CH)
* [Swiss SMS Corpus](http://www.sms4science.ch/Main/WebHome)


#### Learner and Error Corpora

* [C-WEP](http://lingured.info/linguistic-resources/cwep/)
* [Falko](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/forschung/falko)
* [OpinionSpam](https://github.com/hdaSprachtechnologie/OpinionSpam)


#### Word lists

* [DeReWo](http://www1.ids-mannheim.de/kl/projekte/methoden/derewo.html)
* [DiMLex (lexicon of German discourse markers)](https://github.com/discourse-lab/dimlex)
* [German Compound Database](https://www.webcorpora.org/opendata/gecodb/)
* [German nouns from Wiktionary](https://github.com/gambolputty/german-nouns)
* [German Wiktionary Lexicon Graph](https://vlo.clarin.eu/record?10&count=2&docId=21.11105_47_0000-000B-D244-B&fq=collection:CEDIFOR.Lexicon&fqType=collection:or&index=0)
* [German word list for GNU Aspell](https://sourceforge.net/projects/germandict/files/)
* [OpenThesaurus](https://www.openthesaurus.de/about/download)


### Lists

* [CLARIN-D list](https://www.clarin-d.net/en/corpora)
* [Corpora at the IMS](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/index.en.html)
* [CorpusExplorer's list of corpora](https://notes.jan-oliver-ruediger.de/korpora/)
* [Korpora am IMS](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/index.html)
* [Parallel corpora (see below)](#parallel-corpora)
* [Treebanks (see below)](#treebanks)
* [ZAS list](http://www.zas.gwz-berlin.de/katalog00100.html?&L=1)


### Data acquisition

* [bundestag](https://github.com/bundestag)
* [DKPro C4Corpus](https://github.com/dkpro/dkpro-c4corpus)
* [german-reddit](https://github.com/adbar/german-reddit)
* [news-crawler](https://github.com/theSoenke/news-crawler)


## Generic resources

### Frameworks

* [CLARIN-D web tools](https://www.clarin-d.net/en/analysing)
* [CorpusExplorer](http://notes.jan-oliver-ruediger.de/software/corpusexplorer-overview/)
* [DKPro Core](https://dkpro.github.io/dkpro-core)
* [DKPro Similarity](https://dkpro.github.io/dkpro-similarity)
* [DKPro Text Classification (TC)](https://dkpro.github.io/dkpro-tc)
* [DKPro Word Sense Disambiguation (WSD)](https://dkpro.github.io/dkpro-wsd)
* [flair](https://github.com/zalandoresearch/flair)
* [ixa pipes](http://ixa2.si.ehu.es/ixa-pipes/)
* [Mate Tools](http://www.ims.uni-stuttgart.de/forschung/ressourcen/werkzeuge/matetools.en.html)
* [spaCy](https://github.com/explosion/spaCy)
* [Stanford CoreNLP](https://github.com/stanfordnlp/CoreNLP)
* [textblob-de](https://github.com/markuskiller/textblob-de)
* [TextImager](https://vlo.clarin.eu/record?4&count=1&docId=21.11105_47_0000-000B-CAE6-E&index=0&q=TextImager)


### Treebanks

* [German Universal Dependency Treebank](https://github.com/UniversalDependencies/UD_German-GSD/tree/master)
* [Hamburg Dependency Treebank](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/treebank:hdt)
* [NEGRA](http://www.coli.uni-saarland.de/projects/sfb378/negra-corpus/)
* [TIGER Corpus](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/tiger.en.html)
   * [SALSA (role semantic annotation)](http://www.coli.uni-saarland.de/projects/salsa/corpus/)
   * [Tiger2Dep (dependency parses)](http://www.ims.uni-stuttgart.de/forschung/ressourcen/werkzeuge/Tiger2Dep.en.html)
* [TGermaCorp (literary texts)](https://vlo.clarin.eu/record?1&count=2&docId=21.11105_47_0000-000B-D4D9-1&index=0&q=TGermaCorp)
* [TüBa-D/Z](http://www.sfs.uni-tuebingen.de/en/ascl/resources/corpora/tueba-dz.html)


### Annotation

* [cora](https://github.com/comphist/cora)
* [corpus-tools.org (HU Berlin)](http://corpus-tools.org/home/)
* [INCEpTION](https://inception-project.github.io/)
* [WebAnno](https://webanno.github.io/webanno/)


### Standards

* [DTA Basisformat](http://www.deutschestextarchiv.de/doku/basisformat/)
* [ISO TC 37 SC 4](https://www.iso.org/committee/297592.html)
* [UIMA](http://docs.oasis-open.org/uima/v1.0/os/uima-spec-os.html)
* [UIMA CAS XMI](https://uima.apache.org/d/uimaj-current/references.html#ugr.ref.xmi)


## Linguistic processing

### Tokenization

* [JTok](https://github.com/DFKI-MLT/JTok)
* [SoMaJo](https://github.com/tsproisl/SoMaJo)
* [waste](http://kaskade.dwds.de/waste/)
* [german-abbreviations](https://github.com/jfilter/german-abbreviations)


### Stemming

* [CISTEM](https://github.com/LeonieWeissweiler/CISTEM)
* [Snowball](http://snowballstem.org)


### Lemmatization

* [germalemma](https://github.com/WZBSocialScienceCenter/germalemma)
* [IWNLP](https://github.com/Liebeck/IWNLP)
   * [spacy-iwnlp](https://github.com/Liebeck/spacy-iwnlp)


### Morphological analysis

* [CharSplit](https://github.com/dtuggener/CharSplit)
* [DEMorphy](https://github.com/DuyguA/DEMorphy)
* [Durm Lemmatizer](http://www.semanticsoftware.info/durm-german-lemmatizer)
* [HypheNN-de](https://github.com/msiemens/HypheNN-de)
* [jwordsplitter](https://github.com/danielnaber/jwordsplitter)
* [MarMoT](http://cistern.cis.lmu.de/marmot/)
* [Morphy](http://morphy.wolfganglezius.de/)
* [morphisto](https://code.google.com/archive/p/morphisto/)
* [SECOS (unsupervised compound splitter)](https://github.com/riedlma/SECOS)
* [SFST](http://www.cis.uni-muenchen.de/~schmid/tools/SFST/)
* [SMOR](http://www.cis.uni-muenchen.de/~schmid/tools/SMOR/)


### Normalization

* [CAB](http://www.deutschestextarchiv.de/cab)
* [norma](https://github.com/comphist/norma)


### POS-tagging

* [clevertagger](https://github.com/rsennrich/clevertagger)
* [hunpos](https://github.com/mivoq/hunpos)
* [moot](http://kaskade.dwds.de/~jurish/projects/moot)
* [pattern.de](https://www.clips.uantwerpen.be/pages/pattern-de)
* [RFTagger](http://www.cis.uni-muenchen.de/~schmid/tools/RFTagger/)
* [SoMeWeTa](https://github.com/tsproisl/SoMeWeTa)
* [TnT](http://www.coli.uni-saarland.de/~thorsten/tnt/)
* [TreeTagger](http://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/)


### Syntactical parsing

* [Berkeley Parser](https://github.com/slavpetrov/berkeleyparser)
* [BitPar](http://www.cis.uni-muenchen.de/~schmid/tools/BitPar/)
* [CDG](https://nats-www.informatik.uni-hamburg.de/CDG/DownloadPage)
   * [jwcdg](https://gitlab.com/nats/jwcdg)
* [ParZu](https://github.com/rsennrich/parzu)
* [Stanford Parser](https://nlp.stanford.edu/software/lex-parser.shtml)


### Named Entity Recognition

* [AmbiverseNLU KnowNER](https://github.com/ambiverse-nlu/ambiverse-nlu)
* [flair](https://github.com/zalandoresearch/flair)
* [GermaNER](https://github.com/tudarmstadt-lt/GermaNER)
* [LSTM+CRF+FastText with models for (historic) German](https://github.com/riedlma/sequence_tagging)
* [microNER](https://uhh-lt.github.io/microNER/)
* [ner-corpora](https://github.com/EuropeanaNewspapers/ner-corpora)
* [(Faruqui & Pado 2010) Components and evaluation data](https://nlpado.de/~sebastian/software/ner_german.shtml)


### Industry/Applications

* [German Decompounder for Apache Lucene / Apache Solr / Elasticsearch](https://github.com/uschindler/german-decompounder)
* [LanguageTool](https://languagetool.org)


### Evaluation

* [Evaluation of different NLP toolkits](https://github.com/goerlitz/nlp-german)
* [DKPro Statistics](https://dkpro.github.io/dkpro-statistics)


## Semantic analysis

### Datasets

* [Complex Word Identification (DE, EN, ES, FR)](https://sites.google.com/view/cwisharedtask2018/home)
* [Distributional thesauri (includes German)](https://sourceforge.net/projects/jobimtext/files/data/models/)
* [Lexical Chains](https://www.inf.uni-hamburg.de/en/inst/ab/lt/resources/data/lexical-chains.html)
* [schulteimwalde.de/resources.html](http://www.schulteimwalde.de/resources.html)
* [Semantic Relations in Context](https://www.inf.uni-hamburg.de/en/inst/ab/lt/resources/data/semreldata.html)
* [UKP Darmstadt data list](https://www.informatik.tu-darmstadt.de/ukp/research_6/data/index.en.jsp)


### Word embeddings and senses

* [disco (semantic similarity)](https://github.com/linguatools/disco)
* [GermaNet](http://www.sfs.uni-tuebingen.de/GermaNet/)
   * [pygermanet](https://github.com/wroberts/pygermanet)
* [german2vec](https://github.com/Bachfischer/german2vec)
* [GermanWordEmbeddings](https://github.com/devmount/GermanWordEmbeddings)
* [Open German WordNet](https://github.com/hdaSprachtechnologie/odenet)
* [sensegram](https://github.com/tudarmstadt-lt/sensegram)
* [SpinningBytes word embeddings (tweets)](https://www.spinningbytes.com/resources/wordembeddings/)
* [UBY Linked Lexical Resource](https://dkpro.github.io/dkpro-uby/)


### Sentiment analysis datasets / polarity clues

* [GermanPolarityClues](http://www.ulliwaltinger.de/sentiment/)
* [HeiST – Heidelberg Sentiment Treebank](http://www.cl.uni-heidelberg.de/~versley/HeiST/)
* [Potsdam Twitter Sentiment Corpus (PotTS)](https://github.com/WladimirSidorenko/PotTS)
* [Sentiment Lexicon (Univ. Zurich)](http://bics.sentimental.li/files/8614/2462/8150/german.lex)
* [SentimentWortschatz](http://wortschatz.uni-leipzig.de/en/download/)
* [SpinningBytes Swiss German Sentiment Corpus](https://github.com/spinningbytes/SB-CH)


### Sentiment detection

* [LT-ABSA: Aspect-based Sentiment Analysis](https://www.inf.uni-hamburg.de/en/inst/ab/lt/resources/software/lt-absa.html)
* [spacy-sentiws](https://github.com/Liebeck/spacy-sentiws)


### GermEval (category to improve)

* [Official GermEval tools list](https://projects.fzai.h-da.de/iggsa/resources-tools-and-literature/)
* [GermEval 2015 data (Lexical Substitution)](https://sites.google.com/site/germeval2015/)
* [Germeval Task 2017](https://sites.google.com/view/germeval2017-absa/home)
* [GermEval-2018 data](https://github.com/uds-lsv/GermEval-2018-Data)
* [germeval-rug](https://github.com/malvinanissim/germeval-rug)
* [IWG_hatespeech_public](https://github.com/UCSM-DUE/IWG_hatespeech_public)
* [jpadillamontani/germeval2018](https://github.com/jpadillamontani/germeval2018)
* [uhh-lt/GermEval2017-Baseline](https://github.com/uhh-lt/GermEval2017-Baseline)
* [UKP embeddings for GermEval 2017](https://github.com/UKPLab/germeval2017-sentiment-detection)


### Discourse

* [CorZu (coreference resolution)](https://github.com/dtuggener/CorZu)
* [Discourse Segmenter](https://github.com/WladimirSidorenko/DiscourseSegmenter)
* [Frame Identification](https://github.com/UKPLab/naacl18-multimodal-frame-identification)
* [PropS-DE (proposition structures)](https://github.com/UKPLab/props-de)


### Summarization

* [Tools and corpora for summarization of German texts](https://github.com/AIPHES)


### Psycholinguistics

* [Noun Associations for German](http://www.psycholing.es.uni-tuebingen.de/nag/index.php)


## Speech NLP

* [Archiv für gesprochenes Deutsch](http://agd.ids-mannheim.de/korpus_index.shtml)
* [BAS ressources](http://www.bas.uni-muenchen.de/Bas/BasSpeechresourceseng.html)
* [Bochumer Korpus der gesprochenen Sprache im Ruhrgebiet](https://www.ruhr-uni-bochum.de/kgsr/)
* [Database for Spoken German (IDS Mannheim)](https://dgd.ids-mannheim.de/dgd/pragdb.dgd_extern.welcome)
* [(D)iscourse (I)nformation (R)adio (N)ews (D)atabase for (L)inguistic Analysis ](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/dirndl.en.html)
* [Hamburger Zentrum für Sprachkorpora](https://corpora.uni-hamburg.de/hzsk/)
* [kaldi-tuda-de](https://github.com/uhh-lt/kaldi-tuda-de)


## Machine Translation

* []()


#### Parallel corpora

* [Linguatools Webcrawl German-English 2015](http://linguatools.org/tools/corpora/webcrawl-parallel-corpus-german-english-2015/)
* [MuchMore Springer Bilingual Corpus](http://muchmore.dfki.de/resources1.htm)



## Teaching resources and tutorials

* [bubenhofer.com/korpuslinguistik/kurs/](http://www.bubenhofer.com/korpuslinguistik/kurs/)
* [CorpusExplorer v2.0 – Seminartauglich in einem halben Tag](https://lernen-mit.jan-oliver-ruediger.de/)
* [deeplearning4nlp-tutorial](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* Uni Zürich: Sprachtechnologie in den Digital Humanities – MOOC [Youtube](https://www.youtube.com/channel/UChb3Rd5vo3WEgMSy99VInaw) & [Coursera](http://www.coursera.org/learn/digital-humanities)


## More lists

### German

* [CLARIN VLO (DE+public)](https://vlo.clarin.eu/search?2&fq=languageCode:code:deu&fq=licenseType:PUB)
* [computerlinguistik.org](http://www.computerlinguistik.org/portal/portal.html?s=Ressourcen)
* [LRE Map](http://lremap.elra.info/?&selected_facets=languageFilter_exact%3AGerman)
* [MetaShare Language Resources](http://metashare.ilsp.gr:8080/repository/search/?q=&selected_facets=languageNameFilter_exact%3AGerman)
* [Peter Kolb's list](http://www.ling.uni-potsdam.de/~kolb/nlp-tools.html)
* [Swiss German Language Processing](http://kitt.cl.uzh.ch/kitt/noah/resources)


### General

* GitHub topics [corpus-linguistics](https://github.com/topics/corpus-linguistics) & [nlp](https://github.com/topics/nlp)
* [nlp-datasets](https://github.com/niderhoff/nlp-datasets)
* [NLP-progress](https://github.com/sebastianruder/NLP-progress)
* [/r/LanguageTechnology/](https://www.reddit.com/r/LanguageTechnology/)


### Comparable lists

* [awesome-nlp](https://github.com/keon/awesome-nlp)
* [Awesome Community-Curated NLP List](https://github.com/alvations/awesome-community-curated-nlp)
* [awesome-chinese-nlp](https://github.com/crownpku/Awesome-Chinese-NLP)
* [awesome-hungarian-nlp](https://github.com/oroszgy/awesome-hungarian-nlp)
* [Indonesian NLP](https://github.com/kmkurn/id-nlp-resource)
* [awesome-spanish-nlp](https://github.com/dav009/awesome-spanish-nlp)
* [M. Weisser's list of NLP/Computational Linguistics Resources](http://martinweisser.org/corpora_site/comp_ling_resources.html)
* [NLP tools (Saarland University)](http://www.coli.uni-saarland.de/~csporled/page.php?id=tools)
* [W. Roberts' Computational Linguistics Links](http://amor.cms.hu-berlin.de/~robertsw/links.html)


### Larger institutional GitHub groups

* [Language Technology Group, Universität Hamburg](https://github.com/uhh-lt/)
* [Ubiquitous Knowledge Processing Lab, TU Darmstadt](https://github.com/ukplab)


## License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)
