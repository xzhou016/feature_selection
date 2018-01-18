# feature_selection

A nearest neighbor with leave one out classification algorithm. The entire project is written within Jupyter app in Anaconda using Python 3.6.
## Getting Started
### Prerequisites

[Anaconda](https://www.anaconda.com/) The best python IDE I know

### Installing

Get Anaconda up and running 

Windows

```
Go to [Anaconda's site](https://www.anaconda.com/download/) download and install the app
```
```
install jupyter app within the app
```

Linux

Download the linux installer, should read Anaconda3.5.0.1-Linux-x86_64.sh
Right click the file, select properties, in the permissions tab check "Allow executing file as program, exit
Right click on the folder of file, select open in terminal
In the terminal type
```
./Anaconda3-5.0.1-Linux-x86_64.sh
```
type 'yes' when prompted. 
After installation, intall jupyter within the app

## Running the program

make sure all files from the repo is in jupyter projects folder
launch jupyter, select .ipynd file, select 'cell' from the menu then 'Run All'

### Break down of the
There are three different feature selection techniques
1. Forward selection - adding each feature until the prediction accuracy decreases
1. Backward elimination - eliminate each feature until the prediction accuracy decreases
1. Custom algorithm - a combination of the first two with much more accuracy feature list

## Authors

* **Xiao Zhou** - [xzhou016](https://github.com/xzhou016)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
