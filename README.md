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
   - [Deep learning models and transformers](#Deep-learning-models-and-transformers)
   - [Annotation](#Annotation)
   - [Standards](#Standards)
- [Linguistic processing](#Linguistic-processing)
   - [Preprocessing](#Preprocessing)
   - [Tokenization / Sentence boundary detection](#Tokenization--sentence-boundary-detection)
   - [Stemming](#Stemming)
   - [Lemmatization](#Lemmatization)
   - [Morphological analysis](#Morphological-analysis)
   - [Normalization](#Normalization)
   - [Phonology](#Phonology)
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
* [CEHugeWebCorpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11372/LRT-2638)
* [COW](http://corporafromtheweb.org/category/corpora/german/)
* [Digitales Wörterbuch der deutschen Sprache (DWDS)](https://dwds.de)
* [GC4 Corpus](https://german-nlp-group.github.io/projects/gc4-corpus.html) (CommonCrawl)
* [IDS Corpora](http://www1.ids-mannheim.de/kl/projekte/korpora)
* [Leipzig Corpora Collection](http://wortschatz.uni-leipzig.de/en/download/)
* [SdeWaC](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/sdewac.en.html)


### Historical

* [Anselm (14th-16th centuries)](https://www.linguistics.ruhr-uni-bochum.de/anselm/access/index.en.html)
* [Austrian Newspapers (19th C. NewsEye / READ OCR training dataset)](https://github.com/UB-Mannheim/AustrianNewspapers)
* [Deutsches Textarchiv](https://deutschestextarchiv.de/)
* [Elektronische Texte (Thomas Gloning)](http://www.staff.uni-giessen.de/gloning/etexte.htm)
* [GerManC (1650-1800)](https://ota.bodleian.ox.ac.uk/repository/xmlui/handle/20.500.12024/2544)
* [German Drama Corpus (GerDraCor)](https://github.com/dracor-org/gerdracor)
* [German Novels](https://github.com/computationalstylistics/68_german_novels)
* [German Poetry Corpus (DLK)](https://github.com/thomasnikolaushaider/DLK)
* [Lesekorpus Altdeutsch (750-1050)](http://titus.uni-frankfurt.de/lea)
* [LiederCorpus](https://github.com/corpusmusic/liederCorpusAnalysis)
* [Referenzkorpus Altdeutsch (750-1050)](http://www.deutschdiachrondigital.de/)
* [Referenzkorpus Mittelhochdeutsch (1050-1350)](https://www.linguistics.rub.de/rem/)
* [Referenzkorpus Mittelniederdeutsch/Niederrheinisch (1200-1650)](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/text-corpus:ren-0.6)
* [Referenzkorpus Frühneuhochdeutsch (1350-1650)](https://www.linguistics.rub.de/ref/)
* [Thesaurus Indogermanischer Text- und Sprachmaterialien (TITUS)](http://titus.uni-frankfurt.de/indexd.htm?/texte/texte.htm)
* [Transkriptionen von Fibeln (19. Jahrhundert)](https://github.com/UB-Mannheim/Fibeln)


### Specialized

* [arg-microtexts](http://angcl.ling.uni-potsdam.de/resources/argmicro.html)
* [auto-hMDS (multi-document summarization)](https://github.com/AIPHES/auto-hMDS)
* [DFKI MobIE](https://github.com/DFKI-NLP/MobIE)
* [DIRNDL -- (D)iscourse (I)nformation (R)adio (N)ews (D)atabase for (L)inguistic Analysis](https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/dirndl.en.html)
* [Dortmunder Chat Korpus](http://www.chatkorpus.tu-dortmund.de/)
* [Feidegger (Fashion Images and Descriptions)](https://github.com/zalandoresearch/feidegger)
* [Foodblog-Korpus](https://doi.org/10.5281/zenodo.1410445)
* [Fußballlinguistik](https://fussballlinguistik.de/korpora/)
* [German EUROPARL data w/ NE annotation](https://nlpado.de/~sebastian/software/ner_german.shtml)
* [German Job Reference Corpus](https://github.com/iug-htw/GJRC)
* [German Political Speeches Corpus](http://purl.org/corpus/german-speeches)
* [German Recipes Dataset](https://www.kaggle.com/sterby/german-recipes-dataset)
* [GermaParl (Bundestag)](https://github.com/PolMine/GermaParlTEI)
* [German Parliamentary Corpus (GerParCor)](https://github.com/texttechnologylab/GerParCor)
* [German Wikipedia Text Corpus](https://github.com/t-systems-on-site-services-gmbh/german-wikipedia-text-corpus)
* [GRAIN corpus -- (G)erman-(RA)dio-(IN)terviews](https://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/grain.html)
* [Legal Entity Recognition](https://github.com/elenanereiss/Legal-Entity-Recognition)
* [One Million Posts Corpus](https://ofai.github.io/million-post-corpus/)
* [Open Legal Data Corpus (German laws and court decisions)](http://openlegaldata.io/research/2019/02/19/court-decision-dataset.html)
* [Pegida Facebook Comments](http://0x0a.li/wp-content/uploads/2015/01/pegida_korpus.zip)
* [Potsdam Commentary Corpus (PCC)](http://angcl.ling.uni-potsdam.de/resources/pcc.html)
* [Songkorpus](http://songkorpus.de/)
* [Ten Thousand German News Articles Dataset](https://github.com/tblock/10kGNAD)
* [TTLab StadtWiki Corpus](https://vlo.clarin.eu/?7&fq=collection:CEDIFOR.Corpus.StadtWikis&fqType=collection:or)
* [GSM-1k-de (translated german subset of the first 1000 items of GSM8K)](https://huggingface.co/datasets/D4ve-R/gsm-1k-de)

#### Swiss German

* [ArchiMob Corpus](https://www.spur.uzh.ch/en/departments/research/textgroup/ArchiMob.html)
* [NOAH's Corpus: Part-of-Speech Tagging for Swiss German](https://noe-eva.github.io/NOAH-Corpus/)
* [SpinningBytes Swiss German Sentiment Corpus](https://github.com/spinningbytes/SB-CH)
* [Swiss SMS Corpus](http://www.sms4science.ch/Main/WebHome)


#### Learner and Error Corpora

* [C-WEP](http://lingured.info/linguistic-resources/cwep/)
* [DysList (list of dyslexic errors)](https://github.com/Rauschii/DysListGerman)
* [Falko](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/forschung/falko)
* [Litkey](https://www.linguistics.ruhr-uni-bochum.de/litkeycorpus/)
* [OpinionSpam](https://github.com/hdaSprachtechnologie/OpinionSpam)


#### Word lists

* [Analogies in German Particle Verb Meaning Shifts](http://www.ims.uni-stuttgart.de/data/pv-meaning-shift)
* [Degree of Grammaticalization for German Prepositions](https://www.ims.uni-stuttgart.de/forschung/ressourcen/experiment-daten/gramm-prepositions.html)
* [DWDS lemma list](https://www.dwds.de/lemma/list)
* [DeReWo](http://www1.ids-mannheim.de/kl/projekte/methoden/derewo.html)
* [Diachronic Usage Relatedness (DURel)](http://www.ims.uni-stuttgart.de/data/durel)
* [DiMLex (lexicon of German discourse markers)](https://github.com/discourse-lab/dimlex)
* [German Compound Database](https://www.webcorpora.org/opendata/gecodb/)
* [German derivational lexicons](http://www.ims.uni-stuttgart.de/forschung/ressourcen/lexika/DErivBase.html)
* [German nouns from Wiktionary](https://github.com/gambolputty/german-nouns)
* [Metaphoric Change (annotated lexemes)](http://www.ims.uni-stuttgart.de/forschung/ressourcen/experiment-daten/metaphoric_change.html)
* [Morphological Dictionaries (DEMorphy)](https://github.com/DuyguA/german-morph-dictionaries)
* [german_stopwords](https://github.com/solariz/german_stopwords)
* [Stopwords German (DE)](https://github.com/stopwords-iso/stopwords-de)
* [German Wiktionary Lexicon Graph](https://vlo.clarin.eu/record?10&count=2&docId=21.11105_47_0000-000B-D244-B&fq=collection:CEDIFOR.Lexicon&fqType=collection:or&index=0)
* [wiktextract](https://github.com/tatuylonen/wiktextract)
* [wiktionary-de-parser](https://github.com/gambolputty/wiktionary-de-parser)
* [German word list for GNU Aspell](https://sourceforge.net/projects/germandict/files/)
* [OpenThesaurus](https://www.openthesaurus.de/about/download)


### Data acquisition

* [bundestag](https://github.com/bundestag)
* [bundestweets](https://github.com/michi-d/bundestweets)
* [DKPro C4Corpus](https://github.com/dkpro/dkpro-c4corpus)
* [german-reddit](https://github.com/adbar/german-reddit)
* [news-crawler](https://github.com/theSoenke/news-crawler)
* [news-please](https://github.com/fhamborg/news-please)
* [pattern](https://github.com/clips/pattern/wiki/pattern-de)
  * [patternlite](https://github.com/WZBSocialScienceCenter/patternlite)
* [scrape-gutenberg-de](https://github.com/jfilter/scrape-gutenberg-de)
* [SwigSpot Schwyzertuutsch-Spotting](https://github.com/derlin/SwigSpot_Schwyzertuutsch-Spotting)
* Twitter
  * [German April 2013 Twitter Corpus](https://github.com/TScheffler/GermanTwitterApril2013)
* [trafilatura](https://github.com/adbar/trafilatura)


### Lists of corpora

* [CLARIN-D list](https://www.clarin-d.net/en/corpora)
* [Corpora at the IMS](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/index.en.html)
* [CorpusExplorer's list of corpora](https://notes.jan-oliver-ruediger.de/korpora/)
* [Korpusarchiv (IDS Mannheim)](http://www1.ids-mannheim.de/kl/projekte/korpora/archiv.html)
* [Laudatio (Long-term Access and Usage of Deeply Annotated Information)](https://www.laudatio-repository.org/)
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
* [FreeLing](http://nlp.lsi.upc.edu/freeling/)
* [ixa pipes](http://ixa2.si.ehu.es/ixa-pipes/)
* [Mate Tools](http://hdl.handle.net/11022/1007-0000-0000-8E4E-A), webservice via [WebLicht](https://weblicht.sfs.uni-tuebingen.de/)
* [NLP-Cube](https://github.com/adobe/NLP-Cube)
* [nlptasks](https://github.com/ulf1/nlptasks)
* [spaCy](https://github.com/explosion/spaCy)
* [Sparv](https://spraakbanken.gu.se/sparv/docs/)
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


## Deep learning models and transformers

* [LAION LeoLM Llama v2 German Foundation Language Model 7B Parameters](https://huggingface.co/LeoLM/leo-hessianai-7b)
* [LAION  LeoLM Llama v2 German Foundation Language Model 13B Parameters](https://huggingface.co/LeoLM/leo-hessianai-13b)
* [dbmdz BERT models](https://github.com/dbmdz/berts)
* [Deepset German BERT model](https://deepset.ai/german-bert)
* [Evaluating German Transformer Language Models with Syntactic Agreement Tests](https://github.com/DFKI-NLP/gevalm)
* [German ELMo Model](https://github.com/t-systems-on-site-services-gmbh/german-elmo-model)
* [german-transformer-training](https://github.com/PhilipMay/german-transformer-training)
* [GermLM](https://github.com/tonianelope/Multilingual-BERT) (NER exploration)
* [GerPT2](https://github.com/bminixhofer/gerpt2)
* [Sentence Transformers](https://github.com/UKPLab/sentence-transformers)


### Annotation

* [cora](https://github.com/comphist/cora)
* [CorefAnnotator](https://www.ims.uni-stuttgart.de/en/research/resources/tools/corefannotator/)
* [corpus-tools.org (HU Berlin)](http://corpus-tools.org/home/)
* [INCEpTION](https://inception-project.github.io/)
* [satzify](https://github.com/michdr/satzify)
* [TreeAnno](https://www.ims.uni-stuttgart.de/forschung/ressourcen/werkzeuge/treeanno/)
* [WebAnno](https://webanno.github.io/webanno/)


### Standards

* [DTA Basisformat](http://www.deutschestextarchiv.de/doku/basisformat/)
* [ISO TC 37 SC 4](https://www.iso.org/committee/297592.html)
* [UIMA](http://docs.oasis-open.org/uima/v1.0/os/uima-spec-os.html)
* [UIMA CAS XMI](https://uima.apache.org/d/uimaj-current/references.html#ugr.ref.xmi)


## Linguistic processing

### Preprocessing

* [clean-text](https://github.com/jfilter/clean-text)
* [german-preprocessing](https://github.com/jfilter/german-preprocessing)
* [german_transliterate](https://github.com/repodiac/german_transliterate)


### Tokenization / Sentence boundary detection

* [Cutter](https://pub.cl.uzh.ch/wiki/public/cutter/start)
* [Datok](https://github.com/korap/datok)
* [deep-eos](https://github.com/dbmdz/deep-eos) (sentence boundary detection only)
* [FullStop](https://github.com/oliverguhr/fullstop-deep-punctuation-prediction) (sentence boundary detection only)
* [JTok](https://github.com/DFKI-MLT/JTok)
* [KorAP-Tokenizer](https://github.com/KorAP/KorAP-Tokenizer)
* [nnsplit](https://github.com/bminixhofer/nnsplit) (sentence boundary detection only)
* [SoMaJo](https://github.com/tsproisl/SoMaJo)
* [syntok](https://github.com/fnl/syntok)
* [waste](http://kaskade.dwds.de/waste/)
* [german-abbreviations](https://github.com/jfilter/german-abbreviations) (resource)


### Stemming

* [CISTEM](https://github.com/LeonieWeissweiler/CISTEM)
* [german-go-stemmer](https://github.com/antonbaumann/german-go-stemmer)
* [Snowball](http://snowballstem.org)


### Lemmatization

* [cstlemma](https://github.com/kuhumcst/cstlemma)
* [germalemma](https://github.com/WZBSocialScienceCenter/germalemma)
* [GermaLemma++ (ensemble)](https://github.com/rubcompling/germalemmaplusplus)
* [german-lemmatizer](https://github.com/jfilter/german-lemmatizer)
* [IWNLP](https://github.com/Liebeck/IWNLP)
   * [spacy-iwnlp](https://github.com/Liebeck/spacy-iwnlp)
* [LemmaTag](https://github.com/Hyperparticle/LemmaTag)
* [simplemma](https://github.com/adbar/simplemma)


### Morphological analysis

* [CharSplit](https://github.com/dtuggener/CharSplit)
* [DEMorphy](https://github.com/DuyguA/DEMorphy)
* [dehyphen](https://github.com/jfilter/dehyphen)
* [deep-german](https://github.com/aakhundov/deep-german) (classification of nouns by genders)
* [Durm Lemmatizer](http://www.semanticsoftware.info/durm-german-lemmatizer)
* [german_compound_splitter](https://github.com/repodiac/german_compound_splitter)
* [GermanNumerus](https://github.com/ulrischa/GermanNumerus)
* [HypheNN-de](https://github.com/msiemens/HypheNN-de)
* [jwordsplitter](https://github.com/danielnaber/jwordsplitter)
* [lang-deu](https://github.com/giellalt/lang-deu)
* [Low German morphology and tools](https://github.com/giellalt/lang-nds)
* [MarMoT](http://cistern.cis.lmu.de/marmot/)
* [MOP Compound Splitter](https://www.ims.uni-stuttgart.de/forschung/ressourcen/werkzeuge/mcs/)
* [Morphy](http://morphy.wolfganglezius.de/)
* [morphisto](https://code.google.com/archive/p/morphisto/)
* [nnsplit](https://github.com/bminixhofer/nnsplit)
* [SECOS (unsupervised compound splitter)](https://github.com/riedlma/SECOS)
* [SFST](http://www.cis.uni-muenchen.de/~schmid/tools/SFST/)
* [SMOR](http://www.cis.uni-muenchen.de/~schmid/tools/SMOR/), webservice via [WebLicht](https://weblicht.sfs.uni-tuebingen.de/)
* [timur](https://github.com/wrznr/timur)
* [zmorge](https://github.com/rsennrich/zmorge)


### Normalization

* [CAB](http://www.deutschestextarchiv.de/cab)
* [dehyphen](https://github.com/pd3f/dehyphen)
* [norma](https://github.com/comphist/norma)


### Phonology

* [gramophone](https://github.com/wrznr/gramophone)


### POS-tagging

* [clevertagger](https://github.com/rsennrich/clevertagger)
* [HanTa](https://github.com/wartaal/HanTa/)
* [hunpos](https://github.com/mivoq/hunpos)
* [LemmaTag](https://github.com/Hyperparticle/LemmaTag)
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
* [STEPS Parser](https://github.com/boschresearch/steps-parser)


### Named Entity Recognition

* [AmbiverseNLU KnowNER](https://github.com/ambiverse-nlu/ambiverse-nlu)
* [flair](https://github.com/zalandoresearch/flair)
* [GermaNER](https://github.com/tudarmstadt-lt/GermaNER)
* [GERNERMED](https://github.com/frankkramer-lab/GERNERMED)
* [historic-ner](https://github.com/dbmdz/historic-ner)
* [LSTM+CRF+FastText with models for (historic) German](https://github.com/riedlma/sequence_tagging)
* [microNER](https://uhh-lt.github.io/microNER/)
* [Named Entity Recognition (LSTM + CRF + FastText) with models for [historic] German](https://github.com/riedlma/sequence_tagging)
* [ner-corpora](https://github.com/EuropeanaNewspapers/ner-corpora)
* [NER-datasets](https://github.com/davidsbatista/NER-datasets)
* [(Faruqui & Pado 2010) Components and evaluation data](https://nlpado.de/~sebastian/software/ner_german.shtml)
* [Towards Robust Named Entity Recognition for Historic German](https://github.com/dbmdz/historic-ner)


### Misc

* [German Preprocessing](https://github.com/jfilter/german-preprocessing)
* [ICARUS (query tool)](http://hdl.handle.net/11022/1007-0000-0000-8E56-0)
   * [ICARUS2](http://hdl.handle.net/11022/1007-0000-0007-C635-E)
* [nlprule (error correction)](https://github.com/bminixhofer/nlprule)


### Text generation

* [fake_text](https://github.com/fhswf/fake_text)
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
* [Downloads page](https://sites.google.com/site/iggsahome/home) of the Interest Group on German Sentiment Analysis
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
* [WECHSEL (subword embeddings)](https://github.com/CPJKU/wechsel)


### Sentiment analysis datasets / polarity clues

* [Affective norms: abstractness, arousal, imageability and valence ratings](http://www.ims.uni-stuttgart.de/data/affective_norms)
* [German Sentiment Classification Model for Dialog Systems](https://github.com/oliverguhr/german-sentiment)
* [GermanPolarityClues](http://www.ulliwaltinger.de/sentiment/)
* [HeiST – Heidelberg Sentiment Treebank](http://www.cl.uni-heidelberg.de/~versley/HeiST/)
* [(Non-)Literalness Ratings for complex verbs](http://www.ims.uni-stuttgart.de/data/pv_nonlit )
* [Potsdam Twitter Sentiment Corpus (PotTS)](https://github.com/WladimirSidorenko/PotTS)
* [Sentiment dictionary for German political language](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/BKBXWD)
* [Sentiment Lexicon (Univ. Zurich)](http://bics.sentimental.li/files/8614/2462/8150/german.lex)
* [SentimentWortschatz](http://wortschatz.uni-leipzig.de/en/download/)
* [SpinningBytes Swiss German Sentiment Corpus](https://github.com/spinningbytes/SB-CH)


### Sentiment detection

* [EmotiKLUE](https://github.com/tsproisl/EmotiKLUE)
* [germansentiment: A simple python package for sentiment classification](https://github.com/oliverguhr/german-sentiment-lib)
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
* [Coreferee](https://github.com/msg-systems/coreferee)
* [CorZu (coreference resolution)](https://github.com/dtuggener/CorZu)
* [Discourse Segmenter](https://github.com/WladimirSidorenko/DiscourseSegmenter)
* [Frame Identification](https://github.com/UKPLab/naacl18-multimodal-frame-identification)
* [German social media textual entailment dataset](https://www.cl.uni-heidelberg.de/~zeller/res/te-ger/index.mhtml)
* [HotCoref DE (coreference resolution)](https://www.ims.uni-stuttgart.de/forschung/ressourcen/werkzeuge/HotCorefDe)
* [PropS-DE (proposition structures)](https://github.com/UKPLab/props-de)
* [Tense-mood-voice annotation system](https://github.com/aniramm/tmv-annotator)


### Summarization

* [Klexikon](https://github.com/dennlinger/klexikon) (Joint Summarization and Simplification)
* [Tools and corpora for summarization of German texts](https://github.com/AIPHES)


### Psycholinguistics

* [Noun Associations for German](http://www.psycholing.es.uni-tuebingen.de/nag/index.php)


## Speech NLP

* [Archiv für gesprochenes Deutsch](http://agd.ids-mannheim.de/korpus_index.shtml)
* [BAS ressources](http://www.bas.uni-muenchen.de/Bas/BasSpeechresourceseng.html)
* [Bochumer Korpus der gesprochenen Sprache im Ruhrgebiet](https://www.ruhr-uni-bochum.de/kgsr/)
* [Database for Spoken German (IDS Mannheim)](https://dgd.ids-mannheim.de/dgd/pragdb.dgd_extern.welcome)
* [deepspeech-german](https://github.com/AASHISHAG/deepspeech-german)
* [(D)iscourse (I)nformation (R)adio (N)ews (D)atabase for (L)inguistic Analysis ](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/dirndl.en.html)
* [Hamburger Zentrum für Sprachkorpora](https://corpora.uni-hamburg.de/hzsk/)
* [kaldi-tuda-de](https://github.com/uhh-lt/kaldi-tuda-de)
* [Open Speech Data Corpus](http://voxforge.org/home/forums/other-languages/german/open-speech-data-corpus-for-german)
* [Thorsten (Emotional) - Open German Voice Dataset](https://github.com/thorstenMueller/deep-learning-german-tts/#emotional-dataset-information-and-samples-microphone)
* [Thorsten (Neutral) - Open German Voice Dataset](https://github.com/thorstenMueller/deep-learning-german-tts/#samples-of-my-neutral-voice)


## Machine Translation

*(category to improve)*
* [Tensorflow NMT DE-EN](https://github.com/tensorflow/nmt)
   * [NMT English to German](https://github.com/thomasschmied/Neural_Machine_Translation_Tensorflow)
* [Unsupervised Word Segmentation for NMT](https://github.com/rsennrich/subword-nmt)


#### Parallel corpora

* [Linguatools Webcrawl German-English 2015](http://linguatools.org/tools/corpora/webcrawl-parallel-corpus-german-english-2015/)
* [MuchMore Springer Bilingual Corpus](http://muchmore.dfki.de/resources1.htm)
* [OPUS collection](http://opus.nlpl.eu/)


## Teaching resources and tutorials

* [bubenhofer.com/korpuslinguistik/kurs/](http://www.bubenhofer.com/korpuslinguistik/kurs/)
* [CorpusExplorer v2.0 – Seminartauglich in einem halben Tag](https://lernen-mit.jan-oliver-ruediger.de/)
* [deeplearning4nlp-tutorial](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [deutsch-nlp (text classification)](https://github.com/taylorhawks/deutsch-nlp)
* [German Text Classification Tutorial Series](https://github.com/realjanpaulus/german_text_classification_nlp)
* [Statistics for linguists (S. Vasishth)](https://github.com/vasishth/Statistics-lecture-notes-Potsdam)
* [Stilometrie](https://github.com/realjanpaulus/stylometry)
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
* [awesome-danish](https://github.com/fnielsen/awesome-danish)
* [awesome-hungarian-nlp](https://github.com/oroszgy/awesome-hungarian-nlp)
* [awesome Information Retrieval](https://github.com/harpribot/awesome-information-retrieval)
* [Indonesian NLP](https://github.com/kmkurn/id-nlp-resource)
* [Norwegian NLP resources](https://github.com/web64/norwegian-nlp-resources)
* [awesome-nlp-polish](https://github.com/ksopyla/awesome-nlp-polish)
* [awesome-spanish-nlp](https://github.com/dav009/awesome-spanish-nlp)
* [NLP-Pandect](https://github.com/ivan-bilan/The-NLP-Pandect)
* [M. Weisser's list of NLP/Computational Linguistics Resources](http://martinweisser.org/corpora_site/comp_ling_resources.html)
* [NLP tools (Saarland University)](http://www.coli.uni-saarland.de/~csporled/page.php?id=tools)
* [W. Roberts' Computational Linguistics Links](http://amor.cms.hu-berlin.de/~robertsw/links.html)


### Larger institutional GitHub groups


* [DFKI-NLP](https://github.com/DFKI-NLP)
* [Language Technology Group, Universität Hamburg](https://github.com/uhh-lt)
* [Saarland University Spoken Language Systems Group](https://github.com/uds-lsv)
* [Ubiquitous Knowledge Processing Lab, TU Darmstadt](https://github.com/ukplab)
* [Webis](https://github.com/webis-de)


## Contributors

See the [list of contributors](https://github.com/adbar/German-NLP/graphs/contributors).


## License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)
