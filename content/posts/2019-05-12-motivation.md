---
title: Motivation for choosing the topic
date: '2019-05-12'
categories:
  - Essay
---

We are signing documents to verify we are the ones who read the document and agree with its content. It is expected we will sign a real paper document. How easy is it if we want to sign some documents without meeting with another party in person? Do we print the documents from their electronic form only because we need to sign them? There is an alternative in the form of electronic signatures, and there are several reasons we have chosen to concentrate on them.

Firstly, recent changes in the legal status of electronic signatures define their legal status in many parts of the world. For example, in the EU, [eIDAS regulation](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv%3AOJ.L_.2014.257.01.0073.01.ENG) establishes the principle that an "electronic signature should not be denied legal effect on the grounds that it is in an electronic form" and a "qualified electronic signature should have the equivalent legal effect of a handwritten signature".

Furthermore, we could not find any specialized, open-source and cross-platform software that would allow for easy document signing using electronic, and, especially, qualified electronic (is defined in the [eIDAS regulation](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=uriserv%3AOJ.L_.2014.257.01.0073.01.ENG)) signature. What we could find were forum threads discussing lack of such software like the thread "[There is no open-source implementation of PaDES PDF digital signature standard available on Linux](https://www.linuxquestions.org/questions/linux-software-2/there-is-no-open-source-implementation-of-pades-pdf-digital-signature-standard-available-on-linux-4175618211/)" on the LinuxQuestions.org.

Lastly, current software development frameworks allow efficient cross-platform desktop application development enabling us to develop desktop software for all platforms faster than ever. There are libraries available that can simplify the implementation of the signing. Example of that is the "[DSS: Digital signature service](https://ec.europa.eu/cefdigital/wiki/display/CEFDIGITAL/Services+eSignature)" offered by the [CEF Digital](https://ec.europa.eu/cefdigital/wiki/display/CEFDIGITAL) that should facilitate "creation, extension and validation of advanced electronic signatures." This library is licensed under an open source license that allows usage in our software.

This bachelor thesis, therefore, aims to explore the principles and legal status of electronic signatures, review current electronic signature software, and explore possible obstacles the open-source community is facing to develop such specialized applications. We propose an open-source, cross-platform, and user-friendly software compliant with the eIDAS Regulation (Regulation No 910/2014). Our application should allow ordinary users to quickly sign and verify signatures of different types of documents and therefore easily use them in everyday life.
