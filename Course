### Introduction 

---
---

## 🧱 C# Data Types

C# provides a rich set of data types that fall into two main categories: **Value Types** and **Reference Types**. Understanding the difference between them is essential when writing efficient and predictable code.

---

## 🔹 Value Types
Value types store their **data directly in memory**. When assigned to another variable, the value is **copied**, not referenced.

### Common Value Types
| Type | Keyword | Example | Notes |
|------|----------|---------|-------|
| Integer | `int` | `int age = 25;` | 32-bit signed integer |
| Long | `long` | `long big = 123456789;` | 64-bit signed integer |
| Float | `float` | `float price = 19.9f;` | Requires suffix `f` |
| Double | `double` | `double rate = 3.14;` | Default floating type |
| Decimal | `decimal` | `decimal salary = 999.99m;` | High precision, `m` suffix |
| Boolean | `bool` | `bool isActive = true;` | `true` / `false` |
| Character | `char` | `char grade = 'A';` | Single Unicode character |
| Structs | `struct` | Custom structs | User-defined value types |
| Enumeration | `enum` | Custom enums | Named constants |

---

## 🔹 Reference Types
Reference types store a **reference (pointer) to the memory location** where the data actually exists. Assigning them copies the reference, not the data.

### Common Reference Types
| Type | Keyword | Example | Notes |
|------|---------|---------|-------|
| String | `string` | `string name = "Omar";` | Immutable Unicode text |
| Object | `object` | `object data = 123;` | Base type of all types |
| Classes | `class` | `class Person { }` | User-defined reference type |
| Arrays | `[]` | `int[] nums = {1,2,3};` | Fixed-size sequence |
| Interfaces | `interface` | `interface ICar { }` | Contract for classes |

---

## 🔸 Nullable Types
Value types can become nullable using the `?` suffix:

```csharp
int? value = null;
```

---

# 🔤 C# Strings & String Methods

## 📘 What Is a String?
A **string** in C# is a sequence of characters used to represent text.  
Strings are **reference types**, but they are **immutable**, meaning once created, they cannot be changed in memory — any modification creates a *new* string.

---

## ✨ Declaring Strings

```csharp
string name = "Omar";
string message = "Hello, World!";
string empty = string.Empty;
string multiLine = @"This is
a multi-line
string.";
```


# 🔍 Key Features of Strings

- **Strings are immutable.**  
- **They support Unicode.**  
- **They are reference types.**  
- **They support escape sequences** (`\n`, `\t`, `\"`, `\\`).  

---

# 🧰 Common String Methods

## 1️⃣ Length  
Returns the number of characters.

```csharp
string name = "Omar";
int len = name.Length; // 4
```

---

## 🔠 String Methods in C#

### 1️⃣ ToUpper() / ToLower()

```csharp
"omar".ToUpper();   // "OMAR"
"HELLO".ToLower();  // "hello"
```

---

### 2️⃣ Substring()

Extract part of a string.

```csharp
string text = "HelloWorld";
string part = text.Substring(0, 5); // "Hello"
```

---

### 3️⃣ Contains()

```csharp
"Hello World".Contains("World"); // true
```

---

### 4️⃣ Replace()

```csharp
"Hello Omar".Replace("Omar", "Ali"); // "Hello Ali"
```

---

### 5️⃣ Trim() / TrimStart() / TrimEnd()

```scharp
"  hello  ".Trim(); // "hello"
```

---


### 6️⃣ Split()

```csharp
string data = "red,blue,green";
string[] colors = data.Split(',');
```

---


### 7️⃣ Join()

```csharp
string result = string.Join("-", colors);
// Output: "red-blue-green"
```

---


### 8️⃣ StartsWith() / EndsWith()

```csharp
"file.txt".EndsWith(".txt"); // true
```

---


### 9️⃣ IndexOf()

```csharp
"Hello".IndexOf("e"); // 1
```

---


### 🔟 String Interpolation

```csharp
string name = "Omar";
string msg = $"Hello {name}, welcome!";
```

---


### 🔄 Convert to String

```csharp
int age = 25;
string result = age.ToString();
```

---

### ✅ Summary

Strings are immutable text objects.

Provide many built-in methods to search, transform, and manage text.

String interpolation ($"") is the cleanest way to format text.
