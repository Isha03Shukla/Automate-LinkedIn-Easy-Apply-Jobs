Enter your username, password, and search settings into the `config.yaml` file

```
username: # Insert your username here
password: # Insert your password here
phone_number: #Insert your phone number

positions:
- # positions you want to search for
- # Another position you want to search for
- # A third position you want to search for

locations:
- # Location you want to search for
- # A second location you want to search in 

salary: #yearly salary requirement 
rate: #hourly rate requirement 

uploads:
 Resume: # PATH TO Resume 
 Cover Letter: # PATH TO cover letter
 Photo: # PATH TO photo
# Note file_key:file_paths contained inside the uploads section should be written without a dash ('-') 

output_filename:
- # PATH TO OUTPUT FILE (default output.csv)

blacklist:
- # Company names you want to ignore
```

### Execute
To execute the bot run the following in your terminal:
```
python3 linkedinautomate.py
```

Install all these libraries before running this on your system:
```
selenium
beautifulsoup4~=4.9.1
pandas~=1.3.1
pyautogui~=0.9.50
PyYAML~=5.3.1
lxml
future~=0.18.3
bs4~=0.0.1
future
python-dotenv
packaging
```
