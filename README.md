find ./ -type f -exec sed -i '' -e "/categories: \[\]/d" {} \;

FFS
  new page:
    remove the DOCTYPE and header (css, etc)
    run this on the doc to remove extra lines: :%s/.*br><\/p.*//

Resurrecting:
- we seem to be past where we were on wordpress... no no more new to import from there
- i think we need to move the text from the large document into the website format and then post for each page forward
- probably need to take the formatted text document and use something to convert it to html... the above lines seem to suggest
    dont remember what program used to do this though... 'apple converted space' tells me it was on mac and not google docs
    probably textedit?
- okay... so seems the jekyll theme takes in MD and converts to html...


