
## Self Introduction

My name is **Aditya KS**, and I originally come from a **Mechanical Engineering** background. My journey into the field of **Data Science and Analytics** has been both unconventional and transformative. After a life-changing accident, I had to reevaluate my career path and search for a role that was less physically demanding. During this time, I discovered **Data Science**—and I was instantly captivated. The more I explored its potential to solve real-world problems and drive meaningful innovation, the more fascinated I became. What started as curiosity quickly turned into an obsession, and I decided to fully immerse myself in this exciting field.

To formalize my transition, I completed a **Master’s in Data Science** program at **SMEC Labs Pvt. Ltd.**, where I gained hands-on experience with cutting-edge tools and technologies, including **Python, Hadoop, TensorFlow, Spark**, and advanced machine learning frameworks.

I have worked on several impactful projects, such as:
- **Humanoid Robot Simulation**: Developing a clinical reception robot prototype with advanced capabilities like crowd detection, path planning, gesture recognition, and multilingual NLP.
- **Mental Health Support Platform**: Creating an intelligent web platform powered by AI/ML for personalized recommendations and multilingual user interaction.
- **Data Science Projects**: Conducting exploratory data analysis and implementing machine learning models on datasets such as **Airbnb bookings**, **credit card fraud detection**, and **heart attack prediction**.

I specialize in programming languages like **Python**, **Java**, and **Scala**, **Big Data** tools like **Hadoop** and **Spark**, and visualization tools such as **Tableau**, **Power BI**, and **Advanced Excel**. My background in Mechanical Engineering, combined with my relentless passion for Data Science, has given me a unique perspective and problem-solving approach.

## Computer Setup

- **Operating System**: Windows (main OS), Ubuntu (via WSL for Gazebo).
- **Installed Software**: Python, Java, Scala, Anaconda, IDEs like VS Code, PyCharm, IntelliJ IDEA, Eclipse, MySQL Workbench.

## Social Profiles

- [StackOverflow Profile](https://stackoverflow.com/users/23706957/aditya-ks)

## Skills

- **Programming Languages**: Python, Java, Scala
- **Big Data Technologies**: Hadoop, Spark
- **Data Visualization Tools**: Tableau, Power BI, Advanced Excel

---

## Code Examples

### Convert Number to Digits

```python
def num_to_dgt(number):
    digits = []
    number = abs(number)  # Handle negative numbers
    
    while number > 0:
        digits.insert(0, number % 10)
        number //= 10
        
    return digits
```

### Remove Duplicates from an Array

```python
def remove_duplicates(arr):
    return list(set(arr))
```

### Convert Text to Pig Latin

```python
def to_pig_latin(text):
    words = text.split()
    pig_latin_words = []
    
    for word in words:
        pig_latin_word = word[1:] + word[0] + "ay"
        pig_latin_words.append(pig_latin_word)
    
    return ' '.join(pig_latin_words)
```

### Convert Text from Pig Latin to English

```python
def from_pig_latin(text):
    words = text.split()
    english_words = []
    
    for word in words:
        english_word = word[-3] + word[:-3]
        english_words.append(english_word)
    
    return ' '.join(english_words)
```

### Rotate List by `k` Elements

```python
def rotate_list(arr, k):
    n = len(arr)
    k = k % n  # To handle cases where k is larger than the list size
    arr[:] = arr[k:] + arr[:k]  # Rotate the list in place
    return arr

arr = [1, 2, 3, 4, 5, 6]
rotate_list(arr, 2)
```

