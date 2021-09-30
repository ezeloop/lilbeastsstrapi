# Strapi application

A quick description of my strapi application

# First steps: 
    To make it better the experience, i deployed the back 
    Back url: https://lilbeastscenter.herokuapp.com

# Dashboard:
You can access to our dashboard https://lilbeastscenter.herokuapp.com/admin/ with the super admin credentials={
    mail: catsdeveloping@gmail.com
    password: Lilbeasts123$_
}

# API REST
    * https://lilbeastscenter.herokuapp.com/auth/local POST (to get auth token) staff account with editor permission:
    {
    "identifier": "admin@admin.com",
    "password": "112233"
    }

    * https://lilbeastscenter.herokuapp.com/pets GET
    * https://lilbeastscenter.herokuapp.com/pets POST required authorization bearer token provided in /auth/local

    same cases to get,post /animal-types, /sexes, /veterinaries..

    example /pets POST with bearer token jwt: 
    {
    "name": "simon2",
    "age": "2",
    "months": "4",
    "text": "Precious",
    "animal_type": "1",
    "sex": "2"
    },

    