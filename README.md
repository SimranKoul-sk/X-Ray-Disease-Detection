# X-Ray-Disease-Detection

CONCEPT
X-ray is a classical method for diagnosis of some chest diseases. The
diseases are reparable in the event that they are distinguished in their
beginning periods. Detection of chest diseases is mostly based on
chest X-ray images (CXR). This is a tedious procedure and consumes
too much time. At times, medical experts had overlooked the diseases
in their first examinations on CXR, and when the images were reexamined, the infection signs could be identified.
Create a AI based Computer Aided Diagnosis Tool, which can
classify he input X-Ray images into one of the 14 abnormalitiesAtelectasis, Consolidation, Infiltration, Pneumothorax, Edema,
Emphysema, Fibrosis, Effusion, Pneumonia, Pleural-thickening,
Cardiomegaly, Nodule, Mass and Hernia. Diseases are identified by
Class Activation Maps, which highlight the areas of the X-Ray that
are most important for making a particular abnormality classification.
This project aims to build an AI based Healthcare startup which will
take the image of the X-Ray and predict which of the 8 diseases is
present in the patient’s X-Ray.This model will aim to be used by
doctors who find it difficult to handle large number of cases at a very
substantial fee and also this startup will help the nonmedical
individuals to cross-verify the reports that they obtain from the
examination from the doctors.
This startup is also aimed for radiology students who can cross verify
their examination by giving the input of the X-Ray and with the 
obtained results, thereby increasing the efficiency in the new
generation doctors.

PROBLEM DEFINITION
A major health sector issue in India is lack of Diagnosis Support
System and doctors to serve the large number of patients in rural
areas. Indian Hospitals in rural areas also lack Radiologist. Thousands of
cases are usually handled by single available doctor for X-Ray
diagnosis. To assist the doctors in arriving at quick diagnosis, it is
recommended to have a solution that can do Computer Aided
Diagnosis for the Chest X-Ray
Our solution proposes the use of transfer learning approaches or
traditional handcrafted techniques to achieve a remarkable
classification performance, we use cross-verify different algorithms to
extract features from a given chest X-ray image and classify it to
determine if a person is infected with any of the disease.
This model could help mitigate the reliability and interpretability
challenges often faced when dealing with medical imagery. We
deployed several data augmentation algorithms to improve the
validation and classification accuracy of the CNN model and achieved
remarkable validation accuracy.

OBJECTIVES OF THE WORK
Medical check-ups in rural India- Indian Hospitals in rural areas also
lack Radiologist. Thousands of cases are usually handled by single
available doctor for X-Ray diagnosis. Our product can help them to
directly communicate with professional doctors without coming to
city
Accurate reports – Accurate reports can be provided instantly to the
docter and it will be in the database for further reference and to assist
the doctors in arriving at quick diagnosis, it is recommended to have a
solution that can do Computer Aided Diagnosis for the Chest X-Ray.
Traditional pricing rules no longer apply -Transparency in Price is
one of the best advantages that we can deliver to our customers and
this also helps them to pay minimal amount for almost every test they
have
This project aims to build an AI based Healthcare startup which will
take the image of the X-Ray and predict which of the 8 diseases is
present in the patient’s X-Ray.
This model will aim to be used by doctors who find it difficult to
handle large number of cases at a very substantial fee and also this
startup will help the non-medical individuals to cross-verify the
reports that they obtain from the examination from the doctors.
This startup is also aimed for radiology students who can cross verify
their examination by giving the input of the X-Ray and with the
obtained results, thereby increasing the efficiency in the new
generation doctors.

METHODOLOGY AND EXPERMENTAL WORK

METHODLOGY
This model will aim to be used by doctors who find it difficult to
handle large number of cases at a very substantial fee and also this
startup will help the nonmedical individuals to cross-verify the reports
that they obtain from the examination from the doctors.
This startup is also aimed for radiology students who can cross verify
their examination by giving the input of the X-Ray and with the
obtained results, thereby increasing the efficiency in the new
generation doctors.
Our solution proposes a convolutional neural network (CNN) model
trained from scratch to classify and detect the presence of the diseases
from a collection of chest X-ray image samples. Unlike other methods
that rely solely on transfer learning approaches or traditional
handcrafted techniques to achieve a remarkable classification
performance, we constructed a convolutional neural network model
from scratch to extract features from a given chest X-ray image and
classify it to determine if a person is infected with any of the disease.
This model could help mitigate the reliability and interpretability
challenges often faced when dealing with medical imagery. We
deployed several data augmentation algorithms to improve the
validation and classification accuracy of the CNN model and achieved
remarkable validation accuracy.
The overall architecture of the proposed CNN model which consists
of two major parts: the feature extractors and a classifier (sigmoid
activation function). Each layer in the feature extraction layer takes its 
immediate preceding layer's output as input, and its output is passed
as an input to the succeeding layers.
The proposed architecture consists of the convolution, max-pooling,
and classification layers combined together. The feature extractors
comprise conv3×3, 32; conv3×3, 64; conv3×3, 128; conv3×3, 128,
max-pooling layer of size 2×2, and a RELU activator between them.
The output of the convolution and max-pooling operations are
assembled into 2D planes called feature maps, and we obtained
198×198×32, 97×97×62, 46×64×128, and 21×21×128 sizes of feature
maps, respectively, for the convolution operations and 99×99×32,
48×48×64, 23×23×128, and 10×10×128 sizes of feature maps from
the pooling operations, respectively, with an input of image of size
200×200×3.

