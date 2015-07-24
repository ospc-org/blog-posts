# blog-posts
This is a repo for the blog posts

### Installation
run `conda env create --file environment.yml` and then 
`source activate blog_aei`
to create and then activate a conda environment for this.

### Local editing

#### Mac and Linux
First run `PORT=8888 make devserver` and visit http://localhost:8888.
If you are running an IPython Notebook sever, you may need to shut it down first. 
Then, either edit an existing article in /content, or create a new one.
for now, you can only use markdown for articles. See
http://docs.getpelican.com/en/latest/content.html for more documentation on writing articles.

#### Windows
Correct the path to your `pelican.exe` in `pmake.cmd` and `devserver.cmd`, then
simply
```
pmake html
devserver
```