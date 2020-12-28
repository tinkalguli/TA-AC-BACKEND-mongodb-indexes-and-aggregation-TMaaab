writeCode

Insert the data present in users.json into local mongodb database using `mongoimport` into a database called sample and collection named as users.

Write aggregation queries to perform following tasks.

1. Find all users who are active.

2. Find all users whose name includes `blake` case insensitive.

3. Find all males.

4. Find all active males.

5. Find all active females whose age is >= 25.

6. Find all 40+ males with green eyecolor.

7. Find all blue eyed men working in 'USA'.

8. Find all female working in Germany with green eyes and apple as favoriteFruit.

9. Count total male and females.

10. Count all whose eyeColor is green.

11. Count all 20+ females who have brown eyes.

12. Count all occurences of all eyeColors.
    Something like:-

```
blue -> 30
brown -> 67
green -> 123
```

13. Count all females whose tags array include `amet` in it.

14. Find the average age of entire collection

15. Find the average age of males and females i.e. group them by gender.

16. Find the user with maximum age.

17. Find the document with minimum age.

18. Find the sum of ages of all males and females.

19. Group all males by their eyeColor.

20. group all 30+ females by their age.

21. Group all 23+ males with blue eyes working in Germany.

22. Group all by tag names i.e. use \$unwind since tags are array.

23. Group all males whose favoriteFruit is `banana` who have registered before 2015.

24. Group all females by their favoriteFruit.

25. Scan all the document to retrieve all eyeColors(use db.COLLECTION_NAME.distinct);

26. Find all apple loving blue eyed female working in 'USA'. Sort them by their registration date in descending order.

27. Find all 18+ inactive men and return only the fields specified below in the below provided format

```js
{
  name: "",
  email: '';
  identity: {
    eye: '',
    phone: '',
    location: ''
  }
}
```
