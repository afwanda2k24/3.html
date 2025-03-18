<html>
<head>
 <html>
<head>
<meta>
  <title>sesi 3 Styling CSS</title>
  <style>
    section{border:1px solid blue;}
    body{margin:0;}
input{ color:red; background:blue; width : 100%;}
    #username{background:grey; margin:10px; }
    #sandi{background:green;padding : 5px 2px 3px 4px;}
.col-1-2{width:50%;}
.col-1-3{width:33.33%;}
 @media screen and (max-width: 700px) { [class*='col-'] { width: 50%; } }
 @media screen and (max-width: 450px) { [class*='col-'] { width: 100%; }}
 .row { width: 100%; display: table; table-layout: fixed; }
.row::after { content: ""; clear: both; }
[class*='col-'] { float: left;   word-wrap: break-word;}
.col-1-1 { width: 100%; }
.col-1-2 { width: 50%; }
.col-1-3 { width: 33.33%; }
.col-1-4 { width: 25%; }
.col-1-5 { width: 20%; }
.col-2-3 { width: 66.66%; }
.col-3-4 { width: 75%; }
.col-4-5 { width: 80%; }
@media screen and (max-width: 700px) {
[class*='col-'] { width: 50%; }
}
@media screen and (max-width: 450px) {
[class*='col-'] { width: 100%; }
 <html>
<head>
  <title> Pertemuan 3 Penggunaan dan Implementasi CSS</title>
  <link rel="stylesheet" href="3-1.css">
  <link rel="stylesheet" href="3-2.css">
</head>
  <body>
<header><a href="ipwija.ac.id"> Home </a></header>
<main> hi
<br/>
</main id="main" class="main">
<section>Halo Word</section>

    <section id="gambar" >
    <img src="edu.png" height="200" width="200">
    </section>

<section id="form" class="col-1-2">
<form>
<label>Username:</label><input type="text">
<label>Password:</label><input type="password">
<label>Warna:</label><input type="color">
<label>Dropdown:</label>
        <select>
          <option>1</option>
          <option>2</option>
        </select>
<input type="submit" value="cancel">
        <button> login</button>
      </form>
    </section>

    <section id="paragraf">
<p>
<h1> Pertemuan 2</h1>
<h2> HTML dasar </h2>
pertemuan 2, dasar HTML membuat paragraf <br/> sederhana dengan huruf <i>miring </i>,<b>Tebal</b>
</p>
  <ul>
    <li>1</li>
    <li>2</li>
  </ul>
  <ol>
    <li>satu</li>
    <li>dua</li>
  </ol>
</section>
<section id="table">
<h2>table</h2>
<table border="1">
<thead>
  <tr><th>jan </th><th>feb </th></tr>
</thead>
<tbody>
<tr><td>1 </td><td>2 </td></tr>
<tr><td>3 </td><td>4 </td></tr>
</tbody>
</table>
</section>


<footer>@2025</footer>
  </body>
</html>
}
  </style>
</head>
  <body>
<header></header>
    <main>
    <section id="paragraf" class="col-1-3">  <b>Hallo</b> <i> Pemrograman Web</i> </section>
   <section id="table" class="col-1-3"> 
   <table border="1">
    <tr><td>1</td><td>2</td> </tr>
    <tr><td>3</td> <td>4</td></tr>
   </table>
   </section>
   <section id="form" class="col-1-3">  
   <form>
     <label>username</label><input id="username" type="text">
    <label>sandi</label> <input  id="sandi" type="password">
     <input type="submit" value="login">
   </form>
   </section>
    </main>
  <footer></footer>
  </body>
</html>
 <title>pertemuan 2 HTML dasar</title>
</head>
 <body>
 <header><a href="ipwija.ac.id"> home </a>a<>/header>
 </main>
 <br/>
 </main>
 </selection>Hello World>/selection>
 <footer>@2025</footer>
 <section id="gambar">
  <img src="edu.png height="100" with="200">
   </section>
   <section id="from"
    <label>username:</label><input type="text">
  <label>password:</label><input type="password>
  <label>warna:>/label><input type="color">
  <label></>Dropdown:</label>
   <select>
    <option>1</option>
    <option>2</option>
   </select>
    <input type="submit"> value="cancel">
    <button>login </button>
   </from>
   </section>
    <p>
 <section id="paragraf">
   <h1>pertemuan 2</h1>
   <h2>HTML dasar</h2>
  pertemuan dasar HTML membuat paragraf <br/> sederhana dengan huruf <i/>, </i>, <b>Tebal</
  </p>
  <ul>
   <ii>1</ii>
  <ii>2</ii>
  </ul>
  <ol>
   <ii>satu</ii>
   <ii>dua</ii>
  </ol>
 </selection>
   <body>
  <section id="table">
   <table></h2>
   <thead>
   </thead> 
   <tr></th> jan <tr></tr> feb
    <tbody>
    <table broder="1">
     <tr></td>1 <td></td>2 </td></table>tr>
     <tr>3 </td><td></td>4 <td/></tr>
   </tbody>
   </table>
  </section>
   </html>
