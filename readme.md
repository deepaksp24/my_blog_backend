python -m venv venv
venv/Scripts/activate
pip install -r requirements.txt
pip freeze > requirements.txt

feature to be add

1.  blog view for home page
    1.1 blog model (b_id,b_title,b_content,b_status,u_id,time)
    1.2 api to fetch random blog (api/home)
    1.3 what should it return  
     1.3.1 id,title,time (opt. user)
    1.3.2 only 5
    1.4 in click on particulra blog (api/home/<name:title> or <int:number>)
    1.4.1 on click get the blog details from db

2.authication
2.1 create a login icon on top right of the page
2.1.2 there should be 'unknow' if not logged else some 'dp' logged in
2.1.3 there should
2.2 crete a login screen which will be optional
