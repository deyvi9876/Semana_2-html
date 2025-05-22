<b> Bold text

<strong> Important text

<i> ftalic text

<em> Emphasized text

<mark> Marked text

<small> Smaller text

<del> Deleted text

<ins> Inserted text

<sub> Subscript text

<sup> Superscript text


<p>I am normal</p>
   <p style="color: red;">I am red</p>
   <p style="color: blue;">I am blue </p>    
   <p style="font-size: 50px;">I am big </p> 

   <h1 style="background-color: blueviolet;">This is a heading</h1>
   <h1 style="font-size: 300%;">esto es un titulo</h1>
   <h1 style="text-align: center;">titulo</h1>
    <p style="background-color: tomato;">This is a paragraph</p>
    <p style="font-family: Courier ;">This is a paragraph</p>
    <p style="font-size: 160%;">This is a paragraph</p>
    <p style="text-align: center;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque, unde totam! Assumenda, exercitationem magni adipisci porro voluptate velit praesentium sed repellendus unde inventore eius qui error eligendi natus corrupti? Pariatur.</p>

  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #10cef0;
    background-image: url('../_img/imagen_titulo.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;  

}

h1, h2, h3, p, a {
  color: #f4f5f5; /* Color para encabezados, párrafos y enlaces */
}

a {
  text-decoration: none;
  color: inherit; 
  transition: color 0.3s ease; 
}

a:hover, a:focus {
  color: #3498db; 
}


header, nav, main, footer, section, aside {
  padding: 20px;
  margin: 10px;
  border-radius: 8px; 
  box-shadow: 0 2px 5px rgba(8, 243, 212, 0.1); 
}


header {
  background-color: #400766;
  color: white;
  text-align: center;
  border-radius: 8px 8px 0 0; 
}


nav {
  background-color: #1f4770;
  padding: 10px 0;
}

nav ul {
  list-style-type: none;
  padding: 0;
}

nav ul li {
  display: inline-block;
  margin-right: 15px;
}

nav a {
  color: #eaf4f7;
  text-decoration: none;
}