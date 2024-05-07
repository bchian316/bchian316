- 👋 Hi, I’m @bchian316
- 👀 I’m interested in python coding
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me 
- 😄 Pronouns: he/him
- ⚡ Fun fact: ...

<!---
bchian316/bchian316 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
i made a factorial calculator!

# Online Python - IDE, Editor, Compiler, Interpreter
def factorial(x):
    value = 1
    for i in range(x):
        value *= i+1
    return value
def pascaltriangle(x):
    for i in range(x+1):
        print(int(factorial(x)/(factorial(i)*factorial(x-i))), end = " ")
print(pascaltriangle(19))
