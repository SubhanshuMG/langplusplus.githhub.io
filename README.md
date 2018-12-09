# lang++
lang++ is a collection of code editing tools with support for non-English languages.

Most, if not all, of the world's widely-used programming languages are English-based, making it difficult for many non-English speakers to learn to code. Since computer knowledge and programming skills are becoming increasingly valuable in today's world, the lack of support for other languages puts non-English speakers at a disadvantage.

As of now, lang++ supports one language-programming language combination (Chinese-C++). Currently working to increase number of languages, improve the use of links to external resources, and integrate machine learning to to provide better assistance to users.

## Instructions/Notes
To see the online editor in action, download ACE Editor files from ACE Github, index.html, and main.css (from "css" folder) files, then open index.html using browser. Or, go to [https://langpp.weebly.com](https://langpp.weebly.com).

Translation is in "translations" folder in the form of .csv file.

Data string in demo is initialized to Chinese-to-C++ translations. Working on better way to parse translations from aforementioned .csv files; currently, have been converting .csv files to .txt, then using Python parse program in "parse" folder to convert data in .txt to one single string (with '\n' substituted for newlines). In addition, due to only having one language-programming language combination, index.html is set permanently to this combination for now.

## Goals for lang++

 * Improve method for parsing translation data
 * Make demo dynamic
 * Incorporate machine learning
    * Improve translation accuracy
    * Consider context when suggesting autocompletions
    
## Contributing

Please read [CONTRIBUTING.md](https://github.com/fibanneacci/langplusplus/blob/master/CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](https://github.com/fibanneacci/langplusplus/blob/master/CODE_OF_CONDUCT.md) to learn more about contributing to lang++.

## Built With
* ACE Editor - [ACE Editor Github](https://github.com/ajaxorg/ace)

## Authors
* **Anne Li** - *Initial work* - [fibanneacci](https://github.com/fibanneacci)

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details