# CHETANA SAI VEERLAPATI
###### American Jazz Museum
The museum preserves the history of American jazz music, with exhibits on **Charlie Parker, Duke Ellington, Louis Armstrong, Ella Fitzgerald and others**. Nested within the museum is a fully functioning **jazz club, The Blue Room**, which holds live performances multiple nights a week.

---

## NEAREST AIRPORT
**KANSAS CITY INTERNATIONAL AIRPORT** is the nearest airport for American jazz museum.
Directions to Reach American jazz Museum:
1. Exit from the Arrival Section.
2. Reach to the pickup stop.
    1. You can Pick Cab which is right to the Arrivals.
    2. You can Pick Shuttle Service Which is left of the Arrivals
3. Give the destination details.
4. Destination is 20 miles via I-29 N
5. Pay the amount for Cab Driver.

* Nearby Hotels:
    * Sheraton Kansas City Hotel at Crown Center.
    * Indigo Kansas City - The crossroads.
* Nearby Academy:
    * Kansas City MLB Urban Youth Academy.
    * Lincoln college preparatory academy.

**[AboutMe](AboutMe.md)**

---

## PLACES TO VISIT
|       City        |       Important Location      |       Time to Spend       |
| ----------------- | ----------------------------- | ------------------------- |
|    Warangal       |           Bhadrakali Temple   |           1 Day           |
|    Hyderabad      |           Forum Srujana Mall  |           1 Day           |
|    Delhi          |           Red Fort            |           2 Days          |
|    Mumbai         |           Gateway of India    |           2 Days          |

---

## Quotes
> "The purpose of our lives is to be happy." — *Dalai Lama*
> 
> "If you want to live a happy life, tie it to a goal, not to people or things."– *Albert Einstein*

---

## Code Fencing
> I was asked to write my own implementation to remove duplicated values in an array. Here is what I have created. But after tests with 1,000,000 elements it took very long time to finish. Is there something that I can do to improve my algorithm or any bugs to remove ?
<https://stackoverflow.com/questions/17967114/how-to-efficiently-remove-duplicates-from-an-array-without-using-set>
```
const array = [1, 1, 1, 3, 3, 2, 2];

// Method 1: Using a Set
const unique = [...new Set(array)];

// Method 2: Array.prototype.reduce
const unique = array.reduce((result, element) => {
  return result.includes(element) ? result : [...result, element];
}, []);

// Method 3: Array.prototype.filter
const unique = array.filter((element, index) => {
  return array.indexOf(element) === index;
});
```
<https://css-tricks.com/snippets/javascript/remove-duplicates-from-an-array/>
