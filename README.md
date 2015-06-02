# blog-posts
This is a repo for the blog posts

### Installation
`run conda env create --file environment.yml`
`source activate blog_aei`
to create and then activate a conda environment for this.

### Local editing
First run `PORT=8000 make devserver` and visit http://localhost:8888.
Then, either edit an existing article in /content, or create a new one.
for now, you can only use markdown for articles. See
http://docs.getpelican.com/en/latest/content.html for more documentation on writing articles.

