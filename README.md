# scientific-calculator-matlab
"GUI-based scientific calculator with trigonometric functions and real-time graphing capabilities"
# 🧮 Scientific Calculator - MATLAB App

A fully functional GUI-based scientific calculator built using MATLAB App Designer with real-time graphing capabilities.

## 📋 Features

### Basic Operations
- Addition, Subtraction, Multiplication, Division
- Power operations (x^y)
- Parentheses support for complex expressions
- Decimal point support

### Scientific Functions
- **Trigonometry:** sin, cos, tan (in degrees)
- **Logarithm:** Natural log (ln)
- **Square Root:** √x
- **Pi constant:** π (auto-multiply support)

### Advanced Features
- **Real-time Graphing:** Plot sin, cos, and tan functions with one click
- **Interactive UI:** Dark-themed professional interface
- **Error Handling:** Input validation with user alerts
- **Clear Function:** Reset calculator instantly

## 🛠️ Tech Stack
- **Language:** MATLAB
- **Framework:** App Designer
- **Concepts:** GUI Development, OOP, Event-driven Programming, Mathematical Computing

## 🚀 How to Run

### Prerequisites
- MATLAB R2016b or later
- App Designer toolbox

### Steps
1. Open MATLAB
2. Navigate to the project folder
3. Double-click `calculatorapp2.m` to open in App Designer
4. Click **"Run"** button (or press F5)
5. The calculator GUI will launch

### Alternative (If you have the .mlapp file)
1. Double-click the `.mlapp` file
2. Calculator opens automatically

## 📊 Project Structure
- Text field for input/output display
- Number pad (0-9) with responsive buttons
- Operation buttons (+, -, *, /, ^)
- Scientific function buttons (sin, cos, tan, log, sqrt)
- Graph plotting buttons for trigonometric visualization
- Clear button for reset
- Axes component for real-time plotting

## 🎯 Skills Demonstrated
- MATLAB App Designer proficiency
- GUI Design & Development
- Object-Oriented Programming (OOP)
- Event-driven architecture
- Callback function implementation
- String manipulation & expression evaluation
- Mathematical computing
- Data visualization with plotting
- User input validation & error handling
- Professional UI/UX design

## 📸 Features Breakdown

### Calculation Capabilities
```matlab
% Basic: 5 + 3 * 2 = 11
% Scientific: sin(30) = 0.5
% Complex: (5 + 3) * sqrt(16) = 32
% With Pi: 2 * pi = 6.2832
```

### Graphing Functions
- **Plot Sin:** Displays sine wave from 0 to 2π
- **Plot Cos:** Displays cosine wave from 0 to 2π  
- **Plot Tan:** Displays tangent function with asymptotes

## 🔧 Key Functions

- **Expression Evaluation:** Uses `eval()` for mathematical computation
- **String Concatenation:** Builds expressions dynamically
- **Trigonometric Functions:** `sind()`, `cosd()`, `tand()` (degree-based)
- **Error Handling:** `isnan()` checks and `uialert()` for user feedback
- **Plotting:** `plot()`, `fplot()`, and `linspace()` for visualization

## 📝 Future Improvements
- Add memory functions (M+, M-, MR, MC)
- Implement calculation history
- Add keyboard input support
- Include more functions (exp, factorial, combinations)
- Add radian/degree toggle
- Export graph functionality
- Scientific notation support

## 👨‍💻 Author
Aqsa Sajjad

## 📄 License
This project is open source and available for educational purposes.
