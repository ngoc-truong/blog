# Blog

This is a little blog toy app, just for a refresher on how to setup a ruby on rails project.

## Data scheme

### Posts
* Title:String
* Content:Text
* has_many :comments

### Comments
* content:text
* belongs_to :post