MURA: Large Dataset for Abnormality Detection in
Musculoskeletal Radiographs
We introduce MURA, a large dataset of musculoskeletal radiographs
containing 40,561 images from 14,863 studies, where each study is
manually labeled by radiologists as either normal or abnormal. To
evaluate models robustly and to get an estimate of radiologist
performance, we collect additional labels from six board-certified
Stanford radiologists on the test set, consisting of 207 musculoskeletal
studies. On this test set, the majority vote of a group of three
radiologists serves as gold standard. We train a 169-layer DenseNet
baseline model to detect and localize abnormalities. Our model
achieves an AUROC of 0.929, with an operating point of 0.815
sensitivity and 0.887 specificity. We compare our model and
radiologists on the Cohen's kappa statistic, which expresses the
agreement of our model and of each radiologist with the gold
standard. Model performance is comparable to the best radiologist
performance in detecting abnormalities on finger and wrist studies.
However, model performance is lower than best radiologist 
performance in detecting abnormalities on elbow, forearm, hand
humerus, and shoulder studies. We believe that the task is a good
challenge for future research. 

CONCLUSION:
Initially, our website would operate only inside Vellore. A single
office, located in central Vellore would suffice. In the beginning, we
will operate from hostels to save on the office setup-cost. It will
significantly reduce the initial investment cost. Once break-even is
achieved, an office can be setup at the desired location.
A two room apartment is more than enough for well-functioning of
our website. Standard office requirements like computers, printers and
telephones will be required. Since our website is just a platform like
any other website, the clients will have their own X-Rays to upload on
this website. Through our website, they would be able to get the
results of their uploaded X-Rays.
A website is required for the clients to upload their X-Ray file and
place a service request. Only cost involved is of server and its
maintenance.
The most important aspect of opening this business is that initially we
don’t require any man power. As we have CSE/IT members in our
team, we can build the website on our own. This helps us in achieving
the breakeven point very fast as there is no salary situation present in
the business. In later stages, a trained manager can be hired for each
of the 6 categories. Their task would be to handle all the requests and
follow up with both the parties i.e. the clients and doctors aptly.
FUTURE SCOPE OF WORK:
Medical check-ups in rural India- Indian Hospitals in rural areas also
lack Radiologist. Thousands of cases are usually handled by single
available doctor for X-Ray diagnosis. Our product can help them to
directly communicate with professional doctors without coming to
city 
Accurate reports – Accurate reports can be provided instantly to the
doctor and it will be in the database for further reference and to assist
the doctors in arriving at quick diagnosis, it is recommended to have a
solution that can do Computer Aided Diagnosis for the Chest X-Ray.
Traditional pricing rules no longer apply -Transparency in Price is
one of the best advantages that we can deliver to our customers and
this also helps them to pay minimal amount for almost every test they
have.
Sustainable competitive advantage (Sustainability- Sector1)
The reason we chose this strategy is because we know what exactly
hassles general public when it comes to waiting in long queues just to
get an X-Ray detected. We provide a platform where people, who
have preregistered with us, are given the opportunity to shorten their
time and get their disease detected. The disease detection is done
using a database that is made with doctor’s consultation of every
disease discovered till date and in cheap cost. Each and every service
will have different charges based on the complexity of the customer’s
demand, like their request to send the X-Ray directly to the doctor to
get the prescription for medication or treatment required for the
disease or health problem.
Innovation factor (Sustainability – Sector2)
This is very innovative business and one of the very few of its kind.
Currently, no such company with the same service provision exists.
We will be maintaining proper book of accounts and services of the
customers and if a customer uses our services regularly, there will be
special offers as well. We will also have an area for the remarks of
the customers to know if they are satisfied with our services and they
can also provide suggestions where they believe we can make an
easier and more accessible GUI. 
Avoidance of pitfalls (Sustainability – sector3)
All the customers will have their requests attended to on time and will
be provided with the detected result shortly after they upload their XRay document. In case if the service performed by the website is
delayed, the customer has the advantage to decrease the cost of the
service by 5% and then pay the bill. Also, our website maintains
internal controls adequate to ensure all standards are met, and where
possible, exceed all relevant legal requirements. This website
endeavours to behave with honesty, integrity and act fairly and with
the intelligence that is inscribed in it and dealings with its customers
and other clients.
Graceful Exit (Sustainability – Sector4)
More than 90% of startups fail in India. Therefore, while working
hard for the success of the startup we should prepare for its failure. In
our startup we have built a website by which the users can request for
a detection of their disease from the uploaded X-Ray. In case our
startup fails and we are ready to shut down, all the stakeholders,
clients, employees, customers and investors will be informed in
advance and the whole process will be properly planned and executed
in order to make the exit easy on everyone. From the legal stand
point, to shut down our start-up we will be using the Fast Track Exit
Mode as it allows our company to expedite shut down at a lower cost
and a shorter time period. In order to apply for a fast track exit, a
company should:
(a) not have any assets and liabilities
(b) not have any business operation form the past year which has to be
fulfilled and if the set of conditions are met, our company can be
struck off the registrar of the Registrar of Companies (RoC). The
website may be sold to some other party for same or some other
service. 
