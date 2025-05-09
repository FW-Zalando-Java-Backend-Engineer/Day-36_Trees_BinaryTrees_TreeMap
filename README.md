# 🌳 Day-36 Agenda: Trees, Binary Trees & TreeMap in Java

Welcome to Day-36 of our Backend Engineering journey!  
Today, we explore **hierarchical data structures** that power filesystems, compilers, and ordered maps — namely:

- General Trees
- Binary Trees
- TreeMap (Java's sorted map)

By the end of this session, you'll be confident building and traversing tree-like structures in Java, both manually and using Java Collections Framework.

---

## 🎯 Learning Objectives

By the end of this day, you should be able to:

- ✅ Explain the difference between a Tree and a Binary Tree
- ✅ Implement a basic Binary Tree using a custom class
- ✅ Perform In-order traversal of a Binary Tree
- ✅ Use TreeMap to store key-value pairs in sorted order
- ✅ Write JUnit 5 test cases to validate your logic
- ✅ Simulate a directory structure using a tree-based model

---

## 🧠 Key Concepts

### 🌲 Tree (General)
- Hierarchical data structure
- One root, multiple children
- Used in XML parsing, org charts, DOMs

### 🌳 Binary Tree
- Each node has **max two children**
- Common in search trees and parsing
- Traversal orders: In-order, Pre-order, Post-order

### 🗂️ TreeMap
- Java’s sorted map implementation
- Backed by a Red-Black tree
- Auto-sorts keys alphabetically or numerically
- Great for ordered data access and range queries

---

## 🖼️ Visual Aids

### Binary Tree Example
![image](https://github.com/user-attachments/assets/26abd177-55c5-422d-a65f-b66917252873)


**In-order Traversal Output**:
```java
Documents, Downloads, Music, Photos
````

### TreeMap in Action

```java
TreeMap<String, String> files = new TreeMap<>();
files.put("Z", "Zebra");
files.put("A", "Apple");
files.put("C", "Cat");
System.out.println(files); // {A=Apple, C=Cat, Z=Zebra}
```

---

## 🛠️ Project: DirectoryTree

### 👨‍💻 Description:

Build a CLI-based simulation of a folder structure using a binary tree.

* `add("Downloads")` adds a folder
* `listInOrder()` prints folders alphabetically
* Bonus: Store subfolders using TreeMap

### 🧩 Concepts Covered

* TreeNode class & recursive insertion
* In-order traversal for sorting
* TreeMap for key ordering
* Clean OOP design
* JUnit 5 tests

---

## 📦 Technologies Used

* Java 17+
* Maven
* JUnit 5
* IntelliJ IDEA

---

## 🧪 Testing Checklist

* [ ] Test insertion order
* [ ] Test in-order traversal returns sorted results
* [ ] Test edge cases (e.g. duplicates, empty tree)

Use:

```java
assertEquals(List.of("Alpha", "Gamma", "Zeta"), tree.listInOrder());
```

---

## 📝 Assignments

1. **Implement Binary Tree Logic**

   * Create a `DirectoryTree` class and insert folders
2. **Traverse and List**

   * Implement in-order listing
3. **Add Unit Tests**

   * Use `@Test`, `assertEquals`, `@BeforeEach`
4. **Bonus (Optional)**

   * Use `TreeMap<String, DirectoryTree>` to simulate subfolder ordering

---

## 📚 References & Resources

* [Java TreeMap – Baeldung](https://www.baeldung.com/java-treemap)
* [Binary Tree – GeeksForGeeks](https://www.geeksforgeeks.org/binary-tree-data-structure/)
* [Tree Traversals – Medium](https://medium.com/softaai-blogs/exploring-binary-trees-in-java-7c21bf999d88)
* [Java Collections Docs](https://docs.oracle.com/javase/8/docs/api/java/util/TreeMap.html)

---

## 🧠 Thought for the Day

> "Mastering trees means thinking recursively.
> Once you see the pattern, you’ll start modeling everything — from menus to maps — like a Java Jedi. 🌳"

---

## ✅ Deliverables

| Item                     | Status |
| ------------------------ | ------ |
| `DirectoryTree.java`     | ⏳      |
| `DirectoryTreeTest.java` | ⏳      |
| JavaDocs & Comments      | ⏳      |
| README.md Updated        | ⏳      |
| Code Pushed to GitHub    | ⏳      |

---

## 📼 Zoom Recording

🎥 Watch the session here:
🔗 [Day-36 Zoom Recording](_Will be added later_)

---

Great choice — **Edabit** is a solid platform for practicing Java data structure problems in a beginner-friendly environment.

Here's the updated **"Practice Resources"** section for your **Day-36 Agenda README**, with **hand-picked Edabit exercises** that align perfectly with Trees, Binary Trees, and TreeMap concepts.

---

### 📚 Practice Resources – Edabit

Practice your understanding of today's concepts with real Java problems:

#### 🌳 Binary Trees

* ✅ [Height of a Binary Tree](https://edabit.com/challenge/9pD3KKZqFaCqP4FwD)
  *Practice recursive traversal and calculating tree depth.*

* ✅ [Binary Tree Search](https://edabit.com/challenge/SzKXvsJ9EK82fp4HA)
  *Search for a value in a Binary Search Tree.*

* ✅ [Count the Nodes in a Binary Tree](https://edabit.com/challenge/CKqsyasYAvk4ZtPxf)
  *Great for getting used to recursive thinking.*

---

#### 🗂️ TreeMap / Map-like Practice

* ✅ [Sort an Array of Strings Alphabetically](https://edabit.com/challenge/wAdE9gX4bD7zmpbkE)
  *Although not TreeMap-based, this helps reinforce key-ordering logic.*

* ✅ [Frequency of Elements in an Array](https://edabit.com/challenge/Duv3dF5Lrmk5fdy6M)
  *Mimic `TreeMap<String, Integer>` style logic by counting elements with sorting.*

---

📌 **Tip**: Try solving these on Edabit, and then recreate similar logic in your own Java files using the techniques learned in class.

---


