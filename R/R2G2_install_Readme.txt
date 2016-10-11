####### UNIX users:
## To install R2G2 (this version runs with R2.14, older R versions should not complain about it)

# 1. make sure that the working directory of R is where you have downloaded R2G2
setwd("MyPathToR2G2_InstallFile")

# 1. If you had a previous version:
remove.packages("R2G2")

# 2. Install the package from the source (*.tar.gz) using the following command:
install.packages("R2G2_1.0-1.tar.gz", repos = NULL, type = "source")

# 3. load the package
require(R2G2)

# 4. Enjoy the help pages and the examples
?R2G2




####### Windows / Mac users:
## To install R2G2 (this version runs with R2.14, older R versions should not complain about it)

# 1. make sure that the working directory of R is where you have downloaded R2G2
setwd("MyPathToR2G2_InstallFile")

# 1. If you had a previous version:
remove.packages("R2G2")

# 2. Install the package from the compiled binary (*.zip file), using the following command:
utils:::menuInstallLocal() # and select the R2G2_1.0-1.zip file. R should then take care of the rest.

# 3. load the package
require(R2G2)

# 4. Enjoy the help pages and the examples
?R2G2