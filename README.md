# Los Angeles homeless arrests analysis

By [Christine Zhang](mailto:ychristinezhang@gmail.com)

The Los Angeles Times conducted an analysis of arrests of the homeless by the Los Angeles Police Department.

The results were reported in a February 4, 2018, Los Angeles Times story titled ["L.A. leaders oppose 'criminalizing' homeless people. But thousands are jailed for minor offenses"](http://www.latimes.com/local/politics/la-me-homeless-arrests-20180203-story.html).

The Times' findings and analysis are available in a Jupyter [notebook](https://github.com/datadesk/homeless-arrests/blob/master/L.A.%20homeless%20arrests%20analysis.ipynb) in this repository.

Arrestees whose home addresses were recorded as “transient” (sometimes spelled as “trasient” in the data) were classified as homeless.
 
There were six days in 2011 for which arrests data were not available: Feb. 20th, March 17th, Apr. 17th, May 18th, June 11th and Aug. 4th. Arrest figures were prorated for the months with the missing dates to ensure consistency of year-to-year comparisons.

The story reports how many individual homeless arrests were made, regardless of whether the arrestee was cited on multiple charges. The top offenses, by contrast, were determined by analyzing each charge separately. 

The top offenses graphic groups charge codes into the following categories:

* Failure to appear in court includes charges listed under charge codes 40508(A)VC, 853.7PC and 853.8PC
* Drug possession includes charges listed under 11350(A)HS, 11350HS, 11351HS, 11357(A)HS, 11357(B)HS, 11357(C)HS, 11357HS, 11375(B)2HS, 11377(A)1HS, 11377(A)HS, 11377HS, 11550(A)HS, 4060BP and 4573.6PC
* Supervision violation (parole/probation) includes charges listed under 1203.2(A)PC, 1203.2PC, 18 3606US, 3000.08CPC, 3000.08FPC, 3056PC, 3454(C)PC, 3454PC, 3455(A)4PC, 3455(A)PC, 3455(B)1PC and 3455(C)PC
* Shoplifting includes charges listed under 18 1708, 459.5PC, 484(A)PC, 484E(A)PC, 484E(B)PC, 484E(D)PC, 484F(A)PC, 484PC, 484PCTFMV, 485PC, 488PC, 490.2PC, 490.5(A)PC, 490PC, 537(A)(1)PC, 587CPC, 666.5(A)PC, 666.5PC, 666(A)PC, 666PC, A484PC and A488PC
* Trespassing includes charges listed under 369I(A)PC, 419PC, 484F(A)PC, 555PC, 602.1(A)PC, 602.1(B)PC, 602.5(A)PC, 602.5(B)PC, 602(A)PC, 602(D)PC, 602(J)PC, 602(K)PC, 602(L)(1)PC, 602(M)PC, 602(N)PC, 602(O)(1)PC, 602(O)(2)PC, 602(O)PC, 602(P)PC, 602(Q)PC, 602(S)PC, 602(U)(1)PC, 602PC, 647(E)PC and  647(H)PCLPP.

In October 2016, the LAPD began restricting the number of charges it reported on its daily arrest logs to three. This change does not affect the overall patterns presented in this story, as the majority of arrestees were booked on three or fewer charges.

The data file published with this repository was prepared as part of an unpublished processing script. The raw LAPD data includes names and other identifying information about arrestees that The Times has chosen to withhold.  