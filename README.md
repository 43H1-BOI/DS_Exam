## **Internal 1st 2K23**
---
### **Q1. What is a Stack?**

A **stack** is a linear data structure that follows the **LIFO** (Last In, First Out) principle.  
- This means the last element added to the stack is the first one to be removed.  
- Think of it like a stack of plates where you can only add or remove plates from the top.  

#### **Key Operations of a Stack**:
1. **Push**: Add an element to the top of the stack.  
2. **Pop**: Remove the top element from the stack.  
3. **Peek/Top**: View the top element without removing it.  
4. **IsEmpty**: Check if the stack is empty.  

---

### **Uses of Stack**

1. **Expression Evaluation and Conversion**:  
   - Convert infix expressions to postfix or prefix.
   - Evaluate postfix expressions.

2. **Backtracking**:  
   - Used in algorithms like **Depth-First Search (DFS)**.
   - Helps in undo operations in text editors.

3. **Function Call Management**:  
   - Recursion uses a stack to keep track of function calls.

4. **Parenthesis Matching**:  
   - Used to check if parentheses/brackets in an expression are balanced.

5. **Data Reversal**:  
   - Reverse a string or data using a stack.

6. **Syntax Parsing**:  
   - Compilers use stacks to parse expressions, syntax trees, and code generation.

---

### **Example**

**Stack Operations**:
1. Push elements: `[10, 20, 30]` → Stack becomes `[10, 20, 30]`.  
2. Pop element: Remove `30` → Stack becomes `[10, 20]`.  
3. Peek/Top: Top element is `20`.






## **Internal 2nd 2K23**
---
### **Q5. Construct a binary tree from the given In-order and Pre-order traversal sequences.**
In-order sequence: D, B, E, A, F, C
<br>Pre-order sequence: A, B, D, E, C, F


### Constructed Tree:

```
       A
      / \
     B   C
    / \  /
   D  E F
```

---