# Fix8 Overview

Fix8 (Fixate) is an Open-Source GUI Tool for Working with Eye Tracking Data in Reading Tasks. FIx8 includes a novel semi-automated correction approach for eye tracking data in reading tasks.  The proposed approach allows the user to collaborate with an algorithm to produce accurate corrections in less time without sacrificing accuracy.


[![Watch the video](./src/.images/step2.jpg)](https://youtu.be/Zw2uO3IE2vI?si=h1yYnNQag-0Q7lVe)


# Main Features ⭐

- Drift correction including manual, assisted (semi-automated), and automated correction.
- Fully customizable and interactive visualization.
- Synthetic data and distortion generation including full control of word skipping, within-line and between-line regressions.
- Filters: high-pass, low-pass, outlier, merge, and outside screen filters.
- Analyses including hit-test and eye movement metrics like First-Fixation Duration, Single-Fixation Duration, and Total Time.
- Data Converters: EyeLink data, ASCII, CSV, and JSON are supported.
- Request a feature by making an issue on this page!

# Executables  💻
- Windows: 
- Mac: coming soon!
- Linux: coming soon!

# Run Fix8 from code 🚀
To use run Fix8 from the Python code, follow these steps:

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/nalmadi/fix8.git
    cd fix8
    ```

2. **Create a Virtual Environment:**

    It's recommended to use a virtual environment to manage dependencies and isolate your project's environment. If you don't have `virtualenv` installed, you can install it using pip:

    ```bash
    pip install virtualenv
    ```

    Then, create a virtual environment:

    ```bash
    virtualenv venv
    ```

    Activate the virtual environment:
    
    **On Windows:**
    
    ```bash
    venv\Scripts\activate
    ```

    **On macOS and Linux:**
    
    ```bash
    source venv/bin/activate
    ```

3. **Install Requirements:**

    Once the virtual environment is activated, install the project dependencies from the `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Tool:**

    Navigate to the `src` folder and run the tool:

    ```bash
    cd src
    python fix8.py
    ```


5. **Deactivate the Virtual Environment:**

    When you're done using the tool, deactivate the virtual environment:

    ```bash
    deactivate
    ```



### Keyboard Shortcuts ⌨️​
a: 		next fixation

z: 		previous fixation

space: 		accept suggestion

backspace: 	delete current fixation

j:      move the selected fixation to the left

l:      move the selected fixation to the right

i:      move the selected fixation upward

k:      move the selected fixation downward


* * *


# Citation 📝

Please cite our paper if you user this tool, the citation is bellow:

TBD

          
