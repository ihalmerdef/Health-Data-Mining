# Health-Data-Mining

Problems I faced so far:
 - UnicodeDecodeError: 'ascii' codec can't decode byte 0xe2 in position 1387: ordinal not in range(128) 
 Solved by doing changing these lines
with open('acetazolamide.html') as html_file:
to
with open('acetazolamide.html',encoding="utf-8") as html_file:
and 
with open('acetazolamide.csv', 'w') as csvfile:
to
with open('acetazolamide.csv', 'w',encoding="utf-8") as csvfile:


* Drugs that I finished scraping so far from askapatient.com:
1. acetazolamide//done

2.brivaracetam//done

3.carbamazepine//done

4.cenobamate//no ratings found in askapatient.com

5.clobazam//done

6.clonazepam//done

7.diazepam//done

8.divalproex sodium//done

9.eslicarbazepine//done

10.ethosuximide//done

11.ethotoin//no ratings found in askapatient.com

12.everolimus//done

13.felbamate//done

14.fosphenytoin//no ratings found in askapatient.com

15.gabapentin//done

16.lacosamide//done

17.lamotrigine//done

18.levetiracetam//done

19.mephenytoin//no ratings found in askapatient.com

20.metharbital//no records found 

21.methsuximide//done

22.methazolamide//done

23.oxcarbazepine//done

24.phenobarbital//No records returned for PHENOBARBITAL

25.phenytoin DILANTIN//done

26.piracetam//No records returned for PIRACETAM

27.phensuximide//No records returned for PHENSUXIMIDE

28.pregabalin//done

29.primidone//done

30.rufinamide//done

31.sodium valproate//No records returned for SODIUM VALPROAT

32.stiripentol//No records returned for STIRIPENTOL

33.tiagabine//done

34.topiramate//done

35.trimethadione//no ratings found in askapatient.com

36.valproic acid//done

37.vigabatrin//no ratings found in askapatient.com

38.zonisamide//done

I have the ratings of these drugs for research purposes so if you are intersted to get the ratings dataset for the above drugs please reach to me through my email address: ihalmerdef@nu.edu.sa
