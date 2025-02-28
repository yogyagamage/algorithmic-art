## Highways of Hell

<img src="https://github.com/yogyagamage/algorithmic-art/blob/main/theo/imgs/theo1.png?raw=true" alt="" width="500" height="500">

<img src="https://github.com/yogyagamage/algorithmic-art/blob/main/theo/imgs/theo2.png?raw=true" alt="" width="500" height="500">

<img src="https://github.com/yogyagamage/algorithmic-art/blob/main/theo/imgs/theo3.png?raw=true" alt="" width="500" height="500">

The data that drives this artwork comes from [Theo]{https://github.com/chains-project/theo}, yet another tool named after a rock band, this time a nod to [Third Eye Blind]{https://en.wikipedia.org/wiki/Third_Eye_Blind}.

Theo can monitor the execution of Java programs, and track various types of system accesses such as file operations, network activity, and shell command executions. It works with both test and production workloads, and generates reports that capture these interactions. This artwork takes two such reports (one from testing, one from production) and maps them side by side. Each type of access is represented by a different shape. For example, triangles for file reads and squares for file writes create the visual paths you see here.

This piece is inspired by [this article]{https://paulvanderlaken.com/2020/05/02/generative-art-computer-design-painting/}.

Its name comes from the concept of [dependency hell]{https://en.wikipedia.org/wiki/Dependency_hell} and, of course, the legendary anthem [Highway to Hell by AC/DC]{https://en.wikipedia.org/wiki/Highway_to_Hell}.

To view it, clone this project and open the index.html file in your browser.
If you face any issues related to accessing the json data files, you can try launching a [local server](https://developer.mozilla.org/en-US/docs/Learn_web_development/Howto/Tools_and_setup/set_up_a_local_testing_server) instead.
