# Starboard Stats
This is a server-generic Discord starboard analysis program. It is configured for Dyno but should be very easily adaptable to a different bot.

It was initially used for a well-loved community, _The Crockery_ of some thousand-count people, as a sort of "the last two years in summary" presentation. So I'd definitely recommed giving it a whirl, it was fun to do and well-received! Feel free to reach out if you want more info for using this on your own server.

## Installation

You are solely responsible for any data fetching you do (see the `.ipynb` and the `.example.json` for details on what kind of data this takes in). That is, you must have **the explicit approval of the Discord server in use**.

This code was tested on [Python 3.12](https://www.python.org/downloads/). You'll need to `pip install numpy pandas matplotlib`. [VS Code](https://code.visualstudio.com/) with [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) is recommended to read the .ipynb file.

Note that the fonts and colours are a tad opinionated! Root around in 'Matplotlib styling' if you want to add a bit of your own flair to the graphs.

## License

Discord Starboard Stats by [Mia yun Ruse](https://yunru.se) has the license [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).

In other words, it is public domain. Please use it however you want!
Use it in another server, if you have permission to do so!