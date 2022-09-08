# First_Python_Pd_Manipulating_Challenge
I am here to share my experience of my first challenge as an intern.Together with my duo, we manipulated an xls file with python pandas.

![First Insights Project](https://user-images.githubusercontent.com/102270053/189183580-51aaf5d2-a45e-430e-803c-b3f9e99dd951.png)

The Measurement file is the database.

The focus of the challenge is to create more affinity with the pandas library, especially with manipulating dataframes. 

<h3>Enunciate:</h3>

This challenge consists of writing a script that performs the following tasks:

1. Open the file Medição.xls and transform it into a DataFrame with the Pandas Library, this DataFrame should have the following columns:
![image](https://user-images.githubusercontent.com/102270053/189184191-00cfe802-9c0e-4f63-a77c-a0345ee89d6d.png)

2. Select only the 1-minute continuous intervals from the Time column. Example: the script should select only continuous intervals that start at HH:mm:00 and end at HH:mm:59, where HH (hour) mm (minute) must be the same in the interval.
Tip: discard the non-continuous data from the DataFrame.

3. In each selected interval, take the simple average of the data in the MeaValue column.

4. Create a DataFrame with the following columns:
    a) ValueMean: with the average value of each interval;
    b) Time: with the corresponding time in the format HH:mm;
    c) Date: with the day of measurement (present in the Date column).

5. The Challenge must be done in pairs, trios, or individually. The DataFrame must be saved in .xls as "Challenge1 <your names>.xls" and sent via slack along with the script in .ipynb. All steps done in the script must be documented using Markdown.

    
    

</h4> All my and my duo's code is in Portuguese, but I intend to change it to English in the future (= </h4>
