
<script>
	let name = '';
  let title = '';
  let add1 = '';
  let add2 = '';
  let phone = '';
  let cell = '';
  let email = '';
</script>
<style>
	section {
  width: 600px;
  display: grid;
  justify-content: center;
}
	div {
  color: #fff;
  padding: 12px;
  display: inline-block;
}
</style>
   <section><div>
	   <h1>
	GSNCA Email Signature
</h1>
<input bind:value={name} placeholder="enter your name"><br>
<input bind:value={title} placeholder="enter your title"><br>
<input bind:value={add1} placeholder="enter your address line 1"><br>
<input bind:value={add2} placeholder="enter your address line 2"><br>
<input bind:value={phone} placeholder="enter your phone"><br>
<input bind:value={cell} placeholder="enter your cell"><br>
<input bind:value={email} placeholder="enter your email">
<table border="0" cellpadding="5px">
  <tbody>
    <tr>
      <td><p>105 Heatherbrooke Park Drive<br>Birmingham, AL 35242</p></td>
      <td><p>1515 Sparkman Drive NW<br>Huntsville, AL 35816</p></td>
      <td><p>2121 9th Street, Suite C<br>Tuscaloosa, AL 35401</p></td>
    </tr>
  </tbody>
</table>
<br><br>
<p><em>
	Select Signature then Copy and Paste into your signature. Keep source formatting.</em>
</p>
<table>
	<tr>
		<td><img height="48" src="http://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/image002.png" width="103"> <span style="font-family: arial; font-size:12px"><br>
		<strong>{name}</strong></span><br>
		<span style="font-family: arial; font-size:12px">{title}</span><br>
		<span style="font-family: arial; font-size:12px"><span style="color:#00ae58"><strong>Girl Scouts of North&#8211;Central Alabama</strong></span><br>
		<span style="font-family: arial; font-size:12px">{add1}</span><br>
		<span style="font-family: arial; font-size:12px">{add2}</span><br>
		<span style="font-family: arial; font-size:12px">800-734-4541</span></span></td>
	</tr><!--<tr><td><img src="http://placehold.it/150x5"></td></tr>-->
	<tr>
		<td><span style="font-family: arial; font-size:12px"><strong>p:</strong> {phone}</span><br>
		<span style="font-family: arial; font-size:12px"><strong>c:</strong> {cell}</span> <br><span style="font-family: arial; font-size:12px"><a href="mailto:[[EMAIL]]" style="color:#00AE58; border-width:0px; border:0px;">{email}</a></span></td>
	</tr>
	<tr>
		<td><span><a href="https://www.girlscouts.org/en/cookies/share-joy.html"><img border="0" height="169" src="http://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/cookie_pattern_3.jpg" width="300"></a></span></td>
	</tr>
	<tr>
		<td><span style="font-family: arial; font-size:12px"><span style="color:#00ae58"><strong>Virtual Programs with Girl Scouts at Home</strong></span><br>
		<span style="font-family: arial; font-size:12px"><a href="https://www.girlscoutsnca.org/en/events/girl-scouting-at-home.html" style="text-decoration:none !important; text-decoration:none">Click here to learn more!</a></span></span></td>
	</tr>
	<tr>
		<td><span style="font-family: arial; font-size:12px"><span style="color:#00ae58"><strong>Join Girl Scouts</strong></span><br>
		<span style="font-family: arial; font-size:12px"><a href="https://www.girlscoutsnca.org/en/about-girl-scouts/join.html" style="text-decoration:none !important; text-decoration:none">Click here to Join today!</a></span></span></td>
	</tr>
	<tr>
		<td>
			<a href="http://girlscoutsnca.org" style="text-decoration:none !important; text-decoration:none"><img border="0" height="27" src="http://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/image006.png" width="28"></a> <a href="https://www.facebook.com/gsnca" style="text-decoration:none !important; text-decoration:none"><img border="0" height="30" src="http://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/image008.png" width="16"></a> <a href="https://twitter.com/girlscoutsnca" style="text-decoration:none !important; text-decoration:none"><img border="0" height="32" src="http://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/image010.png" width="25"></a> <a href="https://www.youtube.com/user/gsnca" style="text-decoration:none !important; text-decoration:none"><img border="0" height="29" src="http://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/image012.png" width="22"></a> <a href="https://www.instagram.com/girlscoutsnca" style="text-decoration:none !important; text-decoration:none"><img border="0" height="28" src="http://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/image016.png" width="22"></a> <a href="https://www.pinterest.com/gsnca/" style="text-decoration:none !important; text-decoration:none"><img border="0" height="31" src="http://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/image020.png" width="25"></a>
		</td>
	</tr>
	   </table></div>
	</section>


