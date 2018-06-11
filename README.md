## Week 1 — Google Summer of Code 2018

Now the first week has started, I started to work on various aspects of the project. I started to research more on Scrolling Ticker Algorithm and also started did some other work which are as follows

### CWRU HPC Accounts
Every student working under Red Hen Labs is given a CWRU Account for High Performance Computing (HPC) which does the training of a model more speedily than a ordinary laptop. Our administrator Mark Turner asked some of the credentials and our RSA public keys. 
Our accounts had been made in a single day and also our credentials were given to login into CWRU cluster to work on.







You can use the [editor on GitHub](https://github.com/BurhanUlTayyab/burhanultayyab.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown

burhantwo@Burhan-Ubuntu:~$ ssh bxu22@redhen1.case.edu
Last login: Sun May 27 09:18:00 2018 from 103.255.7.30
bxu22@redhen1:~$ ssh bxu22@rider.case.edu
Last login: Sat May 19 06:53:44 2018 from redhen1.cosi.cwru.edu
[bxu22@hpc3 ~]$


Syntax highlighted code block

# Header 1
## Header 2
### Header 3

Bulleted
List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

### Problem and Installations
To solve the scrolling ticker problem, I used a modification of early fusion algorithm, basically what an early fusion algorithm does is, it check for changes in a ticker and a stopping point (which tells that one news has been finished and other has been started), if the changes are above some threshold value, it appends the ticker to a blank ticker otherwise it lets it go, it is very simple but powerful algorithm which can easily detect the changes in a ticker with upto 90% accuracy, to do the early fusion algorithm, I started needed to install OPENCV which is an open source Computer Vision Library. I needed to install OPENCV from source rather than install its pip version because pip version doesn’t support Video processing, so what I did was

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/BurhanUlTayyab/burhanultayyab.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
