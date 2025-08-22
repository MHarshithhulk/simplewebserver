# EX01 Developing a Simple Webserver

# Date:22/08/2025
# AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

# DESIGN STEPS:
## Step 1:
HTML content creation.

## Step 2:
Design of webserver workflow.

## Step 3:
Implementation using Python code.

## Step 4:
Serving the HTML pages.

## Step 5:
Testing the webserver.

# PROGRAM:
```
from http.server import HTTPServer, BaseHTTPRequestHandler
content = """
<!DOCTYPE html>
<html>
	<head>
		<title>REVENUE TABLE</title>
	</head>
	<body bgcolor="cyan">
	<h1>TOP FIVE REVENUE GENERATING SOFTWARE COMPANIES</h1>
	<table border='3' cellspacing="4" cellpadding='3'>
		<tr>
			<th>RANK</th>
			<th>ORGANIZATION</th>
			<th>FY</th>
			<th>REVENUE</th>
		</tr>
		<tr>
			<td>1</td>
			<td>MICROSOFT</td>
			<td>2022</td>
			<td>$203.08 billion</td>
		</tr>

		<tr>
			<td>2</td>
			<td>GOOGLE</td>
			<td>2022</td>
			<td>$173.02 billion</td>
		</tr>

		<tr>
			<td>3</td>
			<td>IBM</td>
			<td>2019</td>
			<td>$123.58 billion</td>
		</tr>
		<tr>
			<td>4</td>
			<td>ORACLE</td>
			<td>2019</td>
			<td> $46.07 billion</td>
		</tr>
		<tr>
			<td>5</td>
			<td>SAP</td>
			<td>2019</td>
			<td>$32.97 billion</td>
		</tr>
	</table>
	</body>
</html>
```

# OUTPUT:
<img width="1919" height="1199" alt="Screenshot 2025-08-22 134306" src="https://github.com/user-attachments/assets/8b72a7b9-aa61-4fa4-9adc-e925047d15ac" />


<img width="1919" height="1199" alt="Screenshot 2025-08-22 134325" src="https://github.com/user-attachments/assets/9f89b50c-28f7-4375-a8e1-b0a809d43cdb" />

# RESULT:
The program for implementing simple webserver is executed successfully.
