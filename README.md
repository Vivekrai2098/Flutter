
# Tutorial of Flutter

That is the Tutorial wihich i follow to create the Flutter project and for the succesfull growing android development carrier 


# Road Map of Flutter

![App Screenshot](https://raw.githubusercontent.com/Vivekrai2098/Flutter/main/flutter-image.jpg)



 

### comments in flutter 📝

```dart
**single comments**
//That is my first comments

**Multiline comments**
/*
that is my first flutter application multi line comments
*/


```
#### **Dart is the case senstive programming language**⚠️


### The flutter obey the bodmas rules and precedence rules 

```dart
**that is the bodmas rules follow by dart programming 🔢**

void main(){
  print(75/5+2);
}

output 17

**that is the precedence rules follow by Dart programming**

void main(){
  print(75/(5+2));
}

output:-10.714285714285714


```
### flutter data type
<datatype> <veriable>=<value>

1. INT 
```
int first_value=22;
```
2. String 
```
String Second_value="22";
```
3. bool :- true or false 
```
bool Second_value=true;
```
4. double 
```
double Second_value=12.90282928;
```

5. dynamic :- That is store any value generaly we not preferred to use dynamic value
```
dynamic anyvalue=22;
```
**You also explore the veriable instance to use .**
## Some example method 
1. String 
```
void main(){
  String value="22";
  print(value.codeUnits);
}

```
explanation \
Okay, so imagine you're making an app in Dart, right? Now, Dart is a programming language used for making apps, especially for things like Android, iOS, or web apps. Ab, imagine you're building a messaging app like WhatsApp.

Now, let's talk about `codeUnits` in Dart. Think of it as a way to break down a string (like a message) into smaller pieces, called code units. Ab dekho, har character ko ek number se represent kiya jata hai, aur `codeUnits` un numbers ko lekar aata hai.

So, let's say you want to count the number of characters in a message. You could use `codeUnits` to do that. It lets you convert each character into a number, and then you can count those numbers.

For example, let's say you have the message "Hello" in your app. `codeUnits` will give you `[72, 101, 108, 108, 111]`. Now, you count these numbers, you'll know there are 5 characters in "Hello".

So, basically, `codeUnits` helps you work with strings more efficiently in your Dart app. It's useful for things like counting characters, comparing strings, or doing other stuff where you need to break down strings into smaller pieces and work with them.

2. Hashcode
```
void main(){
  String value="22";
  print(value.hashCode);
}
```
explanation \
Arre bhai, `hashCode` ka scene kya hota hai? Dekh, jab hum kisi object ko identify karna chahte hain, toh hum uska hash code use karte hain. Hash code ek unique number hota hai jo har object ke sath associated hota hai.

Samjha, imagine tu ek library hai aur har book ko ek unique number de raha hai, jise hum kehte hain hash code. Ab agar koi specific book chahiye, toh librarian ko sirf uska unique number yaad rakhna padega, bas. Waise hi, agar hum kisi object ko compare karna chahte hain, toh hum uske hash code ko use karke kar sakte hain.

Jaise, agar hum ek list mein kuch items store kar rahe hain, aur hume pata karna hai ki kya koi item list mein hai ya nahi, toh hum hash code use kar sakte hain. Hash code ki madad se hum quickly identify kar sakte hain ki kya wo item list mein present hai ya nahi.

Lekin yaad rakh, hash code unique nahi hota har case mein. Thoda tricky hota hai, kuch objects ka hash code same bhi ho sakta hai. Lekin generally, hash code ki help se hum object ko identify aur compare karne mein madad lete hain.

3. isEmpty
```
void main(){
  String value="22";
  print(value.isEmpty);
}

```
explanation \
"isEmpty" ek function hai jo check karta hai ki kya koi list, set ya string khali hai ya nahi. Agar kuch bhi nahi hai toh ye true return karta hai, warna false.

For example, imagine tum apne phone mein contacts dekh rahe ho aur dekhte ho ki koi bhi contact nahi hai. Tab tum "isEmpty" function ka istemal karke check kar sakte ho ki kya tumhara contacts list khali hai ya nahi.

Aur ye kaam real life mein bhi hota hai. Maan lo, tum ek shopkeeper ho aur tumhare paas ek dukaan hai. Subah jab dukaan khulti hai, pehle tum apne stock ka pata lagate ho. Agar dukaan mein koi samaan nahi hai, toh tum keh sakte ho "dukaan khali hai" ya "isEmpty". Agar dukaan mein samaan hai, toh wo isEmpty nahi hogi.

So basically, isEmpty ka istemal karte waqt, hum dekhte hain ki kya kuch bhi hai ya nahi.

4. isNotEmpty
```
void main(){
    String value= 22;
    print(value.isNotEmpty);
}
```
explanation \
isEmpty" in Dart checks if a list, set, or string is empty. "isNotEmpty" does the opposite; it checks if a list, set, or string is not empty. So, when you use "isNotEmpty" in Dart, you're checking if something has something in it, like if a box isn't empty.

5. length
```
void main(){
  String value="22";
  print(value.length);
}
```
explanation \
that is the find the length of the string of the dart programming language

6. runes
```
void main() {
  String hindiText = "नमस्ते";
  for (var char in hindiText.runes) {
    print(new String.fromCharCode(char));
  }
}


```
explanation \
runes are like special characters or symbols, especially useful when dealing with non-English text, like Hindi, in your code. Imagine you want to deal with Hindi text in your Dart program, but Dart mainly understands English. Here, runes come into play.

So, in simple words, runes help you handle text that goes beyond the English alphabet. When you type something in Hindi or any other non-English language in your Dart program, it's stored as a sequence of Unicode characters. Runes let you deal with these characters effectively.

7. runtimeType
```
void main(){
  dynamic  value="string";
  print(value.runtimeType);
}
```
explanation \
In Dart programming, the runtimeType method is used to get the runtime type of an object. This means it tells you the type of an object when your program is running. For example, if you have a variable var a = 5, and you want to know what type a is, you can use a.runtimeType to find out that it's an integer.

---
```
**fill all the missing methods**
```
---

### notes
After when we assign the value in the container or veriable we also change the value in the future example:-

```
void main(){
  dynamic value=33;
  value =44;
  value="jaishrree";
  print(value);
}
```
also use arithmetic assignment 
```
void main(){
  dynamic value=30;
  value+=-50;
  print(value);
}
```