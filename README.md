<h1 align="center">
	<img src="https://i.imgur.com/aY78thj.png" width="150px"><br>
    GMGN.ai Wrapper
</h1>
<p align="center">
	An API wrapper for undocumented endpoints at GMGN.ai<br>NOTE: This is for <b>MY</b> personal use, I do not condone the use of this API for any prohibited reason. :)</br>
</p><br>
<p align="center"><b>Note, the GMGN.ai domain is cloudflare protected,<br> meaning some requests will fail to get access to an unprotected endpoint <br>Join the Discord Server and request access<br>https://discord.gg/xxWqZppjht</b></p>
<b>Example, for more examples go <a href="https://github.com/1f1n/gmgnai-wrapper/tree/main/examples">here</a></b><br><br>

```python
from gmgn import gmgn

gmgn = gmgn()

getTokenInfo = gmgn.getTokenInfo(contractAddress="9eLRcHw2G4Ugrnp1p5165PuZsQ2YSc9GnBpGZS7Cpump")

print(getTokenInfo)
```
