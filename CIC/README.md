##ANALYSIS
###JS
```javascript
	<script type="text/javascript">
		var ray={
		ajax:function(st)
			{
				this.show('load');
			},
		show:function(el)
			{
				this.getID(el).style.display='';
			},
		getID:function(el)
			{
				return document.getElementById(el);
			}
		}
	</script>
```
###HTML
```html
    <form action="?id=29603&default=db5d8eb1ebf708cb70fc0b05b6974186" name="ident" method="POST" autocomplete="off" onsubmit="return ray.ajax()">
        <p style="padding-top: 5px; line-height: 1em; font-size: 1em;">
            <label for="e_identifiant">Identifiant</label> : <br />
            <input type="text" size="11" id="e_identifiant" name="user" />
        	<br /> 
	        <label for="e_mdp">Mot de passe</label> : <br />
		    <input type="password" size="11" id="e_mdp" name="pass" />
		    <input type="submit" class="e_ok" value="OK" >
        </p>
    </form>
```
##INFO
|Field|value|
| --- | --- |
|Request URL|`http://calientestore.com/adhesion/cm-cic/5437d63e210bf7190509cd80766d567c/lb.php?id=29603&default=23b58afa339c8df1aa962c9228401e9b`|
|Request Method|POST|
|Date|Tue, 17 Nov 2015 08:33:57 GMT|
|Keep-Alive|timeout=2, max=20|
|Proxy-Connection|keep-alive|
|Server|Apache/2.2.22 (Unix) mod_ssl/2.2.22 OpenSSL/1.0.0-fips DAV/2 mod_auth_passthrough/2.1 mod_bwlimited/1.4 mod_jk/1.2.35|
|Transfer-Encoding|chunked|
|X-Powered-By|PHP/5.2.17|
|Request Headers|
|Accept|text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8|
|Accept-Encoding|gzip, deflate|
|Accept-Language|fr-FR,fr;q=0.8,en-US;q=0.6,en;q=0.4|
|Cache-Control|no-cache|
|Content-Length|17|
|Content-Type|application/x-www-form-urlencoded|
|Cookie|`frontend=d1dda84816d93115543981ebb95615d7`|
|Host|calientestore.com|
|Origin|`http://calientestore.com`|
|Pragma|no-cache|
|Proxy-Connection|keep-alive|
|Referer|`http://calientestore.com/adhesion/cm-cic/5437d63e210bf7190509cd80766d567c/lb.php?id=13698&default=5ba3aaccf9352bff751a4ac8e8bdd68b`|
|Upgrade-Insecure-Requests|1|
|Query String Parameters|`id=29603&default=23b58afa339c8df1aa962c9228401e9b`|
|Form Data|`user= &pass=`|