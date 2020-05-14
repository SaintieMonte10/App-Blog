# Blog-App

## Author
- Clares Richards

## Description
- This is an application that allows users to sign in or sign up and post blogs abroad.It also allows them to comment and delete on the blogs they have created

## BDD

| Behaviour             |                Input                |                                                                       Output |
| :-------------------- | :---------------------------------: | ---------------------------------------------------------------------------: |
| Load the page         |          **On page load**           |                               Get all posts, Select between signup and login |
| Select SignUp         | **Email**,**Username**,**Password** |                                                            Redirect to login |
| Select Login          |    **Username** and **password**    | Redirect to page with app blogs based on  commenting section |
| Select comment button |             **Comment**             |                                             Form that you input your comment |
| Click on submit       |                                     |       Redirect to all comments tamplate with your comment and other comments |

## Development Installation

To get the code..

1. Cloning the repository:

```bash
https://github.com/SaintieMonte10/App-Blog.git
```

2. Move to the folder and install requirements

```bash
cd blog-post
pip install -r requirements.txt
```

3. Exporting Configurations

```bash
export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
```

4. Running the application

```bash
python3.6 app.py server
```


## Technology used

- Python3.6
- Flask
- Heroku
- Javascript
-HTML & CSS

## Contact Information

claremonte53@gmail.com

## Live Link To Project


## License
 
 Licensed under[MIT license](./LICENSE)