# DASC Lab Website

its in progress....



## To edit the website's content

You should really only need to make changes to the `.md` files in `content/` 
Any static resources like images or pdfs should live in `static/images` and `static/pdfs` etc. This allows you to use relative urls to link to it by `../static/images/image.jpg`, for example. Note the use of `../` instead of `static/` 

Once you are happy with the changes, simply push the changes to github and the rest will take care of itself.

## To build the website locally

Simply run 
```
hugo server
```
in a terminal. This will print the url to open to see the website


## Developing the website


