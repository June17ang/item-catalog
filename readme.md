## Udacity Full Stack Wed Developer Nanodegree - Project 2 [Item Catalog]
#### Project Description
Developing an application that provides a list of items within a variety of categories, as well as provide a user registration and authentication system.

#### Prerequisites
Python 2.7+
Vagrant
VirtualBox

#### How to Run
- Install <a href="https://www.vagrantup.com/downloads.html" tips="click redirect to installation page">Vagrant</a>

- Install <a href="https://www.virtualbox.org/wiki/Downloads" tips="click redirect to installation page">Virtualbox</a>

- Clone git project <br>
```git clone https://github.com/June17ang/item-catalog.git```

- Change directory <br>
```cd item-catalog```

- Setup virtual environment <br>
```vagrant up```

- SSH into vagrant <br>
```vagrant ssh```

- Change to project directory <br>
```cd /vagrant```

- Initial new database table into item-catalogs database <br>
```python dbsetup.py```

- Initial seeder into database <br>
```python seeder.py```

- Launch applicate
```python app.py```

- Click on <a href="http://localhost:5000" tips="click redirect to application">here</a>
 **OR** paste http://localhost:5000 to browser
