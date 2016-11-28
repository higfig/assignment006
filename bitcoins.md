% TITLE
% NAME
% DATE

pandoc -t revealjs --template=template-index.html -s --variable theme="black" --variable transition="slide" --variable revealjs-url="./" bitcoins.md -o index.html