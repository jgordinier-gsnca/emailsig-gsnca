
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.1/css/bulma.min.css">
<script>
	let name = '';
  let title = '';
  let add1 = '';
  let add2 = '';
  let phone = '';
  let cell = '';
  let email = '';
</script><section class="section">
<div class="container"><div class="columns"><div class="column">
	   <h1 class="title">
	GSNCA Email Signature
</h1>
	<label class="label">Name</label>
<input class="input m-1" bind:value={name} placeholder="enter your name">
		<label class="label">Title</label>
<input class="input m-1" bind:value={title} placeholder="enter your title">
			<label class="label">Address line 1 (see addresses below)</label>
<input class="input m-1" bind:value={add1} placeholder="enter your address line 1">
				<label class="label">City, State Zip</label>
<input class="input m-1" bind:value={add2} placeholder="City, State Zip">
				<label class="label">Phone</label>
<input class="input m-1" bind:value={phone} placeholder="enter your direct line">
					<label class="label">Cell</label>
<input class="input m-1" bind:value={cell} placeholder="enter your cell">
					<label class="label">Email</label>
<input class="input m-1" bind:value={email} placeholder="enter your email">
	<h3>Addresses</h3>
<table class="table" border="1" cellpadding="5px">
  <tbody>
    <tr>
      <td><p>105 Heatherbrooke Park Drive<br>Birmingham, AL 35242</p></td>
      <td><p>1515 Sparkman Drive NW<br>Huntsville, AL 35816</p></td>
      <td><p>2121 9th Street, Suite C<br>Tuscaloosa, AL 35401</p></td>
    </tr>
  </tbody>
</table>
<br>
<p><em>
	Select Signature then Copy and Paste into your signature. Keep source formatting.</em>
</p>
<table>
		<tr>
		<td><a href="https://www.girlscoutsnca.org"><img border="0" width="175" height="85" src="https://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/logo/GSNCA-logo_email_s.png"></a>		
			<br>
		<span style="font-family: arial; font-size:12px"><strong>{name}</strong></span><br>
		<span style="font-family: arial; font-size:12px">{title}</span><br>
		<span style="font-family: arial; font-size:12px"><span style="color:#00ae58"><strong>Girl Scouts of North&#8211;Central Alabama</strong></span><br>
		<span style="font-family: arial; font-size:12px">{add1}</span><br>
		<span style="font-family: arial; font-size:12px">{add2}</span><br>
		<span style="font-family: arial; font-size:12px">800-734-4541</span></td>
	</tr>
	<tr>
		<td><span style="font-family: arial; font-size:12px"><strong>p:</strong> {phone}</span><br>
		<span style="font-family: arial; font-size:12px"><strong>c:</strong> {cell}</span> <br><span style="font-family: arial; font-size:12px"><a href="mailto:{email}" style="color:#00AE58; border-width:0px; border:0px;">{email}</a></span></td>
	</tr>
	<tr>
		<td><span style="font-family: arial; font-size:12px"><span style="color:#00ae58"><strong>Renew with Girl Scouts</strong></span><br>
		<span style="font-family: arial; font-size:12px"><a href="https://mygs.girlscouts.org/" style="text-decoration:none !important; text-decoration:none">Click here to learn more!</a></span></span></td>
	</tr>
	<tr>
		<td><span style="font-family: arial; font-size:12px"><span style="color:#00ae58"><strong>Join Girl Scouts</strong></span><br>
		<span style="font-family: arial; font-size:12px"><a href="https://www.girlscoutsnca.org/en/about-girl-scouts/join.html" style="text-decoration:none !important; text-decoration:none">Click here to Join today!</a></span></span></td>
	</tr>
	<tr>
		<td>
			<a href="https://girlscoutsnca.org" style="text-decoration:none !important; text-decoration:none"><img border="0" height="27" src="https://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/image006.png" width="28"></a> <a href="https://www.facebook.com/gsnca" style="text-decoration:none !important; text-decoration:none"><img border="0" height="30" src="https://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/image008.png" width="16"></a> <a href="https://twitter.com/girlscoutsnca" style="text-decoration:none !important; text-decoration:none"><img border="0" height="32" src="https://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/image010.png" width="25"></a> <a href="https://www.youtube.com/user/gsnca" style="text-decoration:none !important; text-decoration:none"><img border="0" height="29" src="https://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/image012.png" width="22"></a> <a href="https://www.instagram.com/girlscoutsnca" style="text-decoration:none !important; text-decoration:none"><img border="0" height="28" src="https://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/image016.png" width="22"></a> <a href="https://www.pinterest.com/gsnca/" style="text-decoration:none !important; text-decoration:none"><img border="0" height="31" src="https://www.girlscoutsnca.org/content/dam/girlscouts-girlscoutsnca/images/email/image020.png" width="25"></a>
		</td>
	</tr>
	   </table>
	</div></div></div></section>

