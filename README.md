# Clojure HTML Library Comparison
## Hiccup
Pure data. It does one thing and it does it well. Hiccup style syntax is 
compatible with enlive, reagent, and sneeze.
## Enlive
Enlive is great for reading .html files into clojure and running transformations 
on them using selectors. It falls short in hiccup compatibility and 
composability. Enlive is very macro heavy and this can cause issues when your 
usage isn't quite in the target use case.
## Enliven
Enlive v2. It's not quite baked and edible. 
## Sneeze
Hiccup with enlive style selector transformations. When you want the simplicity
of hiccup with the flexibility of enlive.
## Others
Never used these, no comment.
- Selmer
- Fleet
