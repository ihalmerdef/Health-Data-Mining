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

12.everolimus

13.felbamate

14.fosphenytoin

15.gabapentin

16.lacosamide

17.lamotrigine

18.levetiracetam

19.mephenytoin

20.metharbital

21.methsuximide

22.methazolamide

23.oxcarbazepine

24.phenobarbital

25.phenytoin DILANTIN

26.piracetam

27.phensuximide

28.pregabalin

29.primidone

30.rufinamide

31.sodium valproate

32.stiripentol

33.tiagabine

34.topiramate

35.trimethadione

36.valproic acid

37.vigabatrin

38.zonisamide

I have the ratings of these drugs for research purposes so if you are intersted to get the ratings dataset for the above drugs please reach to me through my email address: ihalmerdef@nu.edu.sa
