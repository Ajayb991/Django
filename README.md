Step1 : Launch an Instance 

Step2 : Connect to your instance and follow steps to [ Install Python and Django ]

        sudo apt update
        sudo apt install python3
        sudo apt install python3-pip
        sudo apt install python3-venv
        python3 -m venv venv
        source venv/bin/activate
        pip install django
        python -m django --version

Step3: Make a Dir and take a pull from GIT

Step4: source venv/bin/activate ( make venv file active)

Step5: Go to the actual path where you have your project details and run below commands,

       python manage.py makemigrations
       python manage.py migrate
       python manage.py runserver 0.0.0.0:8000

Step6: Now if you wanna display you content using instance IP , Update that in setting.py file under ALLOWED HOST : []       

       
