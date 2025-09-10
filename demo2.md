# showcase how q developer can achieve financial data visualization

## Pre-requisite
  - download smaple csv file from https://data.nasdaq.com/databases/WIKIP, or directly from this repo.
  - move the smaple csv file (WIKI-PRICES.csv) to the workspace that you plan to store the scripts of this project.

## Prompt 1
  ```txt
  generate python scripts that can read the .csv file under current directory, and display the data using multiple line charts, each ticker each chart, using different color. the dashboard should be browser visitable.
  ```
  - q chat process showcase (snapshot)
  <img width="1087" height="1044" alt="Screenshot 2025-09-10 at 21 16 44" src="https://github.com/user-attachments/assets/448f01a1-d6b2-47ac-800c-9b4dba48b602" />
  <img width="1081" height="1078" alt="Screenshot 2025-09-10 at 21 17 14" src="https://github.com/user-attachments/assets/5675d7f1-5f5b-4769-a41a-691d5e0a164e" />
  <img width="1082" height="1104" alt="Screenshot 2025-09-10 at 21 17 42" src="https://github.com/user-attachments/assets/b8d0c617-85c3-4629-afe5-a99b15145316" />
  <img width="1078" height="178" alt="Screenshot 2025-09-10 at 21 18 00" src="https://github.com/user-attachments/assets/0f076f95-4935-418f-b15d-23a7ee9378ed" />

  - scriptes generated (snapshot)
  <img width="1076" height="224" alt="Screenshot 2025-09-10 at 21 21 34" src="https://github.com/user-attachments/assets/2fceb078-556b-474a-99a4-049afa67b9d9" />

  - run command
  ```sh
  python3 stock_dashboard.py
  ```
  - error found
  ```txt
  File "/Users/weishiyang/Documents/dev/demo3/stock_dashboard.py", line 2, in <module>
  import plotly.graph_objects as go
  ModuleNotFoundError: No module named 'plotly' how to solve?
  ```
## Prompt 2
  ```txt
  run python3 stock_dashboard.py, found error: Traceback (most recent call last):
  File "/Users/weishiyang/Documents/dev/demo3/stock_dashboard.py", line 2, in <module>
  import plotly.graph_objects as go
  ModuleNotFoundError: No module named 'plotly' how to solve?
  ```
  - q chat process showcase (snapshot)
  <img width="1085" height="1059" alt="Screenshot 2025-09-10 at 21 23 26" src="https://github.com/user-attachments/assets/fd953e9c-9e93-4b51-9115-537d2fd17b99" />

  - run command
  ```sh
  python3 stock_dashboard.py
  ```
  - error found
  ```txt
  run python3 stock_dashboard.py, got error: Traceback (most recent call last):
  File "/Users/weishiyang/Documents/dev/demo3/stock_dashboard.py", line 73, in <module>
  app.run_server(debug=True, host='0.0.0.0', port=8050)
  ^^^^^^^^^^^^^^
  File "/Library/Frameworks/Python.framework/Versions/3.12/lib/python3.12/site-packages/dash/_obsolete.py", line 22, in getattr
  raise err.exc(err.message)
  dash.exceptions.ObsoleteAttributeException: app.run_server has been replaced by app.run. how to solve?
  ```
## Prompt 3
  ```txt
  run python3 stock_dashboard.py, got error: Traceback (most recent call last):
  File "/Users/weishiyang/Documents/dev/demo3/stock_dashboard.py", line 73, in <module>
  app.run_server(debug=True, host='0.0.0.0', port=8050)
  ^^^^^^^^^^^^^^
  File "/Library/Frameworks/Python.framework/Versions/3.12/lib/python3.12/site-packages/dash/_obsolete.py", line 22, in getattr
  raise err.exc(err.message)
  dash.exceptions.ObsoleteAttributeException: app.run_server has been replaced by app.run. how to solve?
  ```

  - q chat proces show case (snapshot)
  <img width="1082" height="440" alt="Screenshot 2025-09-10 at 21 26 59" src="https://github.com/user-attachments/assets/080deccd-e02c-41b6-b665-89bddb2e83e5" />

## Prompt 4
  ```txt
  add simple moving average line for each ticker
  ```
  - q chat process showcase (snapshot)
  <img width="1085" height="670" alt="Screenshot 2025-09-10 at 21 29 34" src="https://github.com/user-attachments/assets/765b5791-ca36-455e-8dc1-ec38b0dc8fa8" />

## Prompt 5
  ```txt
  add simple moving average line, time span is 50 days, for each ticker
  ```
  - q chat process showcase (snapshot)
  <img width="1079" height="852" alt="Screenshot 2025-09-10 at 21 30 57" src="https://github.com/user-attachments/assets/bbbb7a7e-3175-4688-9c9d-c6e5e7e5abe3" />


 ## Prompt 6
  ```txt
  change the displaying color of ticker ZTS from yellow to blue.
  ```
  - q chat process (snapshot)
  <img width="1077" height="520" alt="Screenshot 2025-09-10 at 21 32 45" src="https://github.com/user-attachments/assets/51870f28-8b6c-4863-ae79-82e78646868f" />


## Prompt 7
  ```txt
  change the displaying color of ZUMZ ticker from light green to dark green, displaying coler of ZQK ticker from light purple to dark purple.
  ```
  - q chat process (snapshot)
  <img width="1068" height="622" alt="Screenshot 2025-09-10 at 21 33 59" src="https://github.com/user-attachments/assets/5e6534eb-ab3c-496e-9299-275c6f83a02e" />

## Final Graphs Showcase (snapshot)
<img width="2550" height="990" alt="Screenshot 2025-09-10 at 21 35 06" src="https://github.com/user-attachments/assets/9e02da72-ef42-47de-a4c8-875fe5c3d5fa" />

