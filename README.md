html, body {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  display: table;
  background-image: url(http://jonathano.com/img/background.jpeg);
  background-size: cover;
  background-position: center top;
}

div.container {
  position: relative;
  z-index: 9999;
  text-align: center;
  vertical-align: middle;
  display: table-cell;
}

body:after {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0;
  right: 0;
  opacity: 0.83;
  background: linear-gradient(#f1c40f 0%, #27ae60 100%);
}

div.container > * {
  font-family: 'uni_sansheavy_caps', sans-serif;
  color: #FFFFFF;
}

div.container > h1 {
  font-size: 37px;
}

footer {
  position: absolute;
  bottom: 5px;
  left: 0;
  right: 0;
  text-align: center;
  z-index: 9999999;
}

footer > * {
  font-family: 'uni_sansheavy_caps', sans-serif;
  color: #FFFFFF;
  text-decoration: none;
}

footer {
  font-family: 'uni_sansheavy_caps', sans-serif;
  color: #FFFFFF;
  font-size: 17px;
}

footer > a:hover {
  color: #bdc3c7;
}
