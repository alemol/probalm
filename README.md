# Modelo Probabilístico de Lenguaje

Generación de modelo de lenguaje basado en transcripciones de EFINFO del 2017 y 2018.

## Getting Started

Si ya se tienen los modelos generados o se van a usar los modelos de esta distribución solamente hay que tener python3 y kenlm==0.0.0.

### Prerequisites


```
pip3 install kenlm
```

## Running the tests

Ejecutar el script de ejemplo

```
$python example.py 

Loading the LM will be faster if you build a binary file.
Reading models/transcrip_efinfo_noloc_2017-2018.arpa
----5---10---15---20---25---30---35---40---45---50---55---60---65---70---75---80---85---90---95--100
****************************************************************************************************
5-gram model
ese comentario me parece muy bueno .
-21.396728515625
-4.498722076416016 2: <s> ese
-3.3212199211120605 2: ese comentario
-2.713170051574707 2: comentario me
-1.1322113275527954 2: me parece
-1.2292165756225586 3: me parece muy
-2.3222291469573975 4: me parece muy bueno
-5.933176517486572 1: .
-0.24678166210651398 2: . </s>


```

<!-- ### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system
 -->

## Built With

* [KenLM](https://kheafield.com/code/kenlm/) - KenLM Language Model Toolkit

<!-- ## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).  -->

## Authors


* **Alejandro Molina villegas** - [dblp](https://dblp.uni-trier.de/pers/hd/m/Molina=Villegas:Alejandro)


## License


En proceso

<!-- This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details -->



<!-- 
## Acknowledgments
* Hat tip to anyone whose code was used
* Inspiration
* etc -->
