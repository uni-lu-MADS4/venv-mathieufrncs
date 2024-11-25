# How to run

## Step 1: Set Up the Environment

1. **Create a Python Environment**

    First, open a terminal at the repository. Then, create a virtual environment either:

   - With Python venv

        ```sh
            python -m venv venv
            source venv/bin/activate
        ```

   - With Conda

        ```sh
            conda create --name myenv python=3.12
            conda activate myenv
        ```

2. **Install required packages**
   
When your environment is successfully activated, run this command:

```sh
    pip install -r requirements.txt
```

## Step 2: Run the code

Execute this command in your terminal with the environment activated:

```sh
    python Q12.py
```

You should get an output like this:

```sh
    UTC time: 2024-11-25 11:22:27.064866 and Local time: 2024-11-25 11:22:27.064866+01:00
    Timezone: Europe/Luxembourg
    Timezone name: CET
    Timezone abbreviation: CET
    Timezone offset: 1:00:00
    difference between UTC and local time: 1.0 hours
```