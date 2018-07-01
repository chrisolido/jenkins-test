pipeline {
    agent any
    stages {

        stage('Create and activate a virtual environment'){
          steps{
		    echo 'Create and Activate'
                sh 'cd /var/www/demoapp'
                sh 'virtualenv venv'
                sh '. venv/bin/activate'
                }
        }
        stage('Create as simple Flask application'){
          steps{
		    echo 'Create as simple Flask application
                sh 'pip install flask'
		sh 'cat >/var/www/demoapp/hello.py'
		    from flask import Flask
		    app = Flask(__name__)
 
                    @app.route("/")
                    def hello():
                    return "Hello World!"

                    if __name__ == "__main__":
                    app.run(host='0.0.0.0', port=8080)
                }
        }
                stage('Let’s execute the script'){
          steps{
		    echo 'Let’s execute the script'
                sh 'python hello.py'
                }
        }

}
}
