# INTRODUCTION

I'm doing some research with git and PHP with Angular. The main idea is make a project with some microservices.
Maybe a chat room in the future.

  * Post site(Front)
  * Users
  * Posts

## How to clone this repository

I've divided this repository using submodules. If you want to clone all of them:

```
git clone --recurse-submodules -j8 https://github.com/fedegallar/blog-project-php.git
```

## Post site
This is the main site where we can manage our posts with our users and with our comments.

## Users
We'll use this micro service to:
  * Register new users
  * Sign In
  * Edit user.

## Posts
  * Create new posts.
  * Edit posts.
  * Comment posts.