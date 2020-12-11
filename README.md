# hugo-funkwhale-shortcode

A shortcode for Hugo static site generator to include audio hosted on a funkwhale instance

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


### References

- [Funkwhale](https://funkwhale.audio/)
- [Hugo](https://gohugo.io)