import sys 
import os
from datetime import date 
today=str(date.today()) 
sample1="1" 
sample2="2" 
sample3="3" 
sample4="4" 
x=(input('select function 1.sample 2.sample 3.sample 4.sample')) 
if x=="1": 
   print('name your folder') 
   namefolder=input() 
   os.chdir('F:\Test') 
   os.mkdir(today+""+namefolder) 
   os.chdir(today+""+namefolder) 
   os.mkdir('copy') 
   os.mkdir('selected') 
   os.mkdir('exports')