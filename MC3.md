# Mini Challenge 3 - PostCreateView

STR:
1. Inside of posts/views.py create the class PostCreateView that inherits from CreateView (the generic class)
2. Remember to fill the following attributes: {template_name, fields, model}
3. On fields I only want to display the: title, subtitle, body and status
4. Create the url that's going to handle that view
5. Add the form into the templates/posts/new.html and make it crispy!
5. 1. Don't forget about csrf security
6. Add a new li inside of the navbar.html that redirect us to create a new post (call it 'New Post')


# Mini Challenge 4 - PostUpdateView

STR:
1. Inside of posts/views.py create the class PostUpdateView that inherits from UpdateView (the generic class)
2. Add the attributes: template_name, model and fields
3. On fields I only want to display the: title, subtitle, body and status
4. Create the url that handles this view
5. Link the url to the button inside of the detail view
6. Add the respective form to the edit.html inside of templates/posts (if that file doesn't exists, create a new one)