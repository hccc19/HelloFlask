# HelloFlask
First micro blog using Flask

- What is Flaskr?
  A sqlite powered thumble blog application

- How do I use it?

	1. go to the project directory
	
	2. using virtualenv, create - active virtual environments
	  	
	   virtualenv env
	   . env/bin/activate
	
	3. install flask using pip
	   pip install flask
	
	4. Instruct flask to use the right application
           export FLASK_APP=flaskr.py

	5. initialize the database with this command:
	   flask initdb

	6. now you can run flaskr:
	   flask run

		 * Serving Flask app "flaskr"
 		 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)


## Test:
	
	run `python /flaskr_tests.py` to see the tests pass.

