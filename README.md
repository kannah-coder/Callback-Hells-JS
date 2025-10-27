# Callback-Hells-JS
# Callback Tasks Example

This project demonstrates how to execute asynchronous tasks in sequence using **callbacks** in JavaScript.  
Each task simulates an async operation with `setTimeout`.

 

##  How it works
1. `task1` runs first (3s delay).
2. After completion, `task2` runs (2.5s delay).
3. Then `task3` runs (1s delay).
4. Finally `task4` runs (1.5s delay).
5. At the end, `"ALL TASKS ARE COMPLETED"` is logged.

This is an example of **callback hell**, where nested callbacks make code harder to read and maintain.  
Later, this can be improved using **Promises** or **async/await**.

## Run the project
Just open `index.html` in your browser and check the console output.

Folder/
└── callback/
    ├── callback.html
    └── c1.html

