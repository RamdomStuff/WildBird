WildBird
========

A simple example of a ONLINE SPORTS Website!
<?xml version="1.0" encoding="utf-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
<head>
<title>WildBird Sports</title>

<link rel="stylesheet" type="text/css" href="new.css">

</head>
<body>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#news">Notícias</a></li>
<li><a href="#contact">Contato</a></li>
<li><a href="#about">Sobre nós</a></li>
</ul>
<a href="http://www.specialized.com/br/pt-br/home/">Clique aqui para acessar a página de nosso fornecedor</a><br>
<style>

ul
{
list-style-type:none;
margin:0;
padding:0;
}
{
display:block;
font-weight:bold;
color:red;
background-color:red;
width:120px;
text-align:center;
padding:4px;
text-decoration:none;
text-transform:uppercase;
}
a:hover,a:active
{
background-color:red;
}
a:link {color:black;}
a:hover {color:red;}
a:link {color:black;}    
a:visited {color:#480000 ;} 
</style>
<div class="img" >
 <a target="_blank" href="klematis_big.htm"><img src="cic.jpg" alt="Klematis" width="110" height="90"></a>
 <div class="desc">Cicling</div>
</div>
<div class="img">
 <a target="_blank" href="klematis2_big.htm"><img src="alpin.jpg" alt="Klematis" width="110" height="90"></a>
 <div class="desc">Alpinismo</div>
</div>
<div class="img">
 <a target="_blank" href="klematis3_big.htm"><img src="fit.jpg" alt="Klematis" width="110" height="90"></a>
 <div class="desc">Fitness</div>
</div>
<div class="img">
 <a target="_blank" href="klematis4_big.htm"><img src="advn.jpg" alt="Klematis" width="110" height="90"></a>
 <div class="desc">Aventuras</div>
</div>

<h1>Welcome to WildBird</h1>
<img class="thumbnail" src="bikes.jpg" width="107" height="90">
<img class="thumbnail" src="alpinismo.jpg" width="107" height="90">
<img class="thumbnail" src="fitness.jpg" width="107" height="80">
<img class="thumbnail" src="advent.jpg" width="116" height="90">

<hr />
<form name="cliente" action="cliente.php" method="get">
<table>
<tr>
<td align="right"><b>Nome:</b></td>
<td><input name="nome" size="50" maxlength="50" /></td>
</tr>
<tr>
<td align="right"><b>Telefone:</b></td>
<td>(<input name="ddd" size="3" maxlength="3" />)<input name=
"fone" size="8" maxlength="8" /></td>
</tr>
<tr>
<td align="right"><b>E-mail:</b></td>
<td><input name="email" size="40" maxlength="50" /></td>
</tr>
<tr>
<td align="right"><b>Foto:</b></td>
<td><input type="file" name="foto" size="30" maxlength="30" /></td>
</tr>
<tr>
<td align="right"><b>Sexo:</b></td>
<td>
<input type="radio" name="sexo" value="" />Masculino
<input type="radio" name="sexo" value="" />Feminino
</td>
</tr>
<tr>
<td align="right"><b>Faixa et&aacute;ria:</b></td>
<td><select name="faixa" size="1">
<option value="1">0-25</option>
<option selected="selected" value="2">26-39</option>
<option value="3">40-49</option>
<option value="4">+ de 50</option>
</select></td>
</tr>
<tr>
<td align="right"><b>Interesse:</b></td>
<td><input type="checkbox" name="interesse" value="1" />Ciclismo<br />
<input type="checkbox" name="interesse" value="2" />Fitness<br />
<input type="checkbox" name="interesse" value="3" />Alpinismo<br />
<input type="checkbox" name="interesse" value="4" />Aventuras<br /></td>
</tr>
<tr>
<td align="right"><b>+ informa&ccedil;&otilde;es:</b></td>
<td>
<textarea rows="5" cols="40" name="mensagem">
</textarea></td>
</tr>
<tr>
<td align="right"></td>
<td>
<input type="submit" value="Cadastrar-me" />
<input type="reset" value="Apagar dados" />
</td>
</tr>
</table>
</form>
<hr />
</body>
</html>
