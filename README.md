# queue-calculator-slides
Slidify presentation for the shiny app that let's you explore 
the response time of 3 queueing systems.

To build the slides in Rstudio, run these commands:

    library(devtools)
    install_github('slidify', 'ramnathv')
    install_github('slidifyLibraries', 'ramnathv')
    library(slidify)
    slidify('index.Rmd')

See the presentation here: [http://timwise.github.io/queue-calculator-slides](http://timwise.github.io/queue-calculator-slides "http://timwise.github.io/queue-calculator-slides")

See the app here: [http://timwise.shinyapps.io/queue-calculator](http://timwise.shinyapps.io/queue-calculator/)
