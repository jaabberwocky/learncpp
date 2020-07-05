# Code for Learncpp.com

Code in my bid to learn C++.

## Note
Add this to CodeRuner VSCode extension setting to link multiple files in the same directory together:

`"code-runner.executorMap": {
        "cpp": "cd $dir && g++ -std=c++17 $dir/**.cpp -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    }`
