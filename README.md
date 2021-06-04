# WKL2batchinfo
Does 3 things:  
1.) Autodetects columns of individual .d files from wkl file  
2.) Autoassigns batch numbers based on plate number as well as column  
3.) Compiles all data into batchinfo_SP2.txt for MRMKit processing.  
  
Instructions:  
1.) Place wkl files named appropriately in input folder  
2.) Run Runner.jar  
  
Requirements:  
1.) Java SE 13.0.2 at least  
2.) WKL files must be named "#.wkl" e.g. 1.wkl, 2.wkl etc based on plate number chronologically  
3.) Pooled samples MUST have the word "pool" inside its name somwehere e.g. pooled is OK  
4.) The method files referenced in the wkl files MUST end with "...C1.m" or "...C2.m" based on column number  
  
Notes:  
Is not capable of processing MRMKit Blanks i.e. blanks with ISTD yet
