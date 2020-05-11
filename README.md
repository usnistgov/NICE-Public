# NICE-Public
NIST's Integrated Colony Enumerator (NICE)

Version 1.4 (Development Version B.2.c, April 2019)

Created and modified, 2008-2020,
Modified, April 2020 for Windows 10 64 bit compliance with MATLAB 2016b.

NICE was developed by:
Matthew Clarke and Jeeseong Hwang (jch@nist.gov)
Applied Physics Division
National Institute of Standards and Technology
Boulder, CO 80305

In collaboration with:
Robert Burton and Moon Nahm, University of Alabama – Birmingham

Citation:
Matthew L. Clarke, Robert L. Burton, A. Nayo Hill, Maritoni Litorja, Moon H. Nahm,Jeeseong Hwang, "Low-Cost, High-Throughput, Automated Counting of Bacterial Colonies" Cytometry A, 77A, 790-797 (2010)

*Correspondence should be sent to jch@nist.gov.

NICE executable file download link:
https://doi.org/10.18434/M32073

For NICE MATLAB codes, please contact jch@nist.gov
 
Support for this project was provided in part by PATH.  The views expressed by the authors do not necessarily reflect the views of PATH.

OVERVIEW

Enumeration of bacterial colonies in an agar plate is simple in concept, but automated colony counting is difficult due to variations in colony color, size, shape, contrast, and density, as well as colony overlap.  Furthermore, in applications where high throughput is essential, it is critical to employ a fast and user-friendly automated technique that doesn’t compromise counting accuracy.  While commercial products exist that can count bacterial colonies, they can be cost-prohibitive for small laboratories.  We present here a colony counting program, NIST’s Integrated Colony Enumerator (NICE), designed to count dark colonies from multiple regions of interests on an agar plate.  Images can be cost effectively acquired by a digital camera or a desktop scanner and imported into NICE.  High throughput standardized assay formats such as the multiplexed opsonophagocytic killing (MOPA4) assay can be readily counted by NICE.

DISCLAIMERS

This software was developed by employees of the National Institute of Standards and Technology (NIST), an agency of the Federal Government and is being made available as a public service. Pursuant to title 17 United States Code Section 105, works of NIST employees are not subject to copyright protection in the United States.  This software may be subject to foreign copyright.  Permission in the United States and in foreign countries, to the extent that NIST may hold copyright, to use, copy, modify, create derivative works, and distribute this software and its documentation without fee is hereby granted on a non-exclusive basis, provided that this notice and disclaimer of warranty appears in all copies. 

THE SOFTWARE IS PROVIDED 'AS IS' WITHOUT ANY WARRANTY OF ANY KIND, EITHER EXPRESSED, IMPLIED, OR STATUTORY, INCLUDING, BUT NOT LIMITED TO, ANY WARRANTY THAT THE SOFTWARE WILL CONFORM TO SPECIFICATIONS, ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND FREEDOM FROM INFRINGEMENT, AND ANY WARRANTY THAT THE DOCUMENTATION WILL CONFORM TO THE SOFTWARE, OR ANY WARRANTY THAT THE SOFTWARE WILL BE ERROR FREE.  IN NO EVENT SHALL NIST BE LIABLE FOR ANY DAMAGES, INCLUDING, BUT NOT LIMITED TO, DIRECT, INDIRECT, SPECIAL OR CONSEQUENTIAL DAMAGES, ARISING OUT OF, RESULTING FROM, OR IN ANY WAY CONNECTED WITH THIS SOFTWARE, WHETHER OR NOT BASED UPON WARRANTY, CONTRACT, TORT, OR OTHERWISE, WHETHER OR NOT INJURY WAS SUSTAINED BY PERSONS OR PROPERTY OR OTHERWISE, AND WHETHER OR NOT LOSS WAS SUSTAINED FROM, OR AROSE OUT OF THE RESULTS OF, OR USE OF, THE SOFTWARE OR SERVICES PROVIDED HEREUNDER.
Support for this project was provided in part by PATH.  The views expressed by the developers of the software do not necessarily reflect the views of PATH.  NICE is an experimental system. Neither NIST nor PATH assumes any responsibility whatsoever for its use by other parties, and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic. We would appreciate acknowledgment if the software is used. This software can be redistributed and/or modified freely provided that any derivative works bear some notice that they are derived from it, and any modified versions bear some notice that they have been modified. 

Certain commercial equipment, instruments, or materials are identified in this paper in order to specify the experimental procedure adequately. Such identification is not intended to imply recommendation or endorsement by the National Institute of Standards and Technology, nor is it intended to imply that the materials or equipment identified are necessarily the best available for the purpose.



