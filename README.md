# Run the jekyll server with

## node packages

install needed node packages

    npm install

## to run jekyll

`jekyll serve --watch --baseurl ""` or better run `grunt jekyll`

---

## resize image via command line

    sips -Z 640 *.jpg

## with set height

    sips --resampleHeight 235 assets/images/*


## optimise all `.jpg` files in a folder `path_to_folder`

    - o = overwrite the files

    find ./path_to_folder -name '*.jpg' | xargs jpegoptim -o

## altenative command

    -m = quality of compression

    jpegoptim assets/wedding/ceremony/* -m70

## for png use optipng

