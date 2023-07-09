# Dynamic Array (aka list, arrayList):



## Key Points:
1. Arrays in memory.
2. what is dynamic array.
3. dynamic array operations time complexity.
4. implementation of dynamic array.
5. dynamic arrays in java (list, arrayList).




## project:
 ```
 public interface DynamicArray
{

---------------- ------ GUIDE ------ ------------------
// create three variable arrays [] is an array,
    // the count will deal with no of element added by you and
    // the size will with the size of the array[]
    private int array[];
    private int count;
    private int size;
-------------------------------------------------------
    constructor initializes the value ofthe variables
 
    public DynamicArray()
    {
        array = new int[1];
        count = 0;
        size = 1;
    }

-------------------------------------------------------
//make a shift function to work as a helper for you in emplementing other required functions
//shift function -> shifts element of array by number of steps starting from a given index 
// positive number of steps = shifting right
// negative number of steps =  shifting left

private shiftBySteps(int stepsNumber,int startIndex)

example:
array.shiftBySteps(4,17)
// the above function call should shift all array element from index 17 to the end of array 
// it will shift them 4 steps to right  

---------------- ------ END OF GUIDE ------ ------------------


// function add an element at the end of the array
    void add(int data);


// function add an element at given index
    void addAt(int index, int data);

// function to add a subarray at the and of the array
		void addSubArray(int[] subArray );

// function to add a subarray starting from a given index in the array
		void addSubArrayAt(int[] subArray, int index );


    // function makes size double of array
    void growSize();


    // function shrink size of array
    // which block unnecessary remove them
    void shrinkSize();


    // function remove last element or put
    // zero at last index
    void remove();

    // function shift all element of right
    // side from given index in left
    public void removeAt(int index);

// function to remove a subarray from the and of the array
		void removeSubArray(int start , int end );


}
```





helper resources:

[Arrays-1](https://www.youtube.com/watch?v=ALs4QeZ495Y)

[Arrays-2](https://youtu.be/A_CQhz8xsQg)

[Arrays-3](https://www.youtube.com/watch?v=wubHiW8Vhds&list=PLrW6ND2wzt4o4kYvTrk1xQjCLiIumqTL3&index=6)

[References to Objects](https://www.youtube.com/watch?v=fCwliBVEwrw&list=PLrW6ND2wzt4o4kYvTrk1xQjCLiIumqTL3&index=6)



[What if you had to invent a dynamic array?](https://www.youtube.com/watch?v=5AllG-i_yto)

[What if you had to invent a dynamic array? - 2](https://www.youtube.com/watch?v=Ij7NQ-0mIVA)


[implement dynamic array in java](https://www.youtube.com/watch?v=uBYUEcmESTw)