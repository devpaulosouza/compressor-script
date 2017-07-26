# compressor-script

A script to compress all images from a directory using [guetzli]

### Requires

[Guetzli]

### Usage:
```sh
# ./compressor-script [folder]
```

If no argument is given, the script uses the current directory for the search


### Example

Given any directory, the script will find the images and compile them using guetzli

```sh
paulo@laptopper:~$ tree folder/
```
folder/
├── another_folder
│   ├── bbc
│   │   ├── crazy.txt
│   │   └── **waterfall.jpeg**
│   └── **duck.png**
├── pie
│   └── apple.doc
└── **potato.jpg**


[guetzli]:<https://github.com/google/guetzli>



