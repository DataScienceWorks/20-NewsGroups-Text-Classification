# 20 Newsgroups - Text Classification



### Context

This dataset is a collection newsgroup documents. The 20 newsgroups collection has become a popular data set for experiments in text applications of machine learning techniques, such as text classification and text clustering.

### Content

There is file (list.csv) that contains a reference to the document_id number and the newsgroup it is associated with. There are also 20 files that contain all of the documents, one document per newsgroup.

In this dataset, duplicate messages have been removed and the original messages only contain "From" and "Subject" headers (18828 messages total).

Each new message in the bundled file begins with these four headers:

Newsgroup: alt.newsgroup

Document_id: xxxxxx

From: Cat

Subject: Meow Meow Meow

The Newsgroup and Document_id can be referenced against list.csv

Organization - Each newsgroup file in the bundle represents a single newsgroup - Each message in a file is the text of some newsgroup document that was posted to that newsgroup.

This is a list of the 20 newsgroups:

- comp.graphics
- comp.os.ms-windows.misc
- comp.sys.ibm.pc.hardware
- comp.sys.mac.hardware
- comp.windows.x rec.autos
- rec.motorcycles
- rec.sport.baseball
- rec.sport.hockey sci.crypt
- sci.electronics
- sci.med
- sci.space
- misc.forsale talk.politics.misc
- talk.politics.guns
- talk.politics.mideast talk.religion.misc
- alt.atheism
- soc.religion.christian

### Acknowledgements

Ken Lang is credited by the source for collecting this data. The source of the data files is here: 
<http://qwone.com/~jason/20Newsgroups/>

### Inspiration

- This dataset text can be used to classify text documents