# CommentsNutekSecurity
Comment on my posts from nuteksecurity.com/blog

## Add a comment

To add a comment, please follow these steps:

1. Use editor to add a comment file (`Markdown` is used to process the
style) to the `hello-world` or any other `folder` named the same as the `blog post`.

2. The comment file should be named whatever you want, but it should have the `.md` extension. Place in the folder following the name of article.

```bash
git clone https://github.com/NutekSecurity/CommentsNutekSecurity.git
cd CommentsNutekSecurity
mkdir hello-world # or any other folder named the same as the blog post 
# (skip if the folder already exists)
cd hello-world
touch my-comment.md # use your name instead of my-comment
echo "Hello, Nutek!" > my-comment.md
git add my-comment.md
git commit -m "Add a comment"
git push
```