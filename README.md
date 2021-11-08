# lazymc

_Note: this is a prototype and currently incomplete._

`lazymc` puts your Minecraft server to rest when idle, and wakes it up when
players connect.

Some Minecraft servers (especially modded) use an insane amount of
resources when nobody is playing. `lazymc` helps with this by stopping your
server when idle, until a player connects again.

`lazymc` functions as proxy between clients and the server. It handles all
incoming status connections until the server is started and then transparently
proxies the rest.

## Demo

![Demo video](https://user-images.githubusercontent.com/856222/140804726-ba1a8e59-85d9-413b-8229-03be84b55d51.mp4)

<details><summary>Click to see screenshots</summary>
<p>

![Sleeping server](./res/screenshot/sleeping.png)
![Join sleeping server](./res/screenshot/join.png)
![Starting server](./res/screenshot/starting.png)
![Started server](./res/screenshot/started.png)

</p>
</details>

## License
This project is released under the GNU GPL-3.0 license.
Check out the [LICENSE](LICENSE) file for more information.
