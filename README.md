# compressor-script

A script to compress all images from a directory using [guetzli]

### Requires

[Guetzli]

> To install guetzli easily run the [guetzli-install] script

### Usage:
```sh
# ./compressor-script [folder]
```

If no argument is given, the script uses the current directory for the search


### Example

Given any directory, the script will find the images and compile them using guetzli

```sh
paulo@laptopper:~$ tree folder/

folder/
├── another_folder
│   ├── bbc
│   │   ├── crazy.txt
│   │   └── waterfall.jpeg
│   └── duck.png
├── pie
│   └── apple.doc
└── potato.jpg
```

For the above folder, only the files: waterfall.jpg, duck.png and potato.jpg, will be compressed. All other extensions will be ignored.


[guetzli]:<https://github.com/google/guetzli>
[guetzli-install]:<https://github.com/paulouza/guetzli-install>



