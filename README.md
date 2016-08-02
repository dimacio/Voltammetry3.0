# Voltammetry3.0

Files for exploring the possibilities of a digital-first (digtially native) textbook. After downloading the files to a folder on your computer, launch `R`, navigate to the folder and set it as your working directory, and run the following command in the console:

```
rmarkdown::render_site()
```

When complete, you should see a `_Site` folder in your directory. To view the website, find the `index.html` file in the `_site` folder and view it in your browser. If you edit and change any of the `.Rmd` files, you can use

```
rmarkdown::render_site("filename.Rmd")
```
to update the corresponding `.html` files. If you wish to add a new page to the website, create it as a `.Rmd` file, add it to appropriate place in the `_site.yml` file, and refresh the whole website using the command

```
rmarkdown::render_site()
```
