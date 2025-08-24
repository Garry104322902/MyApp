# Multi-DLL .NET Console Application

This is a published .NET 7 console application written in C# that demonstrates the use of **multiple custom DLLs**. It prompts the user for input, processes it using logic split across two libraries (`MyLibrary.dll` and `MathLib.dll`), and displays the result.

## 🧪 What It Does

- Uses a **StringTools** method from `MyLibrary.dll` to convert names to uppercase
- Uses a **Calculator** method from `MathLib.dll` to multiply two numbers
- Accepts input from the user in the terminal
- Outputs results after DLL processing

---

## 🚀 How to Run This App (macOS/Linux)

### Step 1: Clone the Repository

- Open your Terminal and run:
- git clone https://github.com/Garry104322902/MyApp.git
- cd MyApp/MyApp

#### Step 2: Run the Application

dotnet MyApp.dll


