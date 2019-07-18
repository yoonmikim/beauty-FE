# beauty-FE

This beauty-FE repository goes with beauty-BE (https://github.com/yoonmikim/beauty-BE)

A Makeup App where user can sign up, log in, log out, go to homepage with categories with images, emojis, and gifs, go to profile page, view products, filter/sort/search products based on user inputs. If user likes certain products, user can add to cart and/or go to product pages to purchase.

+ Created a Ruby on Rails API backend to parse data from a 3rd party API. (Seed data from a complex data set - external API) 
+ Use of MVC, Serializers, ActiveRecord, and custom RESTful routes to optimize database and schema for backend functionality. (belongs_to / has_many / belongs_to / has_many_through relationships in model)
+ Redux Auth (Authorization & Authentication with Signup / Login / Logout) with Bcrypt & JWT - Use of Bcrypt gem to encrypt and store user password (password_digest) in database on backend.
+ Basic database query optimizations & Background jobs for slow actions (provided a Loading Page for async issues with React.js when fetching data from componentDidMount) 
+ Validations (when signing up as a new user - username should be unique) 
+ Built Frontend with React / React-Redux ( React Component, import { createStore, applyMiddleware, combineReducers, compose } from 'redux', Redux Thunk, import { Switch, BrowserRouter as Router, Route, Link, Redirect, withRouter from 'react-router-dom'; import {connect, Provider} from 'react-redux'; Redux reducers / actions )
+ Interacting with a complex API, Custom CSS & HTML for styling UX & UI,  NPM & yarn packages
+ Implemented JSON Web Tokens while utilizing localStorage to store and encrypt user information client-side.

For ERD / User Story for this project:
https://www.draw.io/#G1RzjECKRlHFrrUU8k3ETonh3ze7iP2-K7
