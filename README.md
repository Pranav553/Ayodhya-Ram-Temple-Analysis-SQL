# Ayodhya-Ram-Temple-Analysis-SQL
## Question
**1.)Retrieve information about the Ram Mandir?**
```mysql
select * from Temple;
```
Result:
![Q1](https://i.imgur.com/dDhIpp5.png)

**2.)List all construction phases for the Ram Mandir?**
```mysql
select * from  costructionphase;
```
Result:
![Q2](https://i.imgur.com/W0qXAJ2.png)

**3.)Find the total amount of donations received for the Ram Mandir?**
```mysql
select sum(amount) as total_amount_donation from donations;
```
Result:
![Q3](https://i.imgur.com/tIeX2B8.png)

**4.)Get details about the architecture of the Ram Mandir?**
```mysql
select * from architecture;
```
Result:
![Q4](https://i.imgur.com/eiIm0Uc.png)

**5.)Retrieve events associated with the Ram Mandir?**
```mysql
select * from event;
```
Result:
![Q5](https://i.imgur.com/mFJU4UC.png)

**6.)Find donors who contributed more than 50000 towards the Ram Mandir?**
```mysql
select * from  donations where amount >=5000;
```
Result:
![Q6](https://i.imgur.com/0kzQf89.png)

**7.)Find the start and end dates of the construction phases for the Ram Mandir?**
```mysql
select  startdate ,completiondate from constructionphase;
```
Result:
![Q7](https://i.imgur.com/qyRK8qR.png)
