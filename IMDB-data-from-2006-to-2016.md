# IMDB-data-from-2006-to-2016 Dataset

Original Dataset from [IMDB-Movie-Data](./IMDB-Movie-Data.csv)

Explore 2 dataset that given then finding descriptive statistics and summary result in form of sentences/paragraph at least 5 topics.

### Define a question

1.หนังเรื่องไหนมีผลโหวตมากที่สุด <br/>
2.มีหนังกี่เรื่องที่มี rating มากกว่า 8.0 และมีเรื่องอะไรบ้าง <br/>
3.หนังที่ rating สูงที่สุดในแต่ละปีมีเรื่องอะไรบ้าง (แสดงผลลัพธ์แยกเป็นปี 2006-2016) <br/>
4.


### Loading library and dataset
```{R}
# Step 1: Load library
library(dplyr)

# Step 2: Load dataset
survey <- read.csv("https://github.com/sit-2021-int214/006-IMDB-data-from-2006-to-2016/blob/main/IMDB-Movie-Data.csv")
```



### Team: ไอรดา

1.StudentID: 63130500004 กัณฑ์พงษ์ ศรีสุธาภัทร์ <br/>
2.StudentID: 63130500006 กิตติภูมิ อ่วมทอน <br/>
3.StudentID: 63130500029 ณัฏฐกรณ์ โชติภัทรจินดา <br/>