# hugo-funkwhale-shortcode

A shortcode for Hugo static site generator to include audio hosted on a **Funkwhale** instance. Funkwhale is a community-driven project that lets you listen and share music and audio within a decentralized, open and federated network.

### Usage

**Simplified notation**

```
{{< funkwhale open.audio 84899 >}}
```
Only tracks (no album), and only default config.

**Notation with named params**

```
{{< funkwhale host="open.audio" id="84899" type="track" >}}
```
You cans specify `type` (track or album) and `height` (numeral value: default 138).

**Notation for album**

```
{{< funkwhale host="open.audio" id="8493" type="album"  height="330 >}}
```

Note: you _must_ adjust the `height`.

### References

- [Funkwhale](https://funkwhale.audio/)
- [Hugo](https://gohugo.io)