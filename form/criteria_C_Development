# Criteria C: Development

## Existing Tools
| Software/Development Tools | Coding Structure Tools          | Libraries      |
|----------------------------|---------------------------------|----------------|
| PyCharm                    | Encryption                      | Flask          |
| Relational databases       | Objects, attributes and methods | sqlite3        |
| SQLite                     | If statements                   | passlib        |
| Python                     | for loops                       |                |
| Chat GPT                   |                                 |                | 
## List of techniques used

1. Flask library/routes
2. For loops
3. If statements
4. Password hashing
5. Interacting with databases
6. Lists
7. Cookies
8. json token






## Success criteria
### 1 The system will have a secured data managing screen for the producer.

The client requested a data managing screen for the producer side. In order to give access only to the producer side we created a simple login system. As the producer side is supposed to be used only by the client, I decided to make the login function that only requires the password but not the username.

### 2 The client will be able to manage its grape info and producer info.



### 3 The program will add the collected data to the database.

The client requested a function that will add csv data to the database. The data will be input in the HTML input box. Both grape data and producer data could be added here.
```.py
    if request.method == 'POST':
        print('St')
        csv_text = request.form['myInput']
        line = csv_text.split('\n')
        db = database_handler("grape.db")

        for b in line:
            i = b.split(',')
            print(i)
            if len(i) == 10:
                sweet, maker, type, location, planting, area, pot_num, date, weight, check_date = i[0],i[1],i[2],i[3],i[4],i[5],i[6],i[7],i[8],i[9]
                print(sweet, maker, type, location, planting, area, pot_num, date, weight, check_date)
                query = f'INSERT INTO info(sweet, maker, type, location, planting, area, pot_num, date, weight, check_date) values ("{sweet}","{maker}","{type}","{location}","{planting}","{area}","{pot_num}","{date}","{weight}","{check_date}")'
                db.run_query(query)
            elif len(i) == 5:
                maker,word,quote,product,image = i[0],i[1],i[2],i[3],i[4]
                query = f'INSERT INTO maker(maker,word,quote,product,image) values ("{maker}","{word}","{quote}","{product}","{image}")'
                db.run_query(query)

        db.close()
```
This is the code for this function. When it gets a request, by splitting with \n, the variable line will get a list of CSV in every row. For every line of the CSV if the length is ten then each csv will be added as grape info, if the length is 6 then each csv will be added as producer info into the database. It means the client can mix both data in one and the code will automatically distribute it to the right table. 

### 4 The customer can access the information about the information of grape and producer.
The client requested a feature that allows customers to see the information about the grapes they bought. Two main information that needs to be provided is the general info and cultivation history. In order to create the UI for this I used a template and block system:
eg. summary of history.html
```.html
{% extends "template.html" %}

{% block content %}
    HTML code for history block is supposed to be here
{% endblock %}

```
summary of template.html
```.html
<!DOCTYPE html>
<html>
<body>
    <div class="content">
        {% block content %}{% endblock %}
    </div>
</body>
</html>

```
When this file is loaded into the browser the variables in the file and the base template are put together and displayed.
This way it allows the user to go back and forth between these two tabs quickly as there is no need to change the whole page.
Using {% block content %} in HTML templates allows you to create a reusable template structure where you can insert specific page content dynamically, making it easier to maintain and customize web pages. It promotes code modularity and reduces duplication.
### 5 The customer can access the information about the grape through a barcode.

In order to allow customers to easily access their grape information, we decided to put a barcode on each bunch of grapes. The barcode will represent a URL with the grape ID in the last directory. The code will refer to the id and search for grape which has the common id from the database.

This code shows how the home screen refers to the last directory from the URL and searches for necessary information.
```.py
@app.route('/home/<int:id>')
def home(id):
    result = get_info(id)

def get_info(id):
    print(id)
    db = database_handler("grape.db")
    data = db.search(f"Select * from info where id = {id}")
    print(data)
    data = data[0]
    #print(id, sweet, maker, type, location)
    return data
```

### 6 The customer can access the information about the grape by searching with the grape ID.

### Pattern recognition
### Abstraction
### Decomposition
I applied decomposition by tackling each success criteria individualy and putting it together afterwards. It made me easier to find the solution of error since individual functions makes it easier to identify the error happening.


## Problem encountered
