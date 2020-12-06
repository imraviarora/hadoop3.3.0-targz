# How i push Large File Using LFS

Download Git-lfs from this link https://git-lfs.github.com/

    git init
    git remote add origin https://github.com/imraviarora/hadoop3.3.0-targz.git
    git lfs track "hadoop/*.gz"
    git add .
    git commit -m "LF file is pushing"
    git push -u origin master
