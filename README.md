# OCR for Degraded Bangla Documents
During the last 20 years, significant research studies
have been undertaken for automatic recognition of printed
documents. The same is true for Bangla, a major Indian
script. All these studies were mainly centered on comparatively
well-behaved good quality printed documents. However, many
of the large archives include significant volumes of older
documents which are so degraded in their present form that
they cannot be reasonably transcribed using the existing OCR
(Optical Character Recognition) approaches. On the other hand,
automatic recognition of printed contents of these documents has
significant application potentials such as generation of descriptive
metadata, full-text searching, information extraction etc. The
contributions made in the present study are (i) creation of
a moderately large annotated database of degraded Bangla
documents towards their recognition studies, (ii) development of
a Gaussian mixture model based strategy for extraction of text
components from complex noisy background of such documents
and (iii) development of a line level recognition scheme for
degraded Bangla documents. We have studied two different CNNBLSTM-CTC
hybrid architectures for this recognition problem.
The winning architecture uses the first convolution layer of the
CNN in a fashion similar to the inception model of deep learning
methodologies.

## Full paper
[A Hybrid Deep Architecture for Robust Recognition of Text Lines of Degraded Printed Documents](https://ieeexplore.ieee.org/abstract/document/8545409)

## Database descriptions
The present database (ISIDDI) consists of images of 535
pages scanned from 15 old Bangla printed books. These
books had been collected from three different sources, viz.
(i) Indian Statistical Institute library, (ii) Old Book Market at
College Street, Kolkata, India and (iii) the Public Library of
India (https://archive.org/details/digitallibraryindia). A number
of pages of the books collected from sources (i) and (ii)
containing various types of degradations. We scanned
these degraded document pages using a flatbed scanner at 300
dpi and stored them as color images in both uncompressed
TIF and JPG formats. Similarly, we have identified several
pages of printed Bangla containing one or multiple types of
degradations from the above archive and downloaded them.
Since these books were originally written over a long period
of time of the past history, both of their forms of Bangla
language and font of the printed script vary widely. This
dataset of printed Bangla document pages is divided into
training, test and validation sets consisting of approximately
60%, 25% and 15% sample page images. There are 323,
130 and 82 sample document images in the training, test
and validation sets of the ISIDDI database. Each of these
samples has been ground truthed in Unicode and annotated
at the line level. The numbers of word and character classes
appearing in this entire database are respectively 26,663 and
320. The division of the ISIDDI into the three sets has been
done randomly at the initial stage and latter some adjustments
have been made such that the character lexicon size of each
set becomes the same, i.e., 320. This sample database is
available (https://www.isical.ac.in/∼ujjwal/download/database.html)
free-of-cost for academic research purposes. A few
degraded document image samples have been shown in following figure.

![Alt text](DegradedSamplesCollage.jpg?raw=true "A few samples of document degradation present in
ISIDDI database.")

![Alt text](ICPR2018Poster.png?raw=true

## Related and usefull link
[OCR for Degraded Bangla Documents](https://github.com/xisnu/DegradedOCR)
