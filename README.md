# Awesome-Korean-NLP

A curated list of resources related to NLP (Natural Language Processing) for Korean + NLP resources in Korean.

Tools specialized for Korean is listed ahead of language-agnostic tools.

Feel free to contribute!

Maintainer: [Jaemin Cho](https://github.com/j-min/)

## Index

1. [Tools](#1.-Tools)
2. [Dataset](#2.-Dataset)
3. [Papers](#3.-Papers)
4. [Lectures](#4.-Lectures)
5. [Blog Posts / Slides ](#5.-Blog-Posts-/-Slides)
6. [Researchers / Institutes](#6.-Researchers-/-Institutes)
7. [Journals / Conferences / Events](#7.-Journals-/-Conferences-/-Events)
8. [Online Forums](#8.-Online-Forums)
9. [How to contribute](#9.-How-to-contribute)

## 1. Tools

### 1.1. POS Tagger / 형태소 분석기
- Hannanum (한나눔) (Java, C) [[link](https://kldp.net/hannanum/)]
	- KoNLPy (Python) [[link](http://konlpy.org/en/v0.4.4/api/konlpy.tag/#module-konlpy.tag._hannanum)]
- Kkma (꼬꼬마) (Java) [[link](http://kkma.snu.ac.kr/documents/index.jsp)] [[paper](http://ids.snu.ac.kr/w/images/f/f8/CPL2010-therocks.pdf)]
	- KoNLPy (Python) [[link](http://konlpy.org/en/v0.4.4/api/konlpy.tag/#module-konlpy.tag._kkma)]
- Komoran (Java) [[link](http://www.shineware.co.kr/?page_id=835)]
	- KoNLPy (Python) [[link](http://konlpy.org/en/v0.4.4/api/konlpy.tag/#module-konlpy.tag._komoran)]
- Mecab-ko (C++) [[link](https://bitbucket.org/eunjeon/mecab-ko)]
	- KoNLPy (Python) [[link](http://konlpy.org/en/v0.4.4/api/konlpy.tag/#mecab-class)]
- Twitter (Scala, Java) [[link](https://github.com/twitter/twitter-korean-text)]
	- KoNLPy (Python) [[link](http://konlpy.org/en/v0.4.4/api/konlpy.tag/#module-konlpy.tag._twitter)]
	- .NET, Node.js, Python, Ruby, Elasitc Search bindings 
- KTS [[paper](http://scholar.ndsl.kr/schDetail.do?cn=NPAP07926299#)]
- Arirang (Lucence, Java) [[link](http://cafe.naver.com/korlucene)]
- 깜짝새 [[link](https://ryubook.wordpress.com/%EA%B9%9C%EC%A7%9D%EC%83%88-1-5-5-beta/)]
- dparser (REST API) [[link](http://findyou.readthedocs.io/ko/latest/dparser.html)]
- Rouzeta [[link](https://shleekr.github.io/)] [[slide](http://www.slideshare.net/JieunLee5/ss-67333029?ref=https://readme.skplanet.com/?p=13166)] [[video](https://www.youtube.com/watch?v=tkSVbfWZgn8)]
- seunjeon (Scala, Java) [[link](https://bitbucket.org/eunjeon/seunjeon)]
- RHINO (라이노) [[link](https://sourceforge.net/projects/koreananalyzer/)]

### 1.2. Parser / 구문 분석기
- dparser (REST API) [[link](http://findyou.readthedocs.io/ko/latest/dparser.html)]
- NLP HUB (Java) [[link](http://semanticweb.kaist.ac.kr/home/index.php/NLP_HUB)]

### 1.3. NE Tagger / 개체명 인식기
- annie [[link](https://github.com/krikit/annie)]

### 1.4. Translator / 번역기
- Naver NMT [[link](http://labspace.naver.com/nmt/)]
- OpenNMT [[link](http://opennmt.net/)]
- Google Translator [[link](https://translate.google.com/)]

### 1.5. Sentimental Analysis / 감정 분석기
- OpenHangul (오픈한글) [[link](http://openhangul.com/)] [[paper](http://web.yonsei.ac.kr/dslab/Journal/sentiment%20dictionary.pdf)]

### 1.6. Spell Checker / 맞춤법 검사기
- PNU Spell Checker [[link](http://speller.cs.pusan.ac.kr/)]
- Naver Spell Checker [[link](https://search.naver.com/search.naver?where=nexearch&sm=tab_jum&ie=utf8&query=%ED%95%9C%EA%B8%80+%EB%A7%9E%EC%B6%A4%EB%B2%95+%EA%B2%80%EC%82%AC%EA%B8%B0)]
- Daum Spell Checker [[link](http://alldic.daum.net/grammar_checker.do)]
- hunspell-ko [[link](https://github.com/changwoo/hunspell-dict-ko)]

### 1.7. Packages
- KoNLP (R\) [[link](https://cran.r-project.org/web/packages/KoNLP/index.html)]
- KoNLPy (Python) [[link](konlpy.org)] [[paper](http://dmlab.snu.ac.kr/~lucypark/docs/2014-10-10-hclt.pdf)]
- KoalaNLP (Scala) [[link](https://nearbydelta.github.io/KoalaNLP/)]
- NLTK (Python) [[link](http://www.nltk.org/)] [[paper](http://www.aclweb.org/anthology/P04-3031)]
- gensim (Python) [[link](https://radimrehurek.com/gensim/)]
- FastText (C) [[link](https://github.com/facebookresearch/fastText)]
	- FastText.py (Python) [[link](https://github.com/salestock/fastText.py)]

### 1.8. Others / 기타

- Hangulpy (Python) [[link](https://github.com/rhobot/Hangulpy)]
	- 자동 조사/접미사 첨부, 자모 분해 및 결합
- Hangulize (Python) [[link](https://github.com/sublee/hangulize)]
	- 외래어 한글 변환
- kroman [[link](https://github.com/zhangkaiyulw/kroman)]
	- Hangul Romanization
	- [Ruby](https://github.com/cheunghy/kroman-gem), [Python](https://github.com/zhangkaiyulw/kroman-py), [NodeJS](https://github.com/cheunghy/kroman-js), [Objective-C](https://github.com/cheunghy/kroman-objc), [Swift](https://github.com/cheunghy/kroman-swift)
- hangul (Perl) [[link](https://github.com/dragoncrane/hangul)]
	- Hangul Romanization
- textrankr (Python) [[link](https://github.com/theeluwin/textrankr)] [[demo](https://summariz3.herokuapp.com)]
	- TextRank 기반 한국어 문서 요약
- 한국어 Word2Vec [[demo](http://virgon.snu.ac.kr:8000/)] [[paper](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDozMjkyYjRkYWViM2Q0MzU2)]
	- 한국어 Word2Vec의 analogy test 데모
- 나쁜 단어 사전 [[link](http://badworddictionary.xyz/)]
	- crowdsourced dic about badword in korean

## 2. Dataset
- Sejong Corpus [[link](https://ithub.korean.go.kr/user/corpus/corpusSearchManager.do)]
- KAIST Corpus [[link](http://semanticweb.kaist.ac.kr/home/index.php/KAIST_Corpus)]
- Yonsei Univ. Corpus
- Korea Univ. Corpus
- Wikipedia Dump [[link](https://dumps.wikimedia.org/kowiki/)] [[Extractor](https://github.com/j-min/WikiExtractor_To_the_one_text)]
- NamuWiki Dump [[link](https://namu.wiki/w/%EB%82%98%EB%AC%B4%EC%9C%84%ED%82%A4:%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4%20%EB%8D%A4%ED%94%84)] [[Extractor](https://github.com/j-min/Easy-Namuwiki-Extractor)]
- Naver News Archive [[link](http://dna.naver.com)]
- Chosun Archive [[link](http://srchdb1.chosun.com/pdf/i_archive/)]
- Naver sentiment movie corpus [[link](https://github.com/e9t/nsmc/)]
- sci-news-sum-kr-50 [[link](https://github.com/theeluwin/sci-news-sum-kr-50)]

## 3. Papers
## 3.1. Korean
- 

## 3.2. English
- 

## 4. Lectures
## 4.1. Korean Lectures
- Kangwon Univ. 자연언어처리 [[link](http://cs.kangwon.ac.kr/~leeck/NLP/)]
- 데이터 사이언스 스쿨 [[link](https://www.datascienceschool.net/)]
- SNU Data Mining / Business Analytics [[link](https://www.lucypark.kr/courses/)]


## 4.2. English Lectures
- Stanford CS224N: Natural Language Processing [[link](http://web.stanford.edu/class/cs224n/)] [[YouTube](https://www.youtube.com/playlist?list=PL6397E4B26D00A269)]
- Stanford CS224d: Deep Learning for Natural Language Processing [[link](http://cs224d.stanford.edu/index.html)] [[YouTube](https://www.youtube.com/playlist?list=PLmImxx8Char9Ig0ZHSyTqGsdhb9weEGam)]
- NLTK with Python 3 for NLP (by Sentdex) [[YouTube](https://www.youtube.com/playlist?list=PLQVvvaa0QuDf2JswnfiGkliBInZnIC4HL)]
- LDA Topic Models [[link](https://www.youtube.com/watch?v=3mHy4OSyRf0)]

## 5. Blog Posts / Slides
### 5.1. Blog Posts
- dsindex's blog [[link](http://dsindex.github.io/)]
- 엑사젠, "혼자 힘으로 한국어 챗봇 개발하기" [[link](http://exagen.tistory.com/notice/63)]
- Beomsu Kim, "word2vec 관련 이론 정리" [[link](https://shuuki4.wordpress.com/2016/01/27/word2vec-%EA%B4%80%EB%A0%A8-%EC%9D%B4%EB%A1%A0-%EC%A0%95%EB%A6%AC/)]
- CPUU, "Google 자연어 처리 오픈소스 SyntaxNet 공개" (Korean tranlsation of [Google blog](http://googleresearch.blogspot.kr/2016/05/announcing-syntaxnet-worlds-most.html)) [[link](http://cpuu.postype.com/post/166917/)]
- theeluwin, "python-crfsuite를 사용해서 한국어 자동 띄어쓰기를 학습해보자" [[link](http://blog.theeluwin.kr/post/147587579528/python-crfsuite%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%B4%EC%84%9C-%ED%95%9C%EA%B5%AD%EC%96%B4-%EC%9E%90%EB%8F%99-%EB%9D%84%EC%96%B4%EC%93%B0%EA%B8%B0%EB%A5%BC-%ED%95%99%EC%8A%B5%ED%95%B4%EB%B3%B4%EC%9E%90)]

### 5.2. Slides
- Lucy Park, "한국어와 NLTK, Gensim의 만남" (PyCon APAC 2015) [[link](https://www.lucypark.kr/slides/2015-pyconkr/)]
- Jeongkyu Shin, "Building AI Chat bot using Python 3 & TensorFlow" (PyCon APAC 2016) [[link](https://speakerdeck.com/inureyes/building-ai-chat-bot-using-python-3-and-tensorflow)]
- Changki Lee, "RNN & NLP Application" (Kangwon Univ. Machine Learning course) [[link](http://cs.kangwon.ac.kr/~leeck/ML/RNN_NLP.pdf)]
- Kyunghoon Kim, "뉴스를 재미있게 만드는 방법; 뉴스잼" (PyCon APAC 2016) [[link](http://www.slideshare.net/koorukuroo/20160813-pycon2016apac)]
- Hongjoo Lee, "Python 으로 19대 국회 뽀개기" (PyCon APAC 2016) [[link](http://www.slideshare.net/hongjoo/python-19-pycon-apac-2016)]
- Kyumin Choi,"word2vec이 추천시스템을 만났을 때" (PyCon APAC 2015) [[link](http://www.slideshare.net/ssuser2fe594/2015-py-con-word2vec)]
- 進藤裕之 (translated by Hongbae Kim), "딥러닝을 이용한 자연어처리의 연구동향" [[link](http://www.slideshare.net/ssuser06e0c5/ss-64417928)]
- Hongbae Kim, "머신러닝의 자연어 처리기술(I)" [[link](http://www.slideshare.net/ssuser06e0c5/i-64267027)]
- Changki Lee, "자연어처리를 위한 기계학습 소개" [[link](http://www.slideshare.net/deview/f2-14341235?qid=12363290-1fe5-4903-9a5a-71a4e0c3842f&v=&b=&from_search=7)]
- Taeil Kim, Daeneung Son, "기계 번역 모델 기반 질의 교정 시스템" (Naver DEVIEW 2015) [[link](http://www.slideshare.net/deview/242-52779038)]

## 6. Researchers / Institues
### 6.1. Researchers
- 

### 6.2. Institutes
- 언어공학연구회 [[link](https://sites.google.com/site/sighclt/)]
	- 한글 및 한국어 정보처리 학술대회 (Since 1989, 매년 개최) [[link](https://sites.google.com/site/2016hclt/home)]
	- 국어 정보 처리 시스템 경진대회 (Since 2010, 매년 개최, 주최: 문화체육관광부 및 국립국어원) [[link](http://ithub.korean.go.kr/user/contest/contestIntroLastView.do)]
	- 자연언어처리 튜토리얼 (비정기적) [[link](https://sites.google.com/site/sighclt/haengsasogae/jayeon-eon-eocheoli-tyutolieol)]
	- 자연어처리 및 정보검색 워크샵 [[link](https://sites.google.com/site/sighclt/haengsasogae/jayeon-eocheoli-mich-jeongbogeomsaeg-wokeusyab-1)]
- 한국음성학회 [[link](https://ksss.jams.or.kr/co/main/jmMain.kci)]

## 7. Journals / Conferences / Events

### 7.1. Journals

### 7.2. Conferences
- 한글 및 한국어 정보처리 학술대회 [[link](https://sites.google.com/site/2016hclt/home)]
- KIPS (한국정보처리학회) [[link](http://www.kips.or.kr/)]
- 한국음성학회 학술대회 [[link](https://ksss.jams.or.kr/co/com/EgovMenu.kci?s_url=/ac/config/guid/acGuidview.kci?guidId=000000001258&s_MenuId=MENU-000000000032000&s_tabId=1&accnId=AC0000000006)]

### 7.3. Events
- 국어 정보 처리 시스템 경진 대회 [[link](http://ithub.korean.go.kr/user/contest/contestIntroLastView.do)]


## 8. Online Forums
- 언어공학연구회 [[link](https://sites.google.com/site/sighclt/)]
- Reddit Machine Learning Top posts [[link](https://www.reddit.com/r/MachineLearning/top/)]
- AI Korea (Facebook Group) [[link](https://www.facebook.com/groups/AIKoreaOpen/)]
- Tensorflow KR (Facebook Group) [[link](https://www.facebook.com/groups/TensorFlowKR/)]
- Bot Group (Facebook Group) [[link](https://www.facebook.com/groups/botgroup/)]
- 바벨피쉬 (Facebook Group) [[link](https://www.facebook.com/groups/babelPish/)]

## 9. How to contribute
1) Fork this Repository

2) Edit

3) Create Pull Request! [[Help](https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-project/)]
