# personal-blog
A personal blogging website where one can create and share their opinions and other users can read and comment on them. Additionally,
the application displays random quotes to inspire users. 

## Live Link
[View Site](https://flask-blog-personal.herokuapp.com/)

## Screenshot

<img src="">

## User Stories

* View the blog posts on the site
* Comment on blog posts
* View the most recent posts
* Receive an email alert when a new post is made by joining a subscription
* See random quotes on the site
* Sign in to the blog
* Create a blog from the application
* Delete comments that I find insulting or degrading
* Update or delete blogs I have created

## BDD
| Input                    | Behaviour                       | Output                                       |
| -------------------------| ------------------------------  | -------------------------------------------- |
| Subscribe to mail list              | Input the email               | Redirect you to the index page               |
| Writer login                    | Take you to home page           | Redirect you to the Homepage                 |
| Create a blog post by filling blog form          | Write your blog and post it to blogs    | Your blog is displayed  in index page                     | 
| User comment on the Blog post plus a nickname | Write your feedback and post it | Your feedback is displayed under the blog post   |
| Writer delete a blog post       | Deleting the blog post from the database    | The blog post will be deleted and not appear on the page                  |
| Writer update a blog post       | Updating the blog post in database    | The blog post will be updated                |
| Writer delete a comment         | Deleting the blog post in database    | The comment will no longer appear under the post                   |

### Prerequisites

* Python 3.8

## Running the Application
* To run the application, in your terminal:

        $ python3 manage.py runserver
      
        
## Testing the Application
* To run the tests for the class file and check if it functions well:

        $ cd tests
        $ python3 test_comment.py
        $ python3 test_post.py
        $ python3 test_quote.py
        $ python3 test_user.py
        


## Built With

* [Python](https://www.python.org/) for backend
* [HTML](https://html.com/) for web app structure
* [Bootstrap](https://getbootstrap.com/) and [Javascript](https://www.javascript.com/) for styling
* [Heroku](https://heroku.com)

## Authors

* **Victor  Kibocha** - *Initial work* - [Github](https://github.com/TechVictorKE/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Inspired by Moringa School
