# Rhetorica Ad Herennium
![retorica](sources/banner.png)
The end goal of this project is to create a functional and nicely formatted eBook version of Harry Caplan's English translation of "[Cicero]: Rhetorica ad Herennium" by the Loeb Classical Library. This book was published in 1954 by the Harvard University Press, ISBN: 9780674994447. More information about this book can be seen at [Harvard University Press](https://www.hup.harvard.edu/books/9780674994447). The book is now in the Public Domain, and the vast majority of the hard work of transcribing this text into digital work has already been done, as can be found at [LacusCurtius](https://penelope.uchicago.edu/Thayer/E/Roman/Texts/Rhetorica_ad_Herennium/home.html).

However, there is no plain text transcription, only the HTML version. Once the HTML source is covnerted into plain text, that text will then be copied and formatted into an eBook format. This repository will serve as an archive for the plain text conversion process. The actual eBook formatting will likely be done in a seperate project, which will later be linked here. The plan is to use the [Standard Ebooks](https://standardebooks.org/contribute/producers) toolkit/process to produce the eBook, as their formatting and style standards are very high.

## TODO
- [ ] Introduction
- [ ] Analysis?
- [ ] Bibliography
- [ ] Book 1
    - [x] plain text
    - [x] markdown
    - [ ] footnotes
- [ ] Book 2
- [ ] Book 3
- [ ] Book 4
- [ ] Footnotes

## Issues/Questions
These are the oddities I have not sorted out exactly how to handle yet.

### Inconsistent chapter/section formatting (Book 1)
The chapter and sections are laid pretty well for the most part it seems, yet there are a couple instances that seems strange and I'm not sure how they "should" be formatted in respects to an ebook. For example, in Book 1 Chapters 10 and 11 are "inline" with the text. Take for example how most chapters are formatted:
>Chapter 1  
>**(sect. 1)** Some paragraph text
>
>Chapter 2  
>**(sect. 2)** Some paragraph text  
> etc...

But for chapters 10 and 11, they are formatted like so:
>Chapter 9  
>**(sect. 16)** Some paragraph text. **(Chapter X.)** Some more text.
>
>...
>
>**(sect. 18)** Some paragraph text. **(Chapter XI.)** Some more text.
>
> ...
>
>Chapter XII.  
>etc....
