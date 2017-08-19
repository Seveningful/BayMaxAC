# Baymax Custom Network training

If you want to have a custom set to train your own network you're at the right place !

#### Requirements :

* BaymaxLib

Yes, you do need to download the 200MB library that contains dl4j so you can have your own network otherwise it will load the data from the public network. _If you have a BungeeCord based server there will be a way (in the future) to only have the BaymaxLIB on the BungeeCord proxy and not on every Spigot server._

Once you've downloaded the **BaymaxLIB** start your server and be sure that the `use-public-network` is set to `false` in the **config.yml** file.

Now you'll have to choose which category you want to train :
* 0 | Vanilla Aim
* 1 | Aimbot
* 2 | KillAura

Once you've choosen the category you want to train, execute the command `/train <category-id> <time-in-seconds>`. And fight **normally** for the time you've set in the command.

Once you've trained **every** category a decent amount of times, go to the `Baymax/AI/train` folder and a `data.csv` file will be there. Copy it. Delete the `network.zip` and `data.csv` contained in the `Baymax/AI/` folder and paste the new `data.csv` file.

Restart your server, and let the plugin generate a new network based on the dataset you created !
