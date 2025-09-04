# Guidelines for CTI Datasets

## This website summarizes detailed information regarding the Guidelines for CTI Datasets included in the following paper [1].

## *Detailed information will be released on this website after publication of the paper [1].

*[1] (Under Review) Keisuke Furumoto, Tomohiro Morikawa, Antti Kolehmainen, Bilhanan Silverajan, Takeshi Takahashi, Daisuke Inoue, "A Comprehensive Survey of Threat Intelligence Research: A Measurement-Based Study" ACM Computing Surveys.*

### Background:<br>
The relationship between clients and groups behind cyber attacks has become complicated, making it challenging to deal with cyber attacks.
The use of various types of threat information related to cyber attacks, often referred to as **Cyber Threat Intelligence (CTI)**, is necessary.
Therefore, recent trends in the cyber security field are the management and sharing of various types of CTI and the cross-analysis of multiple types of CTI to deal with sophisticated and complex cyber attacks. 

### Purpose of this website:<br>
We provide the necessary information for constructing **well-balanced datasets** required for CTI research.
Our paper [1] showed that existing CTI research uses unbalanced datasets. We used the following datasets and their statistical information (IoC).

1. Datasets<br>
   -When using a dataset from a security report, it should be considered that vendors include different numbers and types of IoC<br>
   -For a practical evaluation, the bias among the original datasets should be considered when constructing the experimental dataset.<br>
   -When merging data from the Surface Web and the Dark Web, it should be considered whether the IoCs that can be merged are included in the first place.<br>
2. statistical information (IoC)<br>
   -Security Reports, Public Database: IPv4, FQDN, Email, URL, File name, Hash, CVE<br>

Contact:
Tomohiro Morikawa
morikawa@gsis.u-hyogo.ac.jp
