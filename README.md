## `prosecheck`

*A lean,<sup>1</sup> powerful,<sup>2</sup> and portable<sup>3</sup> diagnostic script
for analysing prose in the [command line][2].*

<sup>1. does something useful out of the box without complexity</sup><br></sup>
<sup>2. smart, advanced options for those wanting to use them<br></sup>
<sup>3. written in [POSIX][1] complaint shell scripting language that should run without dependencies on
almost any platform 
</sup>

[1]: http://www.gnu.org/savannah-checkouts/gnu/autoconf/manual/autoconf-2.69/html_node/Portable-Shell.html#Portable-Shell
[2]: http://en.flossmanuals.net/command-line/index/

`prosecheck` does not seek to be authoritative or complete. Rather it targets
sane defaults and reasonable coverage to help authors polish their prose.

## Roadmap

*0.1* <sup>04/22/2016</sup>
- [x] word, character count
- [x] strip html if pandoc is available
- [x] common words minus stop words

![0.1 screenshot](images/v01.png)

*0.2*
- [x] pretty output
- [ ] sentence, paragraph count
- [ ] average sentence length
- [ ] reading difficulty
- [ ] sentence length variation
- [ ] sentence to paragraph ratio
- [ ] move development to dash
- [ ] add time stamp to report.log

*0.3*
- [ ] weasel word index
- [ ] options for short and long outputs
- [ ] modularize
- [ ] installation and usage instructions

*0.4*
- [ ] root report (port from nltk)
- [ ] adverb ratio vs. some writer
- [ ] long introductory clause
- [ ] add tests w/ Travis

*0.5*
- [ ] report generation
- [ ] linting
- [ ] port proselint / prosechck

*0.6*
- [ ] .tex, .docx, and .odt support
- [ ] comparison with other authors
- [ ] json output
- [ ] man page

*0.7*
- [ ] remove dependency on Pandoc to strip html

## Installation, Screenshots

TBA

## Credits

- [Contributors][10]
- List of stopwords from [CoreNLP][11], Stanford NLP

[10]: https://github.com/xpmethod/prosecheck/graphs/contributors
[11]: https://github.com/stanfordnlp/CoreNLP

## Similar tools

- [`conky`](https://github.com/brndnmtthws/conky)
- [`proselint`](https://github.com/amperser/proselint)
- [`textlint`](https://github.com/textlint/textlint)
