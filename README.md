To use the consolidated reference bib file, please create a submodule in your paper or proposal repo.

git submodule add git@github.com:CactiLab/consolidated-reference-bib-file.git

Then, add the following to your .tex file

\bibliography{./consolidated-reference-bib-file/consolidated-ref}

YOu may also need to do 

git submodule update --recursive --remote