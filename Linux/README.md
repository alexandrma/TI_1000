# Linux

## Table of Contents
- [Beginner](#Beginner)
- [Intermediate](#Intermediate)
- [Advanced](#Advanced)


| No. | Questions |
| --- | --- |
| 1   | What a purpose of Kernel? |
| 2   | What is a user space? |


| No. | Questions                                                                                                  |
| --- | ---------------------------------------------------------------------------------------------------------- |
| 1   | What a purpose of Kernel?                                                                                  |
| 2   | What is a user space?                                                                                      |


| No. | Level | Questions                                                                                                  |
| --- | ----- | ---------------------------------------------------------------------------------------------------------- |
| 1   | Beg   | What a purpose of Kernel?                                                                                  |
| 2   | Beg   | What is a user space?                                                                                      |





## Beginner
**What a purpose of Kernel?**
  * Processes The kernel is responsible for determining which processes are allowed to use the CPU.
  * Memory The kernel needs to keep track of all memory—what is currently allocated to a particular process, what might be shared between processes, and what is free.
  * Device drivers The kernel acts as an interface between hardware (such as a disk) and processes. It’s usually the kernel’s job to operate the hardware.
  * System calls and support Processes normally use system calls to communicate with the kernel.

**What is a user space?**
In a computer operating system, **user space** is the portion of memory containing unprivileged processes run by a user. It is strictly separated from kernel space, the portion of memory where privileged operating system kernel processes are executed.
[link] (https://www.computerhope.com/jargon/u/user-space.htm)








6. ### What is the purpose of the array splice method

The **splice()** method is used either adds/removes items to/from an array, and then returns the removed item. The first argument specifies the array position for insertion or deletion whereas the optional second argument indicates the number of elements to be deleted. Each additional argument is added to the array.

   Some of the examples of this method are,

   ```javascript
   let arrayIntegersOriginal1 = [1, 2, 3, 4, 5];
   let arrayIntegersOriginal2 = [1, 2, 3, 4, 5];
   let arrayIntegersOriginal3 = [1, 2, 3, 4, 5];

   let arrayIntegers1 = arrayIntegersOriginal1.splice(0, 2); // returns [1, 2]; original array: [3, 4, 5]
   let arrayIntegers2 = arrayIntegersOriginal2.splice(3); // returns [4, 5]; original array: [1, 2, 3]
   let arrayIntegers3 = arrayIntegersOriginal3.splice(3, 1, "a", "b", "c"); //returns [4]; original array: [1, 2, 3, "a", "b", "c", 5]
   ```

   **Note:** Splice method modifies the original array and returns the deleted array.

   **[⬆ Back to Top](#table-of-contents)**










## Intermediate
Text

## Advanced
Text









* point 1
* point 2

_Note:_ Note here 

**BOLD** 


# Table of Contents

- [VOL1](#VOL1)
- [VOL2](#VOL2)


# VOL1
texttext

# VOL2
text

<details>
  <summary>Click me</summary>
  
  ### Heading
  1. Foo
  2. Bar
     * Baz
     * Qux

  ### Some Code
  ```js
  function logSomething(something) {
    console.log('Something', something);
  }
  ```
</details>