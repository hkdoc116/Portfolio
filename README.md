# How to Add New Files

On your laptop, drag any new files into:
```
~/Projects/portfolio/pdfs
```

Then open your terminal with `⌘ + Space` and type "terminal". Once it is open enter:
```
cd ~/Projects/portfolio
git add .
git commit -m "Adding new files"
git push
```

# How to Update the Homepage

Go to this url: https://github.com/hkdoc116/portfolio/blob/main/index.md
and click the pencil icon.

Make whatever changes you want.

Scroll to the bottom, in the first box under "Commit changes" briefly describe what you did, then click the green "Commit changes" button.

In a minute or two, your site should reflect the changes: https://hkdoc116.github.io/portfolio/

## Template for New Content

Here's a simple template to start from for each entry. We can get all the content in and then work on additional styling later.

Just copy-paste this and modify as needed:
```md
## <a href="pdfs/FILE_NAME" target="_blank">DISPLAY_NAME</a>
DESCRIPTION
```
