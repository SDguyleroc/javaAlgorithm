# java Algorithm
### What is an Algorithm
An algorithm is a series of defined instructions that perform a task

#### algorithm for making sandwich
1. Retrieve the ingredients.
2. Slice the bread.
3. Spread mayo or mustard on the bread.
4. place ham and cheese on the bread.
5. Combine pieces of the bread.

* When giving instructions to a computer, every step must ne defined.

- almost every code instruction you write is part of an algorithm.
- Mnay different algorithms can complete the same task, but they each have defined instructions.
- May different algorithms that can solve the same problem.
- Some are more efficent than the other.
- What if you had to make a trip to the store for each sandwich ingredient?
- To make an algorithm more efficient, you often have to make an assumption about your data
- The assumptions must be true in order to receive the expected output from an alorithm.
- a slow working algorithm is preferred to a fast algorithm that sometimes doesn't work.
 ```java
 public class Algorithms {
// not effience
    public static int findMaxinun(int a, int b, int c){
        if (a>b){
            if(a>c){
                return a;
            }

           
           
        }  
        if (b>c){
                return b;
            }
            return c;
    }

    //effecient
    public static int findMaxinunFaster(int a, int b, int c){
        int max =a;

        if(b>max){
            max=b;
        }
        if (c>max) {
            max=c;
            
        }

        return max;
    }

    public static void main(String[] args) {
        System.out.println(findMaxinunFaster(1, 2, 3));
        System.out.println(findMaxinunFaster(8, 8, 1));
        System.out.println(findMaxinunFaster(3, 2, 3));
        System.out.println(findMaxinunFaster(1, 1, 9));
        System.out.println(findMaxinunFaster(1,9,9));
    }

}
```
# Big-O 
Big-O notation allows us to compare algorithms
independently of input size.

### comparing Search Alorithms

algorith 1:

* The item we are searching for will be the first or last element in the list
* ### O(1) or constant time
* #### Best Case: O(1)
*  #### Worst Case: O(1)
  Algorithm 2
  * The item we are searching for could be anywhere within list
  * #### Best Case: the item we are looking for is the first item
  * #### Worst Case: it is not in list and we would have to check every single element. 





























