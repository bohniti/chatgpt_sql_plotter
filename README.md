# chatgpt_sql_plotter
A Python package that leverages the ChatGPT API to generate SQL queries for Pandas or PySpark DataFrames and visualize the results using Plotly.

## Structure
------------
chatgpt_sql_plotter/
  │
  ├── chatgpt_sql_plotter/
  │   ├── __init__.py
  │   ├── chatgpt_interface.py  # Module to interact with ChatGPT API
  │   ├── sql_generator.py      # Module to generate SQL queries
  │   ├── dataframe_query.py    # Module to execute SQL on Pandas/PySpark DFs
  │   ├── plotter.py            # Module to generate Plotly plots
  │   └── utils.py              # Miscellaneous utility functions
  │
  ├── tests/
  │   ├── __init__.py
  │   ├── test_sql_generator.py
  │   ├── test_dataframe_query.py
  │   └── test_plotter.py
  │
  ├── examples/
  │   └── example_usage.py
  │
  ├── .gitignore
  ├── setup.py
  └── README.md
------------
