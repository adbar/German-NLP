# German-NLP

Curated list of open-access/open-source/off-the-shelf resources and tools developed with a particular focus on German [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Resources and tools which can be used either off-the-shelf or with minor adjustments and which are currently maintained are primarily chosen for this list. It is deliberately biased in terms of usability and user-friendliness.

Pull requests and suggestions are welcome! See [contributing guidelines](contributing.md).


## Table of Contents

- [Text corpora](#Text-corpora)
   - [General-purpose](#General-purpose)
   - [Historical](#Historical)
   - [Specialized](#Specialized)
   - [Word lists](#Word-lists)
   - [Data acquisition](#Data-acquisition)
   - [Lists of corpora](#Lists-of-corpora)
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


## Text corpora

### General-purpose

* [Araneum Germanicum](http://aranea.juls.savba.sk/aranea_about/_germanicum.html)
* [COW](http://corporafromtheweb.org/category/corpora/german/)
* [Digitales Wörterbuch der deutschen Sprache (DWDS)](https://dwds.de)
* [IDS Corpora](http://www1.ids-mannheim.de/kl/projekte/korpora)
* [Leipzig Corpora Collection](http://wortschatz.uni-leipzig.de/en/download/)
* [SdeWaC](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/sdewac.en.html)


### Historical

* [Anselm (14th-16th centuries)](https://www.linguistics.ruhr-uni-bochum.de/anselm/access/index.en.html)
* [Deutsches Textarchiv](https://deutschestextarchiv.de/)
* [Elektronische Texte (Thomas Gloning)](http://www.staff.uni-giessen.de/gloning/etexte.htm)
* [German Drama Corpus (GerDraCor)](https://github.com/dracor-org/gerdracor)
* [German Novels](https://github.com/computationalstylistics/68_german_novels)
* [German Poetry Corpus (DLK)](https://github.com/thomasnikolaushaider/DLK)
* [Lesekorpus Altdeutsch (750-1050)](http://titus.uni-frankfurt.de/lea)
* [LiederCorpus](https://github.com/corpusmusic/liederCorpusAnalysis)
* [Referenzkorpus Altdeutsch (750-1050)](http://www.deutschdiachrondigital.de/)
* [Referenzkorpus Mittelhochdeutsch (1050-1350)](https://www.ruhr-uni-bochum.de/wegera/rem/index.htm)
* [Referenzkorpus Mittelniederdeutsch/Niederrheinisch (1200-1650)](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/text-corpus:ren-0.6)
* [Referenzkorpus Frühneuhochdeutsch (1350-1650)](https://www.ruhr-uni-bochum.de/wegera/ref/index.htm)
* [Thesaurus Indogermanischer Text- und Sprachmaterialien (TITUS)](http://titus.uni-frankfurt.de/indexd.htm?/texte/texte.htm)


### Specialized

* [arg-microtexts](http://angcl.ling.uni-potsdam.de/resources/argmicro.html)
* [auto-hMDS (multi-document summarization)](https://github.com/AIPHES/auto-hMDS)
* [DIRNDL -- (D)iscourse (I)nformation (R)adio (N)ews (D)atabase for (L)inguistic Analysis](https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/dirndl.en.html)
* [Dortmunder Chat Korpus](http://www.chatkorpus.tu-dortmund.de/)
* [Feidegger (Fashion Images and Descriptions)](https://github.com/zalandoresearch/feidegger)
* [Fußballlinguistik](https://fussballlinguistik.de/korpora/)
* [German EUROPARL data w/ NE annotation](https://nlpado.de/~sebastian/software/ner_german.shtml)
* [German Job Reference Corpus](https://github.com/iug-htw/GJRC)
* [German Political Speeches Corpus](http://purl.org/corpus/german-speeches)
* [German Recipes Dataset](https://www.kaggle.com/sterby/german-recipes-dataset)
* [GermaParl (Bundestag)](https://github.com/PolMine/GermaParlTEI)
* [GRAIN corpus -- (G)erman-(RA)dio-(IN)terviews](https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/grain.html)
* [One Million Posts Corpus](https://ofai.github.io/million-post-corpus/)
* [Potsdam Commentary Corpus (PCC)](http://angcl.ling.uni-potsdam.de/resources/pcc.html)
* [Songkorpus](http://songkorpus.de/)
* [Ten Thousand German News Articles Dataset](https://github.com/tblock/10kGNAD)
* [TTLab StadtWiki Corpus](https://vlo.clarin.eu/?7&fq=collection:CEDIFOR.Corpus.StadtWikis&fqType=collection:or)


#### Swiss German

* [ArchiMob Corpus](https://www.spur.uzh.ch/en/departments/research/textgroup/ArchiMob.html)
* [NOAH's Corpus: Part-of-Speech Tagging for Swiss German](https://noe-eva.github.io/NOAH-Corpus/)
* [SpinningBytes Swiss German Sentiment Corpus](https://github.com/spinningbytes/SB-CH)
* [Swiss SMS Corpus](http://www.sms4science.ch/Main/WebHome)


#### Learner and Error Corpora

* [C-WEP](http://lingured.info/linguistic-resources/cwep/)
* [DysList (list of dyslexic errors)](https://github.com/Rauschii/DysListGerman)
* [Falko](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/forschung/falko)
* [OpinionSpam](https://github.com/hdaSprachtechnologie/OpinionSpam)


#### Word lists

* [Analogies in German Particle Verb Meaning Shifts](http://www.ims.uni-stuttgart.de/data/pv-meaning-shift)
* [Degree of Grammaticalization for German Prepositions](https://www.ims.uni-stuttgart.de/forschung/ressourcen/experiment-daten/gramm-prepositions.html)
* [DeReWo](http://www1.ids-mannheim.de/kl/projekte/methoden/derewo.html)
* [Diachronic Usage Relatedness (DURel)](http://www.ims.uni-stuttgart.de/data/durel)
* [DiMLex (lexicon of German discourse markers)](https://github.com/discourse-lab/dimlex)
* [German Compound Database](https://www.webcorpora.org/opendata/gecodb/)
* [German derivational lexicons](http://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/DErivBase.html)
* [German nouns from Wiktionary](https://github.com/gambolputty/german-nouns)
* [Metaphoric Change (annotated lexemes)](http://www.ims.uni-stuttgart.de/forschung/ressourcen/experiment-daten/metaphoric_change.html)
* [Morphological Dictionaries (DEMorphy)](https://github.com/DuyguA/german-morph-dictionaries)
* [German Wiktionary Lexicon Graph](https://vlo.clarin.eu/record?10&count=2&docId=21.11105_47_0000-000B-D244-B&fq=collection:CEDIFOR.Lexicon&fqType=collection:or&index=0)
* [German word list for GNU Aspell](https://sourceforge.net/projects/germandict/files/)
* [OpenThesaurus](https://www.openthesaurus.de/about/download)


### Data acquisition

* [bundestag](https://github.com/bundestag)
* [DKPro C4Corpus](https://github.com/dkpro/dkpro-c4corpus)
* [german-reddit](https://github.com/adbar/german-reddit)
* [news-crawler](https://github.com/theSoenke/news-crawler)
* [pattern](https://www.clips.uantwerpen.be/pages/pattern)
* [scrape-gutenberg-de](https://github.com/jfilter/scrape-gutenberg-de)
* [SwigSpot Schwyzertuutsch-Spotting](https://github.com/derlin/SwigSpot_Schwyzertuutsch-Spotting)
* Twitter
  * [German April 2013 Twitter Corpus](https://github.com/TScheffler/GermanTwitterApril2013)


### Lists of corpora

* [CLARIN-D list](https://www.clarin-d.net/en/corpora)
* [Corpora at the IMS](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/index.en.html)
* [CorpusExplorer's list of corpora](https://notes.jan-oliver-ruediger.de/korpora/)
* [Korpusarchiv (IDS Mannheim)](http://www1.ids-mannheim.de/kl/projekte/korpora/archiv.html)
* [Parallel corpora (see below)](#parallel-corpora)
* [Treebanks (see below)](#treebanks)
* [ZAS list](http://www.zas.gwz-berlin.de/katalog00100.html?&L=1)


## Generic resources

### Frameworks

* [AmbiverseNLU](https://github.com/ambiverse-nlu/ambiverse-nlu)
* [CLARIN-D web tools](https://www.clarin-d.net/en/analysing)
* [CorpusExplorer](http://notes.jan-oliver-ruediger.de/software/corpusexplorer-overview/)
* [DKPro Core](https://dkpro.github.io/dkpro-core)
* [DKPro Similarity](https://dkpro.github.io/dkpro-similarity)
* [DKPro Text Classification (TC)](https://dkpro.github.io/dkpro-tc)
* [DKPro Word Sense Disambiguation (WSD)](https://dkpro.github.io/dkpro-wsd)
* [flair](https://github.com/zalandoresearch/flair)
* [ixa pipes](http://ixa2.si.ehu.es/ixa-pipes/)
* [Mate Tools](http://hdl.handle.net/11022/1007-0000-0000-8E4E-A), webservice via [WebLicht](https://weblicht.sfs.uni-tuebingen.de/)
* [spaCy](https://github.com/explosion/spaCy)
* [Stanford CoreNLP](https://github.com/stanfordnlp/CoreNLP)
* [textblob-de](https://github.com/markuskiller/textblob-de)
* [TextImager](https://vlo.clarin.eu/record?4&count=1&docId=21.11105_47_0000-000B-CAE6-E&index=0&q=TextImager)


### Treebanks

* [German Universal Dependency Treebank](https://github.com/UniversalDependencies/UD_German-GSD/tree/master)/[UD German GSD](https://universaldependencies.org/treebanks/de_gsd/index.html)
* [Hamburg Dependency Treebank](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/treebank:hdt)
* [NEGRA](http://www.coli.uni-saarland.de/projects/sfb378/negra-corpus/)
* [TIGER Corpus](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/tiger.en.html)
   * [SALSA (role semantic annotation)](http://www.coli.uni-saarland.de/projects/salsa/corpus/)
   * [Tiger2Dep (dependency parses)](http://www.ims.uni-stuttgart.de/forschung/ressourcen/werkzeuge/Tiger2Dep.en.html)
* [TGermaCorp (literary texts)](https://vlo.clarin.eu/record?1&count=2&docId=21.11105_47_0000-000B-D4D9-1&index=0&q=TGermaCorp)
* [TüBa-D/Z](http://www.sfs.uni-tuebingen.de/en/ascl/resources/corpora/tueba-dz.html)


### Annotation

* [cora](https://github.com/comphist/cora)
* [CorefAnnotator](http://www.ims.uni-stuttgart.de/forschung/ressourcen/werkzeuge/CorefAnnotator.html)
* [corpus-tools.org (HU Berlin)](http://corpus-tools.org/home/)
* [INCEpTION](https://inception-project.github.io/)
* [TreeAnno](http://www.ims.uni-stuttgart.de/forschung/ressourcen/werkzeuge/TreeAnno.html)
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
* [syntok](https://github.com/fnl/syntok)
* [waste](http://kaskade.dwds.de/waste/)
* [german-abbreviations](https://github.com/jfilter/german-abbreviations)


### Stemming

* [CISTEM](https://github.com/LeonieWeissweiler/CISTEM)
* [Snowball](http://snowballstem.org)


### Lemmatization

* [germalemma](https://github.com/WZBSocialScienceCenter/germalemma)
* [GermaLemma++ (ensemble)](https://github.com/rubcompling/germalemmaplusplus)
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
* [SMOR](http://www.cis.uni-muenchen.de/~schmid/tools/SMOR/), webservice via [WebLicht](https://weblicht.sfs.uni-tuebingen.de/)
* [zmorge](https://github.com/rsennrich/zmorge)


### Normalization

* [CAB](http://www.deutschestextarchiv.de/cab)
* [norma](https://github.com/comphist/norma)


### POS-tagging

* [clevertagger](https://github.com/rsennrich/clevertagger)
* [hunpos](https://github.com/mivoq/hunpos)
* [moot](http://kaskade.dwds.de/~jurish/projects/moot)
* [pattern.de](https://www.clips.uantwerpen.be/pages/pattern-de)
* [RFTagger](http://www.cis.uni-muenchen.de/~schmid/tools/RFTagger/), webservice via [WebLicht](https://weblicht.sfs.uni-tuebingen.de/)
  * [Java interface](http://sifnos.sfs.uni-tuebingen.de/resource/A4/rftj/)
* [RNNTagger](https://www.cis.uni-muenchen.de/~schmid/tools/RNNTagger/)
* [SoMeWeTa](https://github.com/tsproisl/SoMeWeTa)
* [TnT](http://www.coli.uni-saarland.de/~thorsten/tnt/)
* [TreeTagger (including models)](http://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/)
  * [Demo for middle high German](http://clarin05.ims.uni-stuttgart.de/mhdtt/index.html)


### Syntactical parsing

* [Berkeley Parser](https://github.com/slavpetrov/berkeleyparser)
* [BitPar](http://www.cis.uni-muenchen.de/~schmid/tools/BitPar/), webservice via [WebLicht](https://weblicht.sfs.uni-tuebingen.de/)
* [CDG](https://nats-www.informatik.uni-hamburg.de/CDG/DownloadPage)
   * [jwcdg](https://gitlab.com/nats/jwcdg)
* [IMSTrans (dependency parser)](http://www.ims.uni-stuttgart.de/forschung/ressourcen/werkzeuge/imstrans.en.html)
* [ParZu](https://github.com/rsennrich/parzu)
* [Stanford Parser](https://nlp.stanford.edu/software/lex-parser.shtml)


### Named Entity Recognition

* [AmbiverseNLU KnowNER](https://github.com/ambiverse-nlu/ambiverse-nlu)
* [flair](https://github.com/zalandoresearch/flair)
* [GermaNER](https://github.com/tudarmstadt-lt/GermaNER)
* [LSTM+CRF+FastText with models for (historic) German](https://github.com/riedlma/sequence_tagging)
* [microNER](https://uhh-lt.github.io/microNER/)
* [Named Entity Recognition (LSTM + CRF + FastText) with models for [historic] German](https://github.com/riedlma/sequence_tagging)
* [ner-corpora](https://github.com/EuropeanaNewspapers/ner-corpora)
* [(Faruqui & Pado 2010) Components and evaluation data](https://nlpado.de/~sebastian/software/ner_german.shtml)
* [Towards Robust Named Entity Recognition for Historic German](https://github.com/dbmdz/historic-ner)


### Misc

* [ICARUS (query tool)](http://hdl.handle.net/11022/1007-0000-0000-8E56-0)
   * [ICARUS2](http://hdl.handle.net/11022/1007-0000-0007-C635-E)


### Text generation

* [ngen](https://github.com/Fedjmike/ngen)
* [pypolibox](https://github.com/arne-cl/pypolibox)


### Industry/Applications

* [German Decompounder for Apache Lucene / Apache Solr / Elasticsearch](https://github.com/uschindler/german-decompounder)
* [holmes-extractor](https://github.com/msg-systems/holmes-extractor)
* [LanguageTool](https://languagetool.org)


### Evaluation

* [DKPro Statistics](https://dkpro.github.io/dkpro-statistics)
* [Evaluating Off-the-Shelf NLP Tools for German](https://github.com/rubcompling/konvens2019)
* [Evaluation of different NLP toolkits](https://github.com/goerlitz/nlp-german)


## Semantic analysis

### Datasets

* [Complex Word Identification (DE, EN, ES, FR)](https://sites.google.com/view/cwisharedtask2018/home)
* Distributional memories: [DM.de](http://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/dm-de.html) [TransDM.de](http://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/transdmde.html)
* [Distributional thesauri (includes German)](https://sourceforge.net/projects/jobimtext/files/data/models/)
* [Lexical Chains](https://www.inf.uni-hamburg.de/en/inst/ab/lt/resources/data/lexical-chains.html)
* [Logical metonymy database](http://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/GLMD.html)
* [schulteimwalde.de/resources.html](http://www.schulteimwalde.de/resources.html)
* [Semantic Relations in Context](https://www.inf.uni-hamburg.de/en/inst/ab/lt/resources/data/semreldata.html)
* [UKP Darmstadt data list](https://www.informatik.tu-darmstadt.de/ukp/research_6/data/index.en.jsp)


### Word embeddings and senses

* [disco (semantic similarity)](https://github.com/linguatools/disco)
* [GermaNet](http://www.sfs.uni-tuebingen.de/GermaNet/)
   * [pygermanet](https://github.com/wroberts/pygermanet)
* [german2vec](https://github.com/Bachfischer/german2vec)
* [GermanWordEmbeddings](https://github.com/devmount/GermanWordEmbeddings)
* [German ELMO model](https://github.com/t-systems-on-site-services-gmbh/german-elmo-model)
* [Open German WordNet](https://github.com/hdaSprachtechnologie/odenet)
* [sensegram](https://github.com/tudarmstadt-lt/sensegram)
* [SpinningBytes word embeddings (tweets)](https://www.spinningbytes.com/resources/wordembeddings/)
* [UBY Linked Lexical Resource](https://dkpro.github.io/dkpro-uby/)


### Sentiment analysis datasets / polarity clues

* [Affective norms: abstractness, arousal, imageability and valence ratings](http://www.ims.uni-stuttgart.de/data/affective_norms)
* [GermanPolarityClues](http://www.ulliwaltinger.de/sentiment/)
* [HeiST – Heidelberg Sentiment Treebank](http://www.cl.uni-heidelberg.de/~versley/HeiST/)
* [(Non-)Literalness Ratings for complex verbs](http://www.ims.uni-stuttgart.de/data/pv_nonlit )
* [Potsdam Twitter Sentiment Corpus (PotTS)](https://github.com/WladimirSidorenko/PotTS)
* [Sentiment Lexicon (Univ. Zurich)](http://bics.sentimental.li/files/8614/2462/8150/german.lex)
* [SentimentWortschatz](http://wortschatz.uni-leipzig.de/en/download/)
* [SpinningBytes Swiss German Sentiment Corpus](https://github.com/spinningbytes/SB-CH)


### Sentiment detection

* [EmotiKLUE](https://github.com/tsproisl/EmotiKLUE)
* [LT-ABSA: Aspect-based Sentiment Analysis](https://www.inf.uni-hamburg.de/en/inst/ab/lt/resources/software/lt-absa.html)
* [sentiment-analyser](https://github.com/syzer/sentiment-analyser)
* [spacy-sentiws](https://github.com/Liebeck/spacy-sentiws)


### GermEval

*(category to improve)*
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

* [Bilingual formality (T/V) corpus (EN/DE)](https://nlpado.de/~sebastian/data/tv_data.shtml)
* [Bilingual FrameNet frame embeddings (EN/DE)](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/XLFrameEmbed.html)
* [Bilingual parallel frame-semantic annotation (EN/DE)](https://nlpado.de/~sebastian/data/srl_data.shtml)
* [CorZu (coreference resolution)](https://github.com/dtuggener/CorZu)
* [Discourse Segmenter](https://github.com/WladimirSidorenko/DiscourseSegmenter)
* [Frame Identification](https://github.com/UKPLab/naacl18-multimodal-frame-identification)
* [German social media textual entailment dataset](https://www.cl.uni-heidelberg.de/~zeller/res/te-ger/index.mhtml)
* [HotCoref DE (coreference resolution)](https://www.ims.uni-stuttgart.de/forschung/ressourcen/werkzeuge/HotCorefDe)
* [PropS-DE (proposition structures)](https://github.com/UKPLab/props-de)
* [Tense-mood-voice annotation system](https://github.com/aniramm/tmv-annotator)


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
* [Open Speech Data Corpus](http://voxforge.org/home/forums/other-languages/german/open-speech-data-corpus-for-german)


## Machine Translation

* []()


#### Parallel corpora

* [Linguatools Webcrawl German-English 2015](http://linguatools.org/tools/corpora/webcrawl-parallel-corpus-german-english-2015/)
* [MuchMore Springer Bilingual Corpus](http://muchmore.dfki.de/resources1.htm)
* [OPUS collection](http://opus.nlpl.eu/)


## Teaching resources and tutorials

* [bubenhofer.com/korpuslinguistik/kurs/](http://www.bubenhofer.com/korpuslinguistik/kurs/)
* [CorpusExplorer v2.0 – Seminartauglich in einem halben Tag](https://lernen-mit.jan-oliver-ruediger.de/)
* [deeplearning4nlp-tutorial](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Statistics for linguists (S. Vasishth)](https://github.com/vasishth/Statistics-lecture-notes-Potsdam)
* Uni Zürich: Sprachtechnologie in den Digital Humanities – MOOC [Youtube](https://www.youtube.com/channel/UChb3Rd5vo3WEgMSy99VInaw) & [Coursera](http://www.coursera.org/learn/digital-humanities)


## More lists

### German

* [CLARIN VLO (DE+public)](https://vlo.clarin.eu/search?2&fq=languageCode:code:deu&fq=licenseType:PUB)
* [computerlinguistik.org](http://www.computerlinguistik.org/portal/portal.html?s=Ressourcen)
* [Learn German as a foreign language](https://github.com/willianpaixao/awesome-german)
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
