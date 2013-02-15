# Introduction

MarkdownBook is a ebook framework which is extracted from [ProGit Project](https://github.com/progit/progit/) 

## Requirement

### Pandoc ###

	http://johnmacfarlane.net/pandoc/installing.html

### Texlive ###

	http://www.tug.org/mactex/morepackages.html

### Ruby & Gems

#### Mac ####

- Install ruby & rubygems
- Install rdiscount

	gem install rdiscount

#### Linux ####

	$ yum install ruby calibre rubygems ruby-devel rubygem-ruby-debug rubygem-rdiscount

	
# Usage

## Make PDF Book

### Make All Translation  

	./makepdfs

### Make Specific  Tranlation

 Make English Version

	./makepdfs en

 Make Chinese Version

	./makepdfs zh

## Customize MarkdownBook

### latex/template.tex

- Book Title: edit title entry 
- Author: edit author entry
	

### latex/config.yml

- Bookname: edit the default:bookname or corresponding language's
- Thanks : edit the default:thanks or corresponding language's
