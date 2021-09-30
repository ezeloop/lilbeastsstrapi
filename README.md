# Strapi application

A quick description of your strapi application

# Fist steps: 
    * install all the dependencies
    * required postgree db istalled
    settings = {
        username: postgres,
        password: admin
    }
    
    * Starting: npm start
    and now, you can use the rest api http://localhost:1337/, you can get information as a no autenticaded user, from /pets, /animal-types, /sexes, /veterinaries to create data, you need to authorize (POST) at http://localhost:1337/auth/local with staff account with editor permission:
    {
    "identifier": "admin@admin.com",
    "password": "112233"
    }
    then with the jwt now, put a "bearer token" at the autorization, and now you can create and for example, you can http://localhost:1337/pets (POST):
    {
    "name": "simon2",
    "age": "2",
    "months": "4",
    "text": "Precious",
    "animal_type": "1",
    "sex": "2"
    },

# Dashboard:
You can access to our dashboard http://localhost:1337/admin/ with the super admin 
credentials={
    mail: catsdeveloping@gmail.com
    password: Lilbeasts123$_
}

